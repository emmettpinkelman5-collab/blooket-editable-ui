# Blooket Editable UI

A screenshot-inspired, single-page Blooket-style interface. It uses CSS and text only; it does not fetch or include other pictures.

## Pages and links

- The **Games** item in the profile dropdown on the My Sets screen opens the guide page.
- The **Blooket** link on that page opens the recreated My Sets screen.
- **Change page** or **Settings** opens the editor. Update the profile name, set title, logo text, plays, and question badge.
- Add one or more `.html` files in Settings. They are stored in this browser, listed on the Games page, and can be opened from the recreated My Sets page in a sandboxed preview.

Settings and uploaded files are local to the browser using `localStorage`; they are not uploaded to GitHub. Open `index.html` directly or enable GitHub Pages to try it.
