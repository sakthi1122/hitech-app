# Hi-Tech Service - iPhone web app (test build)

Installable web app (PWA) for iPhone: jobs list, new job, job detail, payments. Talks to the Firebase **test** project.

## Install on iPhone
Open the site in Safari -> Share -> **Add to Home Screen**.

## Accounts (Firebase console -> Authentication -> Users -> Add user)
| Email | Role |
|-------|------|
| owner@hitech.test | Owner |
| desk@hitech.test | Front Desk |
| tech@hitech.test (or any other email) | Technician |

The sign-in email decides the role. Edit `owners` / `frontDesk` in `index.html` to change it.
Authentication -> Sign-in method -> turn on **Email/Password** (and turn off sign-up).
