# API Contract

## Endpoint
POST /predict

## Request
Content-Type: application/json

{
  "ticket_text": "Description of the IT issue"
}

## Response

{
  "suggested_solution": "Recommended solution",
  "similar_tickets": [
    {
      "ticket": "Historical ticket description",
      "solution": "Historical solution"
    }
  ]
}

## Responsibilities
- Frontend: collect input and display the response.
- Backend: validate input, call the AI engine, and return JSON.
- AI engine: find similar tickets and recommend solutions.

## Error handling
- Empty ticket descriptions must be rejected.
- Invalid requests must return a useful error message.
