# WeAreExeter site

Support page and privacy policy for the WeAreExeter app, served by GitHub Pages.

- `index.html` — support page (App Store "Support URL")
- `privacy.html` — privacy policy (both stores' "Privacy Policy URL")

The contact email appears in both pages inside `<span data-fill="contact-email">`.
Edit those two spans, commit, and push; Pages redeploys in a minute or two.

If the app's data handling changes — analytics, accounts, location, push tokens —
update `privacy.html` and its effective date before shipping that build, and update
the App Store privacy label and Play data safety form to match.
