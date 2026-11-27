ICAR AGRICULTURE MASTER CHECKLIST — DEPLOYMENT

This is a static, installable Progressive Web App (PWA). It is designed for phone and tablet use and stores progress locally on each device. After the first successful load while online, the app shell is cached for offline use.

FILES
- index.html: complete app and integrated Agriculture syllabus data
- manifest.webmanifest: install metadata
- sw.js: offline cache service worker
- icon.svg: app icon

GITHUB PAGES DEPLOYMENT
1. Create a new public GitHub repository (e.g. icar-agriculture-master-checklist).
2. Upload these four files to the repository root (not inside another folder).
3. Open repository Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for the Pages deployment and open the published https://USERNAME.github.io/REPOSITORY/ URL.
7. Open once while online, then use Chrome menu ⋮ → Install app / Add to Home screen.

OFFLINE
The service worker caches the app shell after first online visit. Progress is stored in browser localStorage on each device. Offline progress does not automatically sync between friends/devices. Use Backup/Restore to transfer progress.

SYLLABUS TRACEABILITY
The app retains the 239 existing source topic records, organized into 21 academic subjects. Each topic retains its Mains unit reference and mapped Prelims General Agriculture section references. The 31-item Prelims cross-reference register and seven source paragraphs are included in the coverage audit.

IMPORTANT
This app is a study organizer, not a substitute for the official notification. The uploaded source pages shown in the conversation include Prelims Paper-I page 4 and Mains Paper-II pages 6–8. Confirm any additional official Agriculture pages against the complete 35-page notification before claiming external-source completeness.
