# Wadke Associates – Website

Static website for Wadke Associates, Interior Designer in Virar West, Vasai-Virar.
Plain HTML/CSS/JS – no build step.

## Run locally
    python3 -m http.server 8000   # then open http://localhost:8000

## Deploy on GitHub Pages
Repo → Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)`.

## Edit
- Text, phone number, address: `index.html`
- Videos: put MP4 (H.264 + AAC, under ~10 MB) in `videos/` and add a `<figure class="vd">` block like the existing ones.
- WhatsApp number: search `918999500841` in `index.html`.
