# Solutions Consulting Cockpit (concept mockup)

A single-page, self-contained concept mockup of a daily workspace for Solutions
Consultants. Hosted only so it can be used as the asset in an unmoderated
usability test.

**Everything in it is fictional.** Every company, person, figure, stakeholder,
calendar entry, deal signal and recommended action is invented. Sesame Street
Inc., Globex, Acme Mutual, Initech, Hooli Health, Vandelay Industries, Cyberdyne
Systems and Wonka Retail are not customers. No real numbers appear anywhere.

## What it is

Four zones, read left to right:

| Zone | Cadence | Contents |
|---|---|---|
| Visibility | Quarterly | Attainment headlines and plan components |
| Schedule | Daily | Clickable day calendar, three days of agenda |
| Execution | Daily | Per-meeting brief: opportunity, stakeholders, commitments, MEDDPICC assessment, Ask AI |
| Intelligence | Weekly | Quarter forecast and the open opportunities that could be worked |

A fifth zone, Coaching, is a work-in-progress placeholder.

## Notes for anyone poking at it

- No build step, no dependencies, no network calls. Open `index.html`.
- Light and dark themes, toggled with the icon in the title bar.
- Several controls are intentionally inert: the two Visibility dropdowns, the
  "Build it" and "Open brief" buttons, and free-text replies in Ask AI. The
  Ask AI suggestion chips do return written answers.
- The MEDDPICC panel follows a 0 to 5 maturity rubric. Score descriptions are
  looked up per element per score rather than hard-coded, so changing a score
  changes the wording.
- Chart colours come from a validated palette: a one-hue ordinal ramp for
  maturity, a two-hue categorical pair elsewhere, and reserved status colours.
  Nothing relies on colour alone.
