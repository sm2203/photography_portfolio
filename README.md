# photography_portfolio
This is my first attempt at learning HTML/CSS and creating a webpage for my photography portfolio.

## Notes
- The page uses a one-page scrolling layout with Home, About, and Portfolio sections.
- The design includes a sticky header, anchor navigation, a responsive photo grid, and a clickable lightbox modal.
- Navigation links scroll to each section using anchor links.
- The portfolio gallery loads images from the local `images` folder through a JSON file.
- Clicking any gallery image opens a full-size lightbox popup for preview.
- The popup includes an `X` button in the top-right corner to close it.

## Run locally
```bash
cd repositories/photography_portfolio
python3 -m http.server 8000
```
Then open `http://localhost:8000` in the browser.
