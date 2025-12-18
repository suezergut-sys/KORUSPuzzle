# KORUS Puzzle

This repository hosts two HTML pages for a sliding-puzzle game built around the `puzzle.jpg` image.

## Files
- **index.html** – Modern puzzle UI that loads `puzzle.jpg` into a 4x4 sliding puzzle with shuffle, solve, hint, and celebration behaviors.
- **puzzle_game_7_years_korus.html** – Alternate layout of the same puzzle for a "7 years with KORUS" theme, using the same controls and image.

## How to run locally
- **Open directly:** double-click either HTML file to open it in your browser.
- **Serve locally:** run `python -m http.server` in the repository root and open `http://localhost:8000/index.html` (or the other file) in your browser.

## Feature highlights
- Shuffle button to randomize the tiles.
- Solve button to restore the completed image.
- Hint toggle that shows or hides the reference picture.
- Celebration effect when the puzzle is finished.

## Changing the puzzle image
Replace `puzzle.jpg` in the repository root with your own image while keeping the same filename. Both HTML files read the image from that path; if you prefer a different name, update the `background-image: url("puzzle.jpg")` rule in each file accordingly.

## Browser support
Developed with modern Chromium- and Firefox-based browsers in mind; recent versions of Edge, Chrome, and Firefox should render correctly. Internet Explorer is not supported.
