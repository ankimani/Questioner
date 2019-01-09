# Questioner
Questioner helps the meetup organizer prioritize questions to be answered.
This part will cover the API endpoints for the Questioner
the following endpoints will be covered:
	1. Endpoint : POST /meetups  -Create an meetup record.
    2. GET /meetups/<meetup-id>  -Fetch a specific meetup record.
	3. GET /meetups/upcoming/    -Fetch all upcoming meetup records.
	4. GET /meetups/upcoming/  -Fetch all upcoming meetup records.
	5. POST /questions -Create a question for a specific meetup.
	6. PATCH /questions/<question-id>/upvote -Upvote (increase votes by 1) a specific question.
	7. POST /meetups/<meetup-id>/rsvps -Respond to meetup RSVP.