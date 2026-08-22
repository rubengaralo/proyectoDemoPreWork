# Project rules

## Calendar invitations require a heads-up (STRICT)

Never make a Google Calendar change that will email anyone without first telling
Ruben, in chat:

1. **Who** will receive an email (each address),
2. **What information** the email will contain (the event description/details
   they will see, summarized honestly — a calendar invite delivers the full
   event description to the guest's inbox),
3. and then **waiting for his explicit OK** before executing.

This applies to: creating events with attendees, adding or removing attendees,
and editing any event that has attendees (title, time, description changes all
re-notify guests by default).

Defaults when working with events that have guests:
- Use `notificationLevel: NONE` for edits unless Ruben explicitly chooses to
  notify.
- Keep sensitive or internal detail out of shared event descriptions; the
  attendee-facing description stays minimal. Full notes go in a private,
  attendee-free companion event or in repo docs.

Context: on 2026-08-22 an all-hands invite was sent to team members with the
full internal meeting design in the description, without warning that adding
guests triggers an invitation email. Ruben flagged it. This rule exists so it
never repeats.
