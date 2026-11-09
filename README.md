# My Story — Personal Portfolio

A free, static, mobile-friendly personal website with Azure-inspired navigation. Bio is the homepage; Travel has a story gallery and slide-out story panels. Other sections are reserved for future updates.

## Preview locally

Open `index.html` in your browser. Alternatively, from this folder run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000 .

## Personalize

1. Open `content.js` in any text editor.
2. Replace `Your Name`, Bio text, highlights, and travel story text with your real information.
3. Put your own JPG/PNG/WebP photographs in `assets/photos/` (create that folder).
4. Update image paths in `content.js`, for example `portrait: "assets/photos/portrait.jpg"` and `image: "assets/photos/italy.jpg"`.
5. Add more destinations by copying an object inside `travel.destinations`, changing its `id` to a unique value.
6. Reload the page. No build process required.

**Privacy:** Avoid sharing private addresses, identification details, or travel plans you don't want publicly visible. Photos are not included except illustrated placeholders.

## Publish free with GitHub Pages

1. Create a public GitHub repository, for example `my-story`.
2. Upload the contents of this folder (not the outer folder) to the repository root.
3. Go to repository **Settings → Pages**.
4. Choose **Deploy from a branch**, `main`, `/ (root)`, and Save.
5. Your website should appear at `https://YOUR-USERNAME.github.io/my-story/` once deployed.

This site works on GitHub Pages without server-side code. The optional Google Fonts stylesheet requires an internet connection; fallback fonts work offline.
