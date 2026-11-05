# Family Organizer: health records pages

Public pages for the Family Organizer app's registration with Epic (MyChart): documentation (`index.html`), privacy and
data use (`privacy.html`), terms (`terms.html`), and the server's public key set for SMART client authentication
(a public key, safe to publish): `jwks.json` for production and `jwks-sandbox.json` for non-production (Epic wants two
addresses; both hold the same key, since one server signs for both). Served by GitHub Pages. No health data lives here.
