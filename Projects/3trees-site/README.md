# 3 Trees Contact Hub

- index.html: the page guests land on (Yasmine chat/voice bot, call, Facebook, Instagram, Google review)
- qr.html: QR poster. The QR code always points to the site's own address (the folder holding index.html), so it is correct automatically once published.
- assets/logo.png: logo

## Publish on GitHub Pages
1. github.com → New repository (e.g. 3trees-hub), Public.
2. "uploading an existing file" → drag in index.html, qr.html, README.md and the assets folder → Commit.
3. Settings → Pages → Source: Deploy from a branch → main / (root) → Save.
4. After ~1 minute the site is live at https://<username>.github.io/<repo>/
5. Open https://<username>.github.io/<repo>/qr.html → Download QR (PNG) or Print poster.

## Test locally
In this folder run: python3 -m http.server 8000, then open http://localhost:8000
(The QR made locally points to localhost; generate the final QR from the published qr.html.)

## Chatbot colour
Set in Voiceflow → Interfaces/Widget. Brand brown #6E4F2C, green #2F6B1F.
