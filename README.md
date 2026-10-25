# JX Laboratories website (GitHub Pages - flat layout)

Public results:  https://YOURDOMAIN/test.html?id=139576

## Files (all in the root - no folders)
- index.html ........ home page
- portal.html ....... client portal (login demo)
- test.html ......... public results page (reads ?id= and loads <id>.json)
- 139576.json ....... one file per completed test (example)
- _TEMPLATE.json .... copy this to start a new result
- CNAME ............. your domain (edit to your real one)

## For each finished test
1. Copy _TEMPLATE.json to <TestID>.json  (e.g. 139576.json) - keep it in the root.
2. Fill product, client, dates, results. Commit.
3. Live at  /test.html?id=<TestID>
4. QR on the report encodes  https://YOURDOMAIN/test.html?id=<TestID>

## Setup
- Settings > Pages > Deploy from branch > main / root.
- Settings > Pages > Custom domain > your domain (keep CNAME in sync).
- Change VERIFY_BASE in test.html and portal.html to your real domain.
- Anything in a .json here is PUBLIC.
