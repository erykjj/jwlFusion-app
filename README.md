# <img src="docs/res/jwlFusion.png" width=35> jwlFusion App

This is an **Android app**[^1] to merge backups created by *JW Library*[^2]. It works **off-line**: your data is not sent to anyone's website or a chatbot.

It merges:
- Annotations (comment fields)
- Bookmarks
- Highlights
- Notes (and tags)
- Favorites (up to limit of 10)
- Playlists (and media files)

<details>
<summary>Preview…</summary>
<br/>
![preview](docs/res/jwlFusion.gif)
<br/>
</details>
<br/>
**Latest release**: [jwlFusion_v1.0.1.apk](https://github.com/erykjj/jwlFusion-app/releases/download/v1.0.1/jwlFusion_v1.0.1.apk)

Pick the two backup archives you wish to merge. The **Primary** one will take precedence in case of any conflicts; it will add to the **Secondary** one and over-write any duplicate records.

The merge itself can take a few seconds, depending on the size of the archives and the capacity of your device.

The merged backup will need to be "saved" (via *Share to…*) with a *jwlFusion_* prefix. You can send it to your cloud storage app (like *Google Drive*) to synchronize to your other device(s), where you can import it into *JW Library* ("Restore Backup").

____
[![Static Badge](https://img.shields.io/badge/releases-orange?style=plastic&logo=rss&logoColor=orange&color=black)](https://github.com/erykjj/jwlFusion-app/releases.atom)

By using this software you agree to abide by the terms of its [License](https://github.com/erykjj/jwlFusion-app#License-1-ov-file).

Feel free to get in touch and post any [issues and/or suggestions](https://github.com/erykjj/jwlFusion-app/issues).

My other *JW Library* projects: [**JWLManager**](https://github.com/erykjj/jwlmanager) & [**jwlFusion** (desktop)](https://github.com/erykjj/jwlFusion)

____
#### Footnotes:
[^1]: Android 10+, arm64-v8a & x86_64; for armeabi-v7a devices, try [v0.11.0](https://github.com/erykjj/jwlFusion-app/releases/download/v0.11.0/jwlFusion_v0.11.0.apk) 

[^2]: [JW Library](https://www.jw.org/en/online-help/jw-library/) is a registered trademark of *Watch Tower Bible and Tract Society of Pennsylvania*
