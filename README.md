## Houston Is a Hockey Town — Website

### Quick start
- Open `index.html` in your browser. It will redirect to `home.html`.
- For a local server (better for fonts and future assets), run one of:
  - Python 3: `python3 -m http.server 5500` then open `http://localhost:5500/`
  - Node (if installed): `npx serve -l 5500 .` then open `http://localhost:5500/`

### Trailer embed
- In `home.html`, find the trailer click handler near the bottom.
- Replace `YOUR_YOUTUBE_ID` with your actual YouTube video ID (the part after `v=`).

### Deploy options
- GitHub Pages: push this folder to a repo and enable Pages (root). Entry file is `index.html`.
- Netlify / Vercel: drag-and-drop the folder; or connect the repo. No build step required (static).

### Customizing content
- Edit text directly in `home.html`. Image placeholders allow local uploads on the page for preview.
- Colors, fonts, and layout are defined inline in the `<style>` block in `home.html`.

### Notes
- The nav uses smooth-scrolling with an offset for the fixed header.
- If you later split CSS/JS to separate files, update references accordingly.

