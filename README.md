# Google Play app downloader [h4ng3r]
This is a cli friendly version of the MCMrARM's Google Play app downloader https://github.com/MCMrARM/google_play_downloader

## Usage:
``` sh
java -jar gplaydl.jar <email> <password> <lang> <android_id> <pkg> [output_path]
```
## Download:
You can download the cli compiled version here:
https://github.com/h4ng3r/google_play_downloader/blob/gh-pages/gplaydl.jar

# Google Play app downloader [MCMrARM]
This java app allows you to download Google Play applications, allowing you to select if you want to download the x86 or arm variant of the app. It is hugely based on https://github.com/Akdeniz/google-play-crawler, and support for downloading paid apps is based on https://github.com/Akdeniz/google-play-crawler/pull/52. Huge thanks to those people!

Licensed under the FreeBSD license.

## Usage:
After starting the app, you'll be asked to enter your Google email and password. Remember that if you are trying to download a paid app, you have to purchase it on that account before trying to download it with this app. You'll be also asked for a preferred language. If android_id.txt doesn't exist, the app will ask you to specify if you would like to download x86 version of apps and generate a android id. Then you'll be asked for the package name of the app you want to download, and if everything is fine, it'll be download to the working directory.

## Download:
You can download compiled version here:
https://mcmrarm.github.io/google_play_downloader/playdl.jar
