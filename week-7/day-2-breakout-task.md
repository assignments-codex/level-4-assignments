#### Goal

Connect the frontend to one endpoint and render results safely.

#### Steps

1. In /server, add GET /api/items to return rows from items.
2. In /client, fetch /api/items using useEffect and AbortController.
3. Show three states: loading, empty, error.
4. Confirm local CORS is correct. Adjust if fetch fails.
5. Optional: deploy server to Render, client to Netlify. Set VITE_API_BASE to the live API.
