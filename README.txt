Ridgeline - how to put it online

Upload everything in this folder (index.html, sw.js, manifest.webmanifest and the icons folder) to any website host that uses https.

Easiest free options:
1. Netlify Drop: go to app.netlify.com/drop, sign in, and drag this whole folder onto the page. You get a link like https://something.netlify.app.
2. GitHub Pages: create a repository, upload these files, then in Settings > Pages choose "Deploy from a branch" and the main branch.
3. Cloudflare Pages: Workers & Pages > Create > Pages > Upload assets, then drag this folder.

Then open the link on any phone, tablet or computer.
- iPhone and iPad: open it in Safari, tap Share, then Add to Home Screen.
- Android: open it in Chrome, tap the menu, then Install app (or use Menu > Install Ridgeline inside the app).
- Computer: open it in Chrome, Edge, Safari or Firefox. Chrome and Edge can install it from the address bar.

Location (GPS) only works over https, so open the hosted link, not the file itself.

Memberships, feedback and first responder keys: see MEMBERSHIP-SETUP.txt.
Until you set a payment company there, paid plans show "Coming soon" and only Free features work.
To try everything first, set paywall:false at the top of index.html.
