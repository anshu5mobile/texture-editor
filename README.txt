AV Studios: Texture Pack Editor - APK guide

1) HOST THE FOLDER (free, needs https)
   - GitHub Pages: make a repo, upload all files in this folder to it, Settings > Pages > deploy from main branch.
   - or Netlify / Cloudflare Pages: upload this folder.
   You get a link like https://yourname.github.io/texture-editor/

2) OPEN pwabuilder.com on your phone, paste the link, tap Start.
   It should show a manifest, service worker and icons as passing.
   Tap "Package for stores" > Android > Generate. Download the zip, it contains the APK.

3) PERMISSIONS
   The app needs none. Opening images uses Android's own file picker, and saving uses a normal download.
   Do not add storage permissions in PWABuilder: they are not needed and can cause rejections.
   When PWABuilder asks for notifications / location, leave them off.

4) SIGNING
   Installing on your own phone works with the debug/test APK. A Play Store upload needs the signing key PWABuilder gives you.

Contact / bugs / feature requests: https://discord.gg/MJVwemmaTf
Made by AV Studios and ItsAnshuXD
