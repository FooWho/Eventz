Events
======

The events service for Velociraffle.

Service has the following endpoints:

GET: /events
Returns a list of all events

POST: /events
Creates a new event, the details of which are described by JSON in the request payload.  Returns the newly created event.

GET: /events/{id}
Returns the event specified by {id}

POST: /events/{id}
Updates the event specified by {id} to match the event specified in the request payload.  Returns the modified event.

DELETE: /events{id}
Deletes the event specified by {id}.