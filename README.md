# Binaar website

One-page site for Binaar (بنار) with interactive 3D models of Faisal Jewel and Faisal Heights.

## Put it live on GitHub Pages (about 5 minutes)

1. Sign in at github.com and click **New repository**. Name it `binaar-website`, set it to **Public**, and click **Create repository**.
2. Click **uploading an existing file**, drag in `index.html`, `README.md` and `.nojekyll`, then click **Commit changes**.
3. Open **Settings → Pages**. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/binaar-website/`.

## Use your own domain (binaarpk.com)

In **Settings → Pages → Custom domain**, enter `binaarpk.com` and save. At your domain provider, add the DNS records GitHub shows you (four `A` records to GitHub's IPs, or a `CNAME` for `www`).

## Editing

Everything is in `index.html`: text, prices, phone number, and the 3D models (search for `Faisal Jewel:` and `Faisal Heights:` in the script).
Project photos load from the developers' official websites. Replace the `src` links with your own photos in an `images/` folder if you prefer.
