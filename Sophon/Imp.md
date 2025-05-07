# Sophon Implementation

## What is Sophon?

Sophon is a new download method introduced by HoYoverse and was firstly introduced widely to the public on the release of their new Unified launcher, HoYoPlay.

Sophon allows files to be downloaded into several chunks, which result more efficient, faster and less error-prone download process compared to conventional archive file download method. This also allows the download process requiring much less disk space since the files will be written into disk on-the-fly without reserving double the size of disk space.

Sophon has 2 download modes, one of them might also be deprecate soon.

- Copy-Over

- Copy and Patch-Over

For implementation, Windows Development can use [Hi3Helper.Sophon](https://github.com/CollapseLauncher/Hi3Helper.Sophon)

For certain platforms, you can try to follow the code examples in the repository linked above to figure how to implement in other lanuages.

This [Documentation](https://github.com/Scighost/Starward/issues/725) is also useful for implementing Sophon.

You can also find it [here](https://blog.amarea.cn/archives/genshin-launcher-chunk-download-mode.html)

Endpoints: 

Global: https://sg-public-api.hoyoverse.com/downloader/sophon_chunk/api/getBuild

China: https://api-takumi.mihoyo.com/downloader/sophon_chunk/api/getBuild

To get the data, the following paramaters is required:

- package_id

- branch=[main/predownload]

- password

These data can be found in section [Game Branches & Sophon] of the corresponding launcher client.