# Fire.net CFO Dashboard

A static CFO dashboard for Fire.net. It is ready to deploy on Vercel as a static site.

## Vercel
1. Import this GitHub repository into Vercel.
2. Select the `cfo-dashboard` branch for the first deployment, or merge it into `main` first.
3. Set **Root Directory** to `cfo`.
4. Framework Preset: **Other** / static site.
5. Build Command: leave empty.
6. Output Directory: `.`
7. Deploy.

## Firebase next
The UI is intentionally separated from the data layer. The next production step is to add Firebase Authentication + Firestore and replace demo transaction data with live Firestore queries.

## WhatsApp next
After Firebase is live, the WhatsApp CFO bot can write/read the same Firestore collections.

## Important
The dashboard contains management figures supplied during the CFO intake. The six-month trend is explicitly illustrative until historical monthly data is entered.
