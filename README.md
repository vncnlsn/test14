# APS Land Services V2 | Operator-first Rebuild

An original static, responsive, staging-only website concept, informed by the APS final Copy Master and research. Navy / cream / terracotta palette. This is NOT a reproduction of Claude's code, which was not provided.

## Test on GitHub Pages
1. Create a separate test repository, such as `aps-v2-test`.
2. Upload the CONTENTS of this folder to the repository root.
3. Settings > Pages > Deploy from branch > main > /(root).
4. Visit `https://USERNAME.github.io/aps-v2-test/`.

All asset and navigation links use relative paths, including nested routes. No build system, dependencies, backend, fonts, tracking, or remote assets.

## Included
11 routes: home, services hub, four individual services, about, safety, landowners, contact, and staging-only privacy. Custom SVG contour and corridor graphics are explicitly illustrative, not real project data.

## Before production
- Replace the temporary APS typographic wordmark with the actual approved logo.
- Add APS-approved privacy policy text. The current privacy route is only a staging placeholder.
- Review the V2 compressed copy against the final Copy Master. The master remains the factual source; V2 intentionally shortens and reorganizes visitor text and therefore requires editorial approval.
- Replace the illustrative geographic graphic with the existing verified APS SVG map if desired; do not infer which 28 states were served.
- Add real, authorized leadership portraits if available.
- Remove `noindex,nofollow` from production routes only after approval; configure canonical URLs, sitemap.xml, robots.txt, OG metadata and structured data for apsland.com.
- Preserve legacy /services fragments, test redirects and legacy domains, run Lighthouse, axe, keyboard, mobile and cross-browser QA.
- Check title-opinion wording before adding any claims. No unapproved client logos, case studies, credentials, or certifications.

## Intentional choices
No contact form, no analytics, no auto-play, no heavy animation, no fake project claims. Short homepage and deeper service pages for fast buyer evaluation.
