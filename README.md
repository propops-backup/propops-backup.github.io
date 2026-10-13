# Property Operations Backup OAuth information site

Public information site for the private, owner-operated Property Operations Backup Google OAuth application.

Live site: https://propops-backup.github.io/

## Files

- `index.html`: application homepage
- `privacy/index.html`: privacy policy
- `terms/index.html`: terms of service
- `styles.css`: shared responsive styling

## Google Search Console verification

1. Add `https://propops-backup.github.io/` as a URL-prefix property in Search Console.
2. Select the HTML-file verification method.
3. Download Google's verification file without changing its name or contents.
4. Add it beside `index.html` at the repository root.
5. Confirm the file is publicly reachable at the exact URL Search Console specifies.
6. Click **Verify** and keep the verification file published.

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
