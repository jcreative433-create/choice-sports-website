# Choice Sports: frontend preview (demo data)
Plain HTML/CSS/JS. No backend, no build, no keys. Everything shown is DEMO data.
## Deploy on Vercel
1. Extract the ZIP and upload its contents (index.html at the repo root) to a GitHub repo.
2. vercel.com > Add New > Project > import the repo. Framework: Other. No build command. Output directory: `.` (default). Deploy.
3. Commercial business use needs a paid Vercel plan (Hobby is non-commercial); Cloudflare Pages or Netlify are alternatives (check their terms).
Navigation uses `#/` links, so refreshing any page works and no rewrite config is needed.
## Edit later
- js/config.js: contact details and the 5 social links (address, phone, email, hours, Maps are pending). Set `number` for pre-filled WhatsApp messages.
- js/products.js: real products and prices. Photos go in /images; list filenames in `images`.
- The logo is text in index.html (`.logo`); swap for an image when supplied.
## Not included in this preview
Checkout is a simulation: no orders, payments, COD, database, login, admin or analytics. robots.txt and a noindex tag block search engines; remove both when going live.
