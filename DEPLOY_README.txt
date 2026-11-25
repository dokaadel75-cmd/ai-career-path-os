AI CAREER PATH OS — PWA UPDATE

Files to upload to GitHub repository root:
- index.html (updated dashboard with prioritized credentials)
- manifest.webmanifest (PWA metadata)
- sw.js (offline app shell cache)
- icon-192.png
- icon-512.png

GitHub upload steps:
1. Open https://github.com/dokaadel75-cmd/ai-career-path-os
2. Add file > Upload files
3. Drag/select all five files
4. Commit changes to main
5. Wait for GitHub Pages build/deploy

Then open: https://dokaadel75-cmd.github.io/ai-career-path-os/

Install on Android/Chrome: browser menu > Install app (or Add to Home Screen).
Install on iPhone Safari: Share > Add to Home Screen.
On desktop Chrome/Edge: install icon in address bar/menu when available.

Current progress is stored locally in each browser/device (localStorage). This release is installable and has an offline cached shell, but it does not yet synchronize progress across devices. Cloud sync/authentication will be a separate next phase.
