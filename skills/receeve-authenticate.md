---
name: Authenticate to the Receive Client API
description: Obtain an OAuth2 Bearer token and call any Receive (Receeve) operation.
api: openapi/receeve-openapi-original.yml
operations: [getOauth2Token]
---

# Authenticate to the Receive Client API

Every Receive operation requires a short-lived OAuth2 Bearer token.

## Steps
1. Base64-encode your `client_id:client_secret` (issued by InDebted).
2. Call **`getOauth2Token`** — `POST /v1/oauth2/token` on your environment host
   (demo: `https://api.receive-demo.com`) with headers:
   - `Authorization: Basic <base64(client_id:client_secret)>`
   - `Content-Type: application/x-www-form-urlencoded`
3. Read `access_token`, `token_type` (`Bearer`) and `expires_in` (3600) from the JSON response.
4. Send `Authorization: Bearer <access_token>` on every subsequent call. The token is
   reusable until it expires — cache it and refresh only near expiry.

## Rules
- All resource paths are tenant-scoped: `/v1/{clientId}/...`. Use your assigned `clientId`.
- On `401` re-authenticate; on `429` (throttled) back off and retry.
