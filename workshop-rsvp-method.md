# Totally simple way we use meetup to manage workshop RSVPs

## The set up

1. Use the [template](template.md).
- Under **RSVP Settings**, Set `Limit to [x] guests` (where **x** is the number of facilitators).
- Don't set `Allow members to go with up to [y] guests`.
- Leave `Members can RSVP starting` as `Now` and leave `Members can RSVP until` as `When the Meetup starts` (or set it to a day or two before).

The result of this is that everyone who RSVPs will be immediately added to the **Waiting List**.

## The RSVPs

1. Use the [warm-up questions template](warm-up-questions-template.md) and add a filled-in copy to the repo for the workshop.
- For the first **z** people (where **z** is the workshop attendee limit), send the warm-up questions message using meetup's messaging functionality.
    - Go to the Waiting List on the event page of the meetup.
    - Open the first **z** people's profiles in new tabs (their photo and name is a link to their profile).
    - For each one click the **Message** link (opens a modal).
    - Copy, Paste in your warm-up questions message, then hit Send (`Shift + Enter`).
    - Note that meetup tends to throttle sending messages like this, so you might need to take a 10 minute break between batches.
- Start a new (secret) Gist, and Paste in your warm-up questions message as a new file.
- As people RSVP:
    - change their RSVP on meetup to `Yes`;
    - Copy, Paste their name and response as a comment on the Gist. This lets us keep a history of RSVPs. Add No RSVPs here too.
- If there are any spots left to fill to make up **z** attendees, make a new warm-up questions message with new dates and send another round of RSVPs.
