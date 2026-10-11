# gym-plan

A mobile workout tracker in Persian (RTL) for a 4-week, 3-day full-body program. It is one static HTML file, with no build step and no backend.

**Live:** https://mohammad78sd.github.io/gym-plan/

## Features

- **Choose who and when:** person (محمد / مهدی), week (1–4) and day (A / B / C), plus an info tab
- **Exercise cards:** sets, reps, rest, notes and a looping SVG animation of each movement
- **Logging:** tap a set to mark it done, which starts a rest timer that vibrates when time is up; log weight and reps for each exercise, with "last time" shown
- **Weekly progression:** RIR targets each week, with an extra set in week 3
- **Body log:** weekly weight and waist
- **Backup:** export the log as JSON, copy it as text, or import it again
- **Optional sync:** auto-saves to a private GitHub Gist, one file per person, using a gist-only token stored on the device

## Data

Logs are kept in each phone's `localStorage`. The GitHub token is never in this repo. Each user pastes their own token into the page once.

## Setup on a phone

1. Open the live link and use **Add to Home Screen**.
2. Pick your name at the top.
3. Optional: **اطلاعات → ذخیره‌ی خودکار در GitHub**, then paste a fine-grained token that has only **Gists: Read and write**.
