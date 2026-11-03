# Awwbree's Virtual Closet 🎀

A functional iPhone-friendly 3D wardrobe starter, built with Vite and Three.js.

## Run on a computer
1. Install Node.js 20.19+ or 22.12+.
2. In this folder, run `npm install` then `npm run dev`.
3. Open the local URL printed in your terminal.

## Publish to Vercel (free-tier eligible)
1. Create a GitHub repository and upload `index.html`, `src.js`, `style.css`, `package.json` and this README.
2. Sign in at https://vercel.com and select **Add New → Project**.
3. Import your repository. Framework preset: **Vite**; build command `npm run build`; output directory `dist`.
4. Deploy and open the HTTPS URL on your iPhone.
5. Safari → Share → Add to Home Screen.

## Important limitations
- Starter avatar is geometry-based, not a personalized Sims mesh. Replace with a licensed GLB avatar later.
- Clothing is procedural geometry, not simulated fabric. Photos are wardrobe thumbnails linked to colorable garment templates, not automatic 3D reconstruction.
- Browser localStorage is per device/browser and has limited space. Use Export Backup regularly. No cloud sync or account login in this starter.
- Hosting does not automatically create cloud storage. Supabase integration is a separate next step.
- Do not upload proprietary Sims `.package` files directly. Convert only assets you have permission to use.
