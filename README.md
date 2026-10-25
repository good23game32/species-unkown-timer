# The Final Countdown — Space Edition

## Publish for free with GitHub Pages
1. Upload `index.html` and `space-background.jpg` to the root of your public repository.
2. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
3. Wait for GitHub Pages to publish the site.

## Share a countdown
Set the target date/time, song lead-in, and audio path, then click **Share countdown link**. The link encodes the exact target timestamp so friends in different time zones see the same instant.

## Shared music
To make the same song available to everyone, put an audio file called `countdown-song.mp3` in the repository root and keep the audio path set to that filename. Only upload audio you own or are licensed to distribute. You can alternatively enter a direct URL to an audio file you have permission to use.

Browsers generally require each visitor to interact with the page before sound can play. Ask everyone to open the link and click **Enable sound** well before the target. They must keep the page open and the device awake. Static GitHub Pages cannot make audio play if a browser/device is closed or asleep.

## Repository setup choices
- **License:** choose **None** unless you deliberately want to publish a license for reuse. If you add a license, it applies to your code; it does not give you rights to redistribute commercial music.
- **.gitignore:** not needed for this simple static site. You can leave it as **None**.
