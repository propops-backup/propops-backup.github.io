# Property Operations Backup OAuth information site

Local-only static site prepared for a future Google OAuth production application. It has not been published or connected to Google Cloud.

## Files

- `index.html`: public application homepage
- `privacy/index.html`: privacy policy
- `terms/index.html`: terms of service
- `styles.css`: shared responsive styling

## Required before publication

1. Confirm the privacy-policy statements against the final production configuration.
2. Decide the GitHub Pages account and final `https://<username>.github.io/` URL.
3. Review the effective date on both policy pages.
4. Obtain explicit authorization before creating a repository, enabling Pages, or changing Google Cloud.

## Local preview

From this directory, serve the files with any local static HTTP server. For example:

```powershell
python -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Google Search Console verification later

After the final Pages URL exists:

1. Add its root URL, including `https://` and the trailing slash, as a URL-prefix property in Search Console.
2. Select the HTML-file verification method.
3. Download Google's verification file without changing its name or contents.
4. Place it beside `index.html` at this site's root.
5. Publish the site and confirm the file is publicly reachable at the exact URL Search Console specifies.
6. Click **Verify** in Search Console and keep the verification file published.

Do not add a verification file until Google generates it for the final site and account.

## Requirement mapping

| Google requirement | Site coverage |
| --- | --- |
| Publicly accessible application homepage | `index.html` |
| Clear description of application functionality | Homepage hero and “How it works” section |
| Visible privacy-policy link | Header and homepage policy section |
| Privacy policy on the same host | `privacy/index.html` |
| Disclosure of Google data access and use | Privacy sections “Google data accessed” and “How Google data is used” |
| Disclosure of storage, sharing, retention, and security | Corresponding privacy sections |
| Terms link, if provided | Header, homepage, and `terms/index.html` |
| Public support contact | `propops.backup@gmail.com` on all three pages |
