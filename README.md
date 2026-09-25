# David Morgensztern — NFC contact page

## Publish free with GitHub Pages

1. Sign in to GitHub as `Dmorgs81` and create a **public** repository named `contact`.
2. Upload `index.html`, `styles.css`, `script.js`, and the entire `assets` folder **without changing the folder structure**. You can drag and drop these files in **Add file → Upload files** (upload the assets folder too).
3. Go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
4. Wait for GitHub Pages to publish. Your expected URL is `https://dmorgs81.github.io/contact/` (verify it actually loads before programming the NFC card).
5. On your phone, install **NFC Tools**, choose **Write → Add a record → URL/URI**, paste your live URL, tap **Write**, and hold your NFC card against the phone. Test with another phone before considering any permanent tag lock.

## Customize

- `assets/profile.png`: your portrait.
- `assets/mizzou-engineering.png`: the supplied Mizzou Engineering graphic.
- `styles.css`: colors, spacing, animations, layout.
- `script.js`: contact data and downloadable vCard.
- `index.html`: all page text and links.

## Notes

The Save Contact button generates a `.vcf` file in the visitor's browser. On some phones the visitor may need to open the downloaded file to import the contact. The Share Card button uses the native share sheet where supported, or copies the URL over HTTPS.

This is a static site; no server, tracking, or paid hosting required. Because it contains your personal phone number and email, publishing the repository publicly also publishes that information.
