# Deploy from a phone

## 1. Create the GitHub repository

1. Open GitHub in Chrome.
2. Tap your profile photo → **Your repositories**.
3. Tap **New**.
4. Repository name: `delta-exchange-product-dossier`
5. Set it to **Public**.
6. Do not add a README, license or `.gitignore` because the package already contains a README.
7. Tap **Create repository**.

## 2. Upload the project

1. Extract the ZIP on your phone.
2. Open the new repository.
3. Tap **Add file → Upload files**.
4. Upload the contents inside the extracted folder. Do not upload the ZIP itself.
5. Keep the folder structure exactly as supplied: `assets`, `data`, `downloads`, and the HTML files must be at the repository root.
6. Commit directly to `main` with the message: `Launch Delta Exchange Product Dossier`.

GitHub mobile uploads may limit the number of files. Upload in batches if required, but preserve the paths.

## 3. Deploy with Vercel

1. Open Vercel and sign in with GitHub.
2. Tap **Add New → Project**.
3. Import `delta-exchange-product-dossier`.
4. Framework preset: **Other**.
5. Leave Build Command empty.
6. Leave Output Directory empty.
7. Tap **Deploy**.

## 4. Verify before sharing

Open these routes:

- `/`
- `/evidence`
- `/methodology`
- `/about`
- `/downloads/delta-exchange-app-review-intelligence.pdf`
- `/downloads/delta-exchange-adversarial-audit.pdf`

Check on your phone and desktop. Then use LinkedIn Post Inspector to refresh the social preview after deployment.
