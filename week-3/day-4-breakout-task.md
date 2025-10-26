#### Goal

Guard one route and add logs

#### Steps

1. Add a header-based guard that checks x-api-key for one protected route.
2. Add a request logger that prints method, path, and elapsed ms.
3. Extra practice if you want
   - return a clear 401 JSON object on failure
