# Review Agent — Landing Page

Static landing page for **Review Agent** by 4 The People Community Solutions.

Review Agent texts clients ~2 hours after an appointment, routes happy clients
to the business's Google review link, and surfaces unhappy clients privately
before they post publicly.

## Files
- `index.html` — the whole page (inline CSS, no build step)
- `demo.mp4` — product demo video
- `poster.jpg` — video poster frame

## Local preview
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy
Static site, no framework. On Vercel: import the repo, leave framework as
"Other", output directory = root. Nothing to build.

## Before going live
- [x] Real contact email: ebonee@4thepeoplecommunity.com
- [ ] Swap the mailto CTA for a real booking link (Calendly, etc.)
- [x] Real logo + favicon added (logo.png, favicon.png)
