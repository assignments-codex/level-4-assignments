#### Objective

Two flows end to end: one read, one write.

#### Requirements

1. Server has POST /api/items that validates a non-empty title and returns 201 with the created row. On invalid input return 400 with { "error": "message" }.
2. Client has a small form to create an item. On success, show the new item. On error, show a friendly message.
3. Keep the Day 2 list working. Loading, success, and error states are visible.

#### Submission

Git repo link(s). Note what you validated on the server and on the client.

#### Rubric (20 pts)

- Read flow works 0-5
- Write flow works with 201 0-5
- Validation and error messages present 0-5
- Code organization is clear 0-5
