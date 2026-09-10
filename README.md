# ILY4S.SBIH4N Systems — Windows 2000 Portal

Static mirror of Apache portal at `http://localhost:8083` (Windows 2000 + Matrix hacked desktop, DedSec loop, ILY4S.SBIH4N Systems banner).

* Original: Apache 2.4.58 on 8083, PHP 8.3, `/var/www/html/files`
* This static version: pure HTML/CSS/JS, no PHP — file list baked in at build time.

## Files
Small files are hosted directly (`hello.pdf`, `readme.txt`, `test.zip`, `lutris...deb`). 
Large ISO `tiny10 23h1 x64.iso` (3.7G) exceeds GitHub 100MB limit — hosted externally via Apache tunnel/public IP. Link in page points to `files/tiny10...iso` — replace with external URL if needed.

To update file list: re-run `curl http://localhost:8083/ > index.html` and copy new files to `files/`.

Hosted via GitHub Pages.
