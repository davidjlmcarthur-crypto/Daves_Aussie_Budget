Dave's Aussie Budget — Android offline PWA

1. Export a JSON backup from the existing deployed app BEFORE switching.
2. On GitHub, create a repository (e.g. Daves-Aussie-Budget). Upload ALL files from this ZIP to the repository root (not the ZIP itself).
3. Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save.
4. Open the published HTTPS GitHub Pages URL on Android in Chrome while online. Wait for the page to finish loading.
5. Chrome menu > Add to Home screen > Install app (wording varies).
6. Open installed app and restore the JSON backup. Test offline by enabling airplane mode and reopening.

The app stores financial data in localStorage on this device, not on GitHub. Backup regularly; uninstalling/clearing site data can delete records. No automatic cross-device sync.

Note: Offline use requires one successful online load after deployment; new deployments may require reopening online to fetch updates.
