# XV Tools website v1.6.0 — deployment preparation

Publisher: Revi XV (individual; name supplied by publisher, portal verification not checked).
GitHub destination requested: yerin-glitch.
Support: tarastanhey@gmail.com.
Plugin: free; intended global availability. Public directory review is still pending.

## Before making the site public
- Read terms.html and confirm the proposed terms accurately reflect your intended terms. Once you approve them, remove the draft notice and change the page title/description to remove draft wording. No legal or OpenAI attestations are implied by this package.
- Confirm third-party distribution rights and retain attribution and licenses. The privacy text reflects the support-data practices you approved.
- robots.txt currently requests no indexing while the site is in preparation; change `Disallow: /` to `Disallow:` or remove robots.txt if you want indexing once published. This file is not a privacy control.

## GitHub Pages setup
1. Sign in to GitHub as yerin-glitch. Create a new public repository named xv-tools, or use an empty repository you control with an appropriate name.
2. Extract this ZIP and upload its CONTENTS (not the ZIP) to the root of main. Preserve assets/, LICENSES/, catalog/, and .nojekyll.
3. Open Settings > Pages. Under Build and deployment choose Deploy from a branch, main, / (root), then Save.
4. Once GitHub displays the published HTTPS address, open it while signed out. Also open support.html, privacy.html and terms.html and verify the publisher, contact and policy content.
5. Provide the actual working website address for verification and insertion of the four listing URLs into the existing plugin manifest. Do not use guessed addresses.

The expected address if the repository name and owner are exactly as above is https://yerin-glitch.github.io/xv-tools/ (not verified or live at packaging time).

This static website has no bundled plugin source, analytics scripts, database, contact form, login, or backend. The plugin ZIP is separate. The public website is not equivalent to public plugin approval or availability.
