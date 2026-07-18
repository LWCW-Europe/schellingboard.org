# Contributing

This repo hosts the static marketing site for SchellingBoard
(`index.html`, `screenshots.html`, `screenshots/`). The app itself lives in
[LWCW-Europe/schelling-board](https://github.com/LWCW-Europe/schelling-board).

## Taking screenshots

General setup:

* Firefox
* Responsive Design Mode (Ctrl+Shift+M)
* Desktop shots: "Laptop with touch" device, 1280x950
* Mobile shots: "Galaxy Note 9 / Android 7" device
* Hide the Next.js developer tools overlay before capturing

Save files into `screenshots/` using the exact file names below, then update
`screenshots.html` (and `index.html`'s hero image / OpenGraph tags, if the
hero shot changed).

## Screenshot checklist

Go through the app end-to-end and (re)capture each of these when the UI
changes materially. Check off `[ ]` as you go.

### Desktop (1280x950)

- [ ] `home-multi-event.png` — Home page listing multiple events with phase, dates, and quick links
- [ ] `proposals-browse.png` — Proposal list with search, filters, and sortable columns
- [ ] `proposal-edit.png` — Session proposal form (title, description, hosts, duration)
- [ ] `proposals-vote.png` — Proposal list with Interested / Maybe / Skip voting
- [ ] `quick-voting.png` — Quick Voting mode, one proposal at a time
- [ ] `schedule-grid.png` — Drag-and-drop scheduling grid with room photos (also used as the site hero / OG image)
- [ ] `session-details.png` — Session detail popup (host, location, time, attendees, description)
- [ ] `add-session.png` — Form for adding a session directly to the schedule
- [ ] `attendees.png` — Searchable attendee directory with avatars and host badges
- [ ] `participant-profile.png` — Participant profile page (bio, proposals, sessions attending)
- [ ] `edit-profile.png` — Edit profile form (name, pronouns, avatar, Markdown bio)
- [ ] `admin-events.png` — Admin panel listing all events with a Manage button
- [ ] `admin-event-settings.png` — Admin event configuration form (name, dates, timezone, rules)

### Mobile (Galaxy Note 9)

- [ ] `mobile-schedule.png` — Scheduling grid rendered on a phone screen
- [ ] `mobile-session-details.png` — Mobile session detail popup with closed-session warning

After capturing, open `screenshots.html` locally and click through the
lightbox to confirm captions still match what's on screen.
