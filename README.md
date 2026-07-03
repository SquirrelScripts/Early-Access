# Early-Access

Landing page for early-access signups, served via GitHub Pages at
https://squirrelscripts.github.io/Early-Access/

Click and email-capture events are logged to the `smoke_events` table in
Supabase (project `vgwpvjiuqdadycwnjcla`, anon insert-only via RLS).

The stats dashboard at `dashboard.html` is gated behind the owner's
Supabase sign-in; the anon key can only insert events, never read them.
