# Host your Sada Vedic Apps website on GitHub (beginner guide)

You already have the website files in the `website` folder.
GitHub can show them on the internet **for free** using **GitHub Pages**.

After hosting, you will use:

| App Store field | Page on your site |
| --- | --- |
| **Support URL** | `https://YOUR_USERNAME.github.io/sada-vedic-apps/support.html` |
| **Privacy Policy URL** | `https://YOUR_USERNAME.github.io/sada-vedic-apps/privacy.html` |

Replace `YOUR_USERNAME` with your GitHub username.

---

## What you need

1. A free [GitHub](https://github.com) account
2. About 10–15 minutes
3. These website files (already created for you)

---

## Step 1 — Create a GitHub account (if you do not have one)

1. Open [https://github.com/signup](https://github.com/signup)
2. Enter email, password, username
3. Verify your email

---

## Step 2 — Create a new repository (like a folder online)

1. After login, click the **+** (top right) → **New repository**
2. Repository name: `sada-vedic-apps`  
   (short, no spaces — this becomes part of your website address)
3. Description (optional): `Sada Vedic Apps website`
4. Choose **Public** (needed for free GitHub Pages on a normal account)
5. **Do not** check “Add a README” (we will upload files ourselves)
6. Click **Create repository**

---

## Step 3 — Upload the website files

1. On the new empty repo page, click **uploading an existing file**
2. On your computer, open the project folder:  
   `SAS/website`
3. Drag **all** of these into the browser upload area:
   - `index.html`
   - `support.html`
   - `privacy.html`
   - `styles.css`
   - `assets` folder (with images inside)
   - `apps` folder (with the two app pages inside)
4. Scroll down, commit message: `Add Sada Vedic Apps website`
5. Click **Commit changes**

Important: keep the same folder names. Do not put `index.html` inside another extra folder.

---

## Step 4 — Turn on GitHub Pages (publish the site)

1. In your repo, click **Settings**
2. Left sidebar → **Pages**
3. Under **Build and deployment** → **Source**, choose **Deploy from a branch**
4. Branch: **main** (or **master**)
5. Folder: **/ (root)**
6. Click **Save**

Wait 1–2 minutes. Refresh the Pages settings page.
GitHub will show a link like:

`https://YOUR_USERNAME.github.io/sada-vedic-apps/`

That is your live website home page.

---

## Step 5 — Check every important page

Open these in your browser:

- Home: `.../sada-vedic-apps/`
- Donate: `.../sada-vedic-apps/donate.html`
- Support (App Store Support URL): `.../sada-vedic-apps/support.html`
- Privacy (App Store Privacy Policy URL): `.../sada-vedic-apps/privacy.html`
- Sandhyavandanam: `.../sada-vedic-apps/apps/sadarogya-sandhyavandanam.html`
- Vedic Seva: `.../sada-vedic-apps/apps/vedic-seva.html`

If a page is blank or 404, wait another minute, then hard-refresh (`Cmd+Shift+R` on Mac).

---

## Step 6 — Use the links in App Store Connect

In App Store Connect → your app → App Information (or Privacy):

- **Support URL** → your `support.html` link
- **Privacy Policy URL** → your `privacy.html` link

Use the **same** Support and Privacy URLs for Sadarogya Sandhyavandanam and Vedic Seva (one website for all apps).

---

## How to update the site later

1. Open the repo on GitHub
2. Click the file → pencil icon → edit → Commit
3. Or upload a replacement file with the same name

The live site usually updates within a minute or two.

---

## Optional: custom domain later

You can add a domain like `sadavedicapps.com` later in **Settings → Pages → Custom domain**.
Not required for App Store review.

---

## If something goes wrong

| Problem | Fix |
| --- | --- |
| Pages shows 404 | Wait 2 minutes; confirm `index.html` is in the repo root, not inside a subfolder |
| CSS looks broken | Confirm `styles.css` and `assets/` were uploaded |
| Wrong username in URL | Use the username shown on your GitHub profile |
| Private repo | Make the repo **Public**, or use a GitHub Pro plan for private Pages |

Need help while uploading? Tell me your GitHub username after the repo is created, and I can check the live URLs with you.
