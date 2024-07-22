# Bugbook

## Getting Started

Install necessary packages before running the app:

```bash
npm install
```

To run the development server locally:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the
result.

## Deploy on Vercel

You can refer to the video url below for the quick deployment guide through
Vercel:

[https://www.youtube.com/shorts/HVhou1CGa1c](https://www.youtube.com/shorts/HVhou1CGa1c)

_Diregard the creation of repository as we already have a repository for this
project._

**P.S. Don't for get to add the environment variables before deploying the
application**

## Commit Guide

_In general the pattern mostly looks like this:_

**type(scope❓): subject #scope is optional; multiple scopes are supported
(current delimiter options: "/", "\" and ",")**

- **build:** Changes related to build processes.
- **chore:** General maintenance and tasks that are not tied to a specific
  feature.
- **ci:** Updates to CI/CD configuration and scripts.
- **docs:** Documentation updates or additions.
- **feat:** New features or enhancements.
- **fix:** Bug fixes.
- **perf:** Performance improvements.
- **refactor:** Code refactoring without changing its behavior.
- **revert:** Reverts a previous commit.
- **style:** Code style changes (formatting, indentation).
- **test:** Adding or modifying tests.

### ENV EXAMPLE

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=

SCRIBEMATIC_BASE_URL=
SCRIBEMATIC_API_KEY=

OPENAI_API_KEY=
```
