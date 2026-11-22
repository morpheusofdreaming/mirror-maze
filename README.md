# Mirror Maze: Android build

The game is `www/index.html`. GitHub Actions wraps it with Capacitor and builds a debug APK.

## Get the APK (browser only, no Git needed)
1. Upload these files to the repository with the GitHub website (Add file > Upload files).
2. Open the repo's **Actions** tab and wait for the green tick (about 5-10 minutes).
3. Open **Releases** (right side of the repo page) > **Latest build** > download `MirrorMaze-debug.apk`.

## Update the game
Open `www/index.html` on GitHub, click the pencil/**...** menu > Delete or replace it by uploading the new file to the `www` folder (Add file > Upload files), then Commit. A new APK is built and replaces the one on the Latest build release.

## Install on the phone
Open the APK, allow "install unknown apps" if asked, install. If an older Mirror Maze is installed, uninstall it first.
