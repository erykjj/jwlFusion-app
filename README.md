<img src="res/jwlFusion.png" width=100> βητα

This is an **Android app** to merge backups created by the *JW Library* app[^1] created on different devices.

For Android 10+ arm64-v8a devices only.

By using this software you agree to abide by the terms of its [License](https://github.com/erykjj/jwlFusion#License-1-ov-file).

## Downloads

**Coming soon**

## Usage

1. Set a backup folder (once). This *can* be in the Internal Storage of the device or on an SD Card, but unless you then synchronize the contents of that folder (using something like *Syncthing*), you will have to manually copy backups from the other device(s) to this folder. So, pick a folder/location on *Google Drive* (or other such cloud storage) where you also save backups from other devices.
2. When you **Create Backup** (*Personal Study* section of *JW Library*), select *jwlFusion* as the destination. The app serves as a bridge between *JW Library* and your backup folder.
3. *jwlFusion* will save your backup as is in the folder you selected (as would *JW Library*) and it looks for the most recent backup from *another* device (this is where synchronized cloud storage comes in handy). If a backup from another device is found, a merge will be performed; it can take a few seconds, depending on the size of the archives. Once merged, the merged backup will be saved with a *jwlFusion_* prefix in your backup folder and will be synchronized (by your cloud storage app) to your other device(s), where you can import it (**Restore Backup**).
4. If no backups from other devices exist, nothing is merged and you're done.

____
[![Static Badge](https://img.shields.io/badge/releases-orange?style=plastic&logo=rss&logoColor=orange&color=black)](https://github.com/erykjj/jwlFusion-app/releases.atom)

Feel free to get in touch and post any [issues and/or suggestions](https://github.com/erykjj/jwlFusion-app/issues).

My other *JW Library* projects: [**JWLManager**](https://github.com/erykjj/jwlmanager) & [**jwlFusion** (desktop)](https://github.com/erykjj/jwlFusion)
____
#### Footnotes:
[^1]: [JW Library](https://www.jw.org/en/online-help/jw-library/) is a registered trademark of *Watch Tower Bible and Tract Society of Pennsylvania*
