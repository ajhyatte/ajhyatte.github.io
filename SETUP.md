# Putting your site online — step by step

Free hosting with GitHub Pages. No coding tools needed; everything happens in your browser.
Your site will live at **https://YOUR-USERNAME.github.io**.

## 1. Get the files
Download `site.zip` and unzip it. You should see a folder with:
`index.html  blog.html  cv.html  reading.html  style.css  cv.pdf  README.md  SETUP.md`

## 2. Make a GitHub account
Go to **github.com** → **Sign up**. Pick your username carefully — it becomes your web address
(e.g. username `ajhyatte` → `ajhyatte.github.io`).

## 3. Create the repository (the folder that holds your site)
1. Top-right **+** → **New repository**.
2. **Repository name:** type exactly `YOUR-USERNAME.github.io` (your username, then `.github.io`).
3. Set it to **Public**.
4. Click **Create repository**.

## 4. Upload the files
1. On the new repo page, click the link **"uploading an existing file"**.
2. Open your unzipped folder, select **all the files inside it** (not the folder itself), and drag them into the browser.
3. Scroll down, click **Commit changes**.

## 5. Turn on the website
1. In the repo, go to **Settings** → **Pages** (left sidebar).
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)** → **Save**.
4. Wait 1–2 minutes, refresh. A box appears: *"Your site is live at https://YOUR-USERNAME.github.io"*.

That's it — you're online.

---

## Editing later (all in the browser)
1. Go to your repo on github.com and click the file (e.g. `reading.html`).
2. Click the **pencil icon** (Edit) in the top-right of the file.
3. Make your change — each file has comments explaining how (look for `HOW TO`).
4. Click **Commit changes…** → **Commit changes**. The live site updates in about a minute.

### Common edits
- **Add a book:** in `reading.html`, copy an existing `<a class="item" …>…</a>` line, paste it under
  the right section, and change the link, title, tags and author.
  - To get a Goodreads link: find the book on goodreads.com and copy the address bar.
  - Tags: `<span class="tag nonfiction">Nonfiction</span>`, `<span class="tag fiction">Fiction</span>`,
    or any topic: `<span class="tag">Latin America</span>`.
- **Finished a book:** cut its line from *Currently reading* and paste it under *Read in 2026*.
- **New blog post:** in `blog.html`, copy a post line and paste in the Substack link, title and date.
  Also replace `YOURNAME.substack.com` on the Subscribe button with your Substack address.
- **Update the CV:** edit `cv.html`. To replace the downloadable PDF, upload a new file named
  exactly `cv.pdf` (Add file → Upload files) — it overwrites the old one.

## Optional: your own domain (e.g. ajhyatte.com)
1. Buy the domain (Namecheap, Porkbun, Cloudflare — about $10–15/year).
2. Repo **Settings → Pages → Custom domain**: type your domain → **Save**.
3. At your domain company, add the DNS records GitHub shows you
   (guide: docs.github.com → search "managing a custom domain for your GitHub Pages site").
4. Back in Settings → Pages, tick **Enforce HTTPS** once it's available.
