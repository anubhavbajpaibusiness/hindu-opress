# Hindu College Voicebox

Anonymous complaint & suggestion box for the Hindu College Students' Union
(University of Delhi). Static frontend in `public/`, three serverless API
routes in `api/`, shared helpers in `lib/`, and data stored in Upstash Redis.

- **No login, no name, no trace** for students — every submission gets a
  tracking code (e.g. `HIN-7F3K2Q`) so the student can look up status and
  any reply later.
- **Union desk** is protected by a single password and gives the office
  bearers status changes, replies, and delete.

## Deploy in 5 steps (under 10 minutes)

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "hindu-voicebox"
git branch -M main
git remote add origin https://github.com/anubhavbajpaibusiness/hindu-opress.git
git push -u origin main