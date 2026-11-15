# Shottas AR — GitHub Pages starter

This project shows the supplied animation (with its original audio) when the printed Shottas silhouette is recognized by your phone camera.

## Create the site
1. Create a **public** GitHub repository named `shottas-ar` at https://github.com/new (do not initialize with a README).
2. Extract this ZIP, open the `shottas-ar` folder, and upload its files to the **root** of the new repository (not the folder itself).
3. **Important:** `targets.mind` is not included yet. To generate it, open https://hiukim.github.io/mind-ar-js-doc/tools/compile/ and compile `reference-art.png` (or later a clear straight-on photo of your final printed artwork). Download the resulting `targets.mind` and upload it to the repository root. The AR tracking will not work until this file exists.
4. Go to GitHub repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. After deployment, visit `https://YOUR-USERNAME.github.io/shottas-ar/` on your phone. Grant camera permission and tap Enable Sound.

Files: `index.html` (AR viewer), `shottas.mp4` (video with original audio), `reference-art.png` (tracking reference).

The artwork remains black, white and red. No changes to the Paul Campbell AR project. Mobile browsers may require a tap to enable sound.
