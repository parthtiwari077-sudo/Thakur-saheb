# Classified Files: Shikhar Singh

A responsive, static HTML/CSS/JavaScript friendship-gift website. It has no npm dependencies or build step.

## Run locally

1. Extract this folder.
2. Double-click `index.html` to preview, or use VS Code Live Server for best local video behavior.
3. Keep the `media/` folder beside `index.html`.

## Deploy to Vercel

1. Upload the contents of this folder (including `index.html`, `styles.css`, `app.js`, and `media/`) to a GitHub repository.
2. Import the repository in Vercel.
3. Framework preset: **Other**. Build command: leave empty. Output directory: `.` (or leave the default if Vercel detects static files).
4. Deploy.

## Important limitations

- This is a static front-end version and does not include a secure admin login or backend.
- Media uploaded using the Add Photos / Add Videos buttons is only a browser preview and disappears when the page is refreshed. Those files are not uploaded to Vercel or a server.
- The friendship message editor saves to the current browser's local storage only.
- Files in `media/` are public when deployed. Do not include private media unless you are comfortable with anyone who has access to the deployed site viewing those files. For persistent uploads and private access, integrate a backend such as Supabase with correctly configured authentication, storage policies, and database policies.
- The site uses Google Fonts when internet access is available; fallback fonts are provided.
