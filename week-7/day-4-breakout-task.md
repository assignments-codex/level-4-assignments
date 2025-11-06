#### Goal

Protect one write action.

#### Steps

1. In /server, add middleware that checks Authorization: Bearer <ADMIN_TOKEN> from env. Return 401 if missing, 403 if wrong.
2. Protect POST /api/items with the middleware.
3. In /client, prompt once for the token and attach it in the request header for protected calls.
4. Show a clear message on 401 or 403. Hide or disable the protected action when not authorized.
