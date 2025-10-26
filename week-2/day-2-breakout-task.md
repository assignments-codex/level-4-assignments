#### Goal

Read data from Supabase with the Supabase JS client

#### Steps

1. Install the Supabase JS client and initialize it in your server code using env vars.
2. Implement GET /items that selects rows from your table and returns JSON.
3. Return 500 with a JSON error body on unexpected errors.
4. Extra practice if you want
   - implement GET /items/:id that returns 404 when not found
