EXPLORAR EVORA — ATELIER EDITION
Eren Ozturk — 77222 — ex77222@alunos.uevora.pt
INF13207L, Tecnologias Web, Universidade de Evora, 2026/2027

OPEN
Extract the ZIP, then double-click index.html. The website needs no installation,
framework, build tools or application server. Stay online for university events,
OpenStreetMap and optional Google Fonts. Fonts have local system fallbacks.

FILES
LIVE-DEMO.txt: public project, source, report and related study-resource links.
index.html: semantic page, forms, navigation and dialogs.
styles.css: responsive design, motion and light/dark themes.
app.js: university API integration and simulated roles.
evora-temple.jpg / CREDITS.txt: photograph and attribution.
relatorio.pdf: two-page Portuguese critical report, version 1.3.
verify.cjs: 13 optional focused checks; run `node verify.cjs` if Node is available.
Node is NOT needed to open or use the website.

TRY
Browse the next four events. Open Agenda completa and change pages. Search names
or dates; filter the displayed results locally. Open details, coordinates,
comments and maps. Try the simulated visitor, agent and administrator profiles.
Check mobile navigation, keyboard dialogs and the theme switch.

VERIFICATION AND LIMITS
Real server reads, POST pagination and search were verified on 16 November 2026.
Browser checks confirmed events, catalogue, details, map and administrator view.
The 13 focused checks cover escaping, dates, GPS, response errors, event codes
and ownership checks, including regression cases for the verified write contracts.
Later improvements include keyboard focus handling, safer ownership checks,
loading resilience, system theme preference, bounded parallax and reduced motion.

Live write verification completed on 16 November 2026 using one temporary test
event and comment. Creation returned event_id and registration_code. Editing uses
POST /events/{id}; PUT is rejected by this server. Comment deletion requires
event_id and comment_id; event deletion uses id. All successful operations were
read back. The test comment was removed and the deleted event returned 404.
Frontend request contracts and focused regression checks were corrected.
Authentication and roles remain client-side demonstrations as the brief requires.

SUBMISSION
Package: Eren-Ozturk-77222-Explorar-Evora-T1.zip.
Internal folder: tweb-t1-77222. The package includes source, photo credits,
two-page report, optional checks and the public demo links in LIVE-DEMO.txt.
Upload the package to Moodle assignment 30849 and retain the submission receipt.
The public website does not itself constitute a Moodle submission.

Sources:
https://www.moodle.uevora.pt/2627/mod/resource/view.php?id=30848
https://www.moodle.uevora.pt/2627/mod/assign/view.php?id=30849
https://magno.di.uevora.pt/tweb/t1

See CREDITS.txt for photo attribution. Existing custom project source was used;
no third-party portfolio template was cloned into this project.
