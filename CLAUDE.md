# Fairway Ledger

Single-file web app (`index.html`) backed by Firebase (Firestore + Auth, project `fairway-ledger-3bad6`).
Remote: https://github.com/matthewfix23/Fairway-Ledger (branch `main`).

## Git workflow

After every change to the app, commit and push to `origin main` without asking:
- Use a short, descriptive commit message (not "Update index.html").
- Only commit files that belong to the app; never commit secrets beyond the public Firebase web config already in `index.html`.
- If the push fails (auth, conflict), stop and tell the user instead of forcing.

## Finding git

Git for Windows is installed at `C:\Users\fixmp\Git\cmd\git.exe`. If `git` isn't found on PATH (the shell may predate the install), use that full path.
