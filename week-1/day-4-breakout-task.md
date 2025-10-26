#### Goal
Add validation and consistent errors

#### Steps
1. Validate incoming data for POST and return 400 on bad input.
2. Centralize errors in a helper or middleware that returns { "error": "message" }.
3. Extra practice if you want
   - add a timing log for each request
