# AI Quick Search public website

A static HTML/CSS homepage, privacy policy and support section. Publisher: Maximiliano Monategui. Support/privacy contact: maximilianoamunategui@gmail.com. Policy effective date: November 2, 2026, confirmed by the owner.

Expected homepage: https://imilianomax.github.io/ai-quick-search-site/
Privacy policy: https://imilianomax.github.io/ai-quick-search-site/privacy.html
Support: https://imilianomax.github.io/ai-quick-search-site/#support

These URLs are only live after GitHub Pages deployment has completed and been verified.

## Files

- `index.html`: homepage and support/contact section.
- `privacy.html`: complete reviewed privacy disclosures and Limited Use commitment.
- `styles.css`: responsive, accessible system-font styling.
- `assets/glint.svg`: existing AI Quick Search Glint logo.
- `.nojekyll`: serve the files directly without Jekyll processing.

No JavaScript, build tools, package installation, analytics, tracking, site-set cookies, external fonts or third-party embedded resources are needed. External links are normal navigation links. GitHub hosting and user-initiated email are governed by those services' own practices.

## GitHub Pages deployment

1. Use this separate **public** repository, `imilianomax/ai-quick-search-site`. Keep the extension repository private; do not copy its source code, tests, history or private files here.
2. Commit these files to the `main` branch, with `index.html` at the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then **Save**.
6. Wait for the Pages deployment to finish. Keep **Enforce HTTPS** enabled.
7. Open the homepage, `privacy.html` and support link in a signed-out/private browser. They must return the intended pages without GitHub authentication.

No custom domain, Actions workflow, npm project or build step is required. GitHub may manage its own Pages build/deployment job for the branch source.

## Updating the policy

Edit `privacy.html` directly; keep the title, publisher/contact/effective-date metadata and policy content consistent. Preserve disclosures about prompt handoff, third parties, Chrome sync/local/session storage, temporary retention limits, URL/history/clipboard records, optional permissions and Limited Use. The source was the publisher's reviewed extension-policy draft. Only draft bookkeeping/owner TODOs were removed and the supplied owner details were completed; data-handling disclosures were preserved. The website-hosting section is separate.

Before pushing a new policy, confirm there are no unfinished placeholders and check links, keyboard navigation, mobile layout and the production HTTPS response. A repository commit alone does not establish that Pages deployment succeeded.
