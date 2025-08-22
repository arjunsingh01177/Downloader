```markdown
# Safe Audio Downloader

This is a minimal, legal, educational example of a small web app that lets a user paste a direct audio file URL and download it. It is explicitly intended for downloading audio you own or audio that is explicitly licensed for redistribution (public domain / Creative Commons with redistribution permissions).

Important: Do NOT use this app to download copyrighted music or content you do not have permission to download.

Features:
- Validates that the remote resource is audio (Content-Type audio/*).
- Enforces a maximum file size.
- Streams the audio to the browser as an attachment.

How to run:
1. Install Node 18+.
2. npm install
3. npm start
4. Open http://localhost:3000 and paste a direct mp3/wav URL.

Notes & next steps:
- Add OAuth or API-based integrations to only allow downloads from providers that permit it.
- Add rate-limiting and authentication to prevent abuse.
- Consider server-side caching and virus scanning if you plan to accept arbitrary files.
```