# Student Dashboard

A dark, responsive personal assignment dashboard for GitHub Pages.

## Included
- 19 starter assignments across six classes
- Assignment creation, editing, deletion and status changes
- Priority, due date, notes, search, filtering and sorting
- Completion, remaining-work and awaiting-approval counters
- Per-class counts and overall progress
- JSON backup export
- Browser storage using `localStorage`

## Publish with GitHub Pages
1. Create a GitHub repository named `student-dashboard`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. GitHub will provide the published website URL.

## Important: cloud sync
This starter currently saves data in the browser on the device being used. True cloud sync needs a backend and user authentication. GitHub Pages is static hosting; it does not provide a database.

A recommended next step is a private Supabase project:
- Enable email/password authentication.
- Create a table for assignments, with a user ID ownership column and row-level security.
- Add the Supabase project URL and public anon key to the app.
- Replace the local save/load functions with authenticated Supabase reads and writes.

Do not put a Supabase service-role key or other secret in this public repository. The public anon key is intended for browser use only when row-level security is correctly configured.

## Starter assignment notes
Two Spanish assignments are preloaded as **Awaiting approval** because they were reportedly completed but marked late. `U2 Reading: Mateo` is preloaded as **Verify submission** because the gradebook note suggested a possible missing name. These remain part of the 19 gradebook items and are tracked separately from completed/graded work.
