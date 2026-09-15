# Upload instructions

The folder is ready for the GitHub profile repository `isk0rka/isk0rka`.

## Browser method

1. Open <https://github.com/isk0rka/isk0rka> and sign in.
2. Choose **Add file → Upload files**.
3. Upload `README.md` and `assets/banner.jpg` from this package.
4. Confirm that GitHub shows these paths before committing:
   - `README.md`
   - `assets/banner.jpg`
5. Use the commit message `Redesign profile README` and commit to `main`.
6. Open <https://github.com/isk0rka> and verify the profile preview.

## Git method

Run these commands from a folder where you want to keep the repository:

```bash
git clone https://github.com/isk0rka/isk0rka.git
cd isk0rka
cp /absolute/path/to/this/package/README.md ./README.md
mkdir -p assets
cp /absolute/path/to/this/package/assets/banner.jpg ./assets/banner.jpg
git add README.md assets/banner.jpg
git commit -m "Redesign profile README"
git push origin main
```

## Optional personal links

The README contains a commented placeholder under **Minecraft / Content Creation**. Replace `YOUR_YOUTUBE_URL` and `YOUR_STREAM_URL` with verified public channel links, then remove the surrounding HTML comment markers.

Do not add a private email address to a public profile README.

`assets/banner.png` is also included as the full-resolution source-quality version; the README uses the smaller `banner.jpg` for faster loading.
