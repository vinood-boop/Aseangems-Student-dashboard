# ASEAN GEMS Student Dashboard

A static Edutourism student dashboard prototype. Open `index.html` in a browser; no build step is required.

The dashboard includes applications, bookmarks, profile information, university document requests, application history, post-approval records, and withdrawal actions. Application details use the Stage focus layout.

Sample applications cover New Application, Documents Required, Req. Document Submitted, Approved, and Withdrawn. Uploaded files remain drafts until submission is confirmed; submitted files are available for viewing and downloading.

Application changes and uploads are simulated in the browser. No university, KPT, or backend service is connected. Reloading restores the sample data.

The required CSS and JavaScript remain inside `index.html`. Bootstrap is retained for the existing dropdowns and mobile menus. Montserrat, the used icon fonts, and additional images are bundled in `assets/`; the original dashboard images remain alongside `index.html`.

The dashboard can run without external services. Profile edits and password changes are simulated locally. The header language panel supports English, and search filters the local sample applications and bookmarks.

The source before cleanup is preserved in `_archive/dashboard-before-cleanup/`. Browser verification reports and comparison screenshots are inside its `review/` folder. The archive and temporary verification scripts are excluded from Git while the cleanup is reviewed.
