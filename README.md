# ALICE Website — Vercel Deployment

This project is prepared for direct deployment to Vercel.

## Easiest deployment: GitHub + Vercel

1. Create a new GitHub repository.
2. Upload the **contents** of this project folder (not the outer download folder) to the repository.
3. In Vercel, choose **Add New → Project** and import that GitHub repository.
4. Vercel will detect Vite automatically. The included `vercel.json` confirms these settings:
   - Build command: `npm run build`
   - Output directory: `dist`
5. Click **Deploy**.

## Direct deployment with Vercel CLI

If Node.js is installed on your computer, open a terminal inside the extracted project folder and run:

```bash
npm install
npx vercel
```

Follow the prompts. For a production release, run:

```bash
npx vercel --prod
```

## Important

- Do not upload `node_modules`; Vercel installs packages automatically.
- The project has already been verified using `npm run build`.
- The contact form currently presents an on-page confirmation. Connect it to your CRM, email service, or form endpoint before the final client launch.
- Replace visual/client proof assets only after you have permissions and final approved materials.
