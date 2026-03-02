# Publish ShailenSense Signal to GitHub (Desktop + Phone)

## What to publish
- Phone web app (GitHub Pages): use `docs/`
- Desktop app download: upload `ShailenSense Signal.exe` as a GitHub Release asset

## Desktop EXE path
`otc-desktop-app/dist/ShailenSense-Signal-Luxury-v5/ShailenSense Signal-win32-x64/ShailenSense Signal.exe`

## Steps
1. Create a new GitHub repository (for example: `shailensense-signal`).
2. Upload/push this project with the `docs/` folder included.
3. In GitHub repo settings:
   - Open `Pages`
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/docs`
4. Save. Your phone web link will be:
   `https://<your-username>.github.io/<repo-name>/`
5. For desktop download:
   - Open `Releases` -> `Draft a new release`
   - Upload the EXE from the path above as a release asset.

## Notes
- A Windows `.exe` does not run on Android/iPhone directly.
- Phones should use the GitHub Pages link; users can add it to home screen.
