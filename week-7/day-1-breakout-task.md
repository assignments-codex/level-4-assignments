#### Goal

Plan the integration and get both apps running locally.

#### Steps

1. Create folders: /client (React) and /server (Express).
2. Add .env.example to both apps. Do not commit real secrets.
3. Create a Supabase project and one table items with fields: id, title, created_at.
4. In /server, add GET /health that returns { "ok": true }.
5. Enable CORS in /server for http://localhost:5173.
6. In /client, render a placeholder view and read VITE_API_BASE from env.
7. Confirm: client starts, server starts, /health responds.
