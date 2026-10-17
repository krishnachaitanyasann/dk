# Wherever, Always ❤️
A private-feeling keepsake site for Krish & Danah, ready for GitHub Pages.

## Publish
1. Extract this ZIP on your computer.
2. Create a GitHub repository (for example `wherever-always`).
3. Upload **the contents of the extracted folder**, including `index.html`, `style.css`, `app.js`, `memories.json`, `media/`, and `audio/` to the repository root.
4. GitHub repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
5. Wait for GitHub Pages to publish, then open the URL shown there.

**Important:** GitHub Pages websites are public on the internet, even if you use a private repository (depending on plan). Do not upload secrets or genuinely private content without reviewing GitHub Pages visibility.

## Add future memories
Upload images or videos into `media/`, then edit `memories.json` by adding a record:
`{"file":"media/new-photo.jpg","type":"photo","date":"2026-10-17","name":"Our day"}`
For videos, use `"type":"video"`. Keep the JSON comma-separated and valid. Images keep their original aspect ratios.

## Diary and future letters
These work locally in each person's browser. GitHub Pages alone does **not** sync diary data between Krish and Danah. Use Export diary + letters to download a JSON backup and share it; Import restores it on another browser. Export regularly, because clearing browser storage deletes local entries. The future-letter date lock is only a visual interface lock, not encryption.

## Video formats
Original `.MOV` clips are included. Playback depends on each visitor's browser and the video codec. For broader compatibility, convert MOV to MP4 (H.264/AAC) and change the corresponding filename in `memories.json`.

## Soundtrack
Add a licensed audio file at `audio/soundtrack.mp3`; music plays only after a visitor taps the button.

## Notes
The original archive included HEIC photos. These were converted to browser-friendly JPG where possible. File date is taken from available EXIF data; undated files are kept but not assigned invented dates.
