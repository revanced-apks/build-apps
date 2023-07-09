YouTube-Extended: 18.25.40  
YouTube: 18.23.35  
Music-Extended (arm-v7a): 6.08.50  
Music (arm-v7a): 6.08.50  
Music (arm64-v8a): 6.08.50  
Music-Extended (arm64-v8a): 6.08.50  
Twitter: 9.96.0-release.0  
Twitch: 15.4.1  
TikTok: 30.3.4  
Reddit: 2023.26.0  
Spotify: 8.8.50.466  
Spotify-Lite: 1.9.0.31697  
Backdrops: 4.52  
MyExpenses: 3.4.9  
NyxMusicPlayer: 2.2.7  
IconPackStudio: 2.1 build 028  
TickTick: 6.6.5.0  
Tasker: 6.1.33  
Instagram-arm64: 275.0.0.27.98  
Instagram-arm: 275.0.0.27.98  
Facebook-Messenger-arm64: 416.0.0.9.76  
Facebook-Messenger-arm: 416.0.0.9.76  
InShorts-arm64: 5.5.6  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-2.22.0-all.jar  
Integrations: inotia00/revanced-integrations-0.112.1.apk  
Patches: inotia00/revanced-patches-2.182.1.jar  

YouTube
==
- feat(youtube): add `enable-new-comment-popup-panels` patch [Screenshot](https://imgur.com/a/RSNOBlr)
- feat(youtube/hide-button-container): removed settings marked as `Experimental Flags` (these settings no longer fixable in latest YouTube)
- feat(youtube/hide-description-component): add `Hide game sections`, `Hide info cards sections` settings https://github.com/inotia00/ReVanced_Extended/issues/1069
- feat(youtube/hide-layout-components): add `Hide browse store button` settings
- fix(youtube/custom-video-speed): videos always play at 2.0x speed, even if the default video speed is faster than 2.0x
- fix(youtube/default-video-speed): can't play video from PlayStore
- fix(youtube/player-type-hook): `shared-resource-id` patch is missing from dependencies https://github.com/inotia00/ReVanced_Extended/issues/1091 https://github.com/inotia00/ReVanced_Extended/issues/1102 
- fix(youtube/settings): unable to import .json files on Android 9 device https://github.com/inotia00/ReVanced_Extended/issues/1056
- fix(youtube/spoof-player-parameter): update settings text for known side effects https://github.com/inotia00/ReVanced_Extended/issues/1045
- feat(youtube/translations): update translation
`Arabic`, `Brazilian`, `Bulgarian`, `Greek`, `Japanese`, `Korean`, `Russian`, `Spanish`, `Ukrainian`


Reddit
==
- feat(reddit): remove `hide-chat-button` patch


Etc
==
- add support YouTube v18.25.40


※ Compatible ReVanced Manager: [RVX Manager v1.3.8 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.3.8)
[Crowdin translation]
- [European Countries](https://crowdin.com/project/revancedextendedeu)
- [Other Countries](https://crowdin.com/project/revancedextended)
---
CLI: j-hc/revanced-cli-2.22.0-all.jar  
Integrations: revanced/revanced-integrations-0.112.0.apk  
Patches: revanced/revanced-patches-2.182.0.jar  

### [2.182.0](https://github.com/revanced/revanced-patches/compare/v2.181.0...v2.182.0) (2023-07-08)


### Bug Fixes

* **youtube/hide-layout-components:**  hide mix playlists ([33a87bd](https://github.com/revanced/revanced-patches/commit/33a87bd6eac1639687ebdf96ef8924cd674f81e4))


### Features

* **pixiv:** add `hide-ads` patch ([#2578](https://github.com/revanced/revanced-patches/issues/2578)) ([862a7ec](https://github.com/revanced/revanced-patches/commit/862a7ec5b0767c28e79454a44218069d3e9cbac7))
* remove unnecessary notice ([7e9f0b2](https://github.com/revanced/revanced-patches/commit/7e9f0b2d02e910984f08777fefcd2ad7df6a21ee))
* **slideforreddit:** add `change-oauth-client-id` patch ([#2571](https://github.com/revanced/revanced-patches/issues/2571)) ([8cd60ee](https://github.com/revanced/revanced-patches/commit/8cd60eea36bd49514ed1c42bf362dce7e9675fca))
* **youtube:** support versions `18.20.39` and `18.23.35` ([#2461](https://github.com/revanced/revanced-patches/issues/2461)) ([d20fde1](https://github.com/revanced/revanced-patches/commit/d20fde1e57077fe9a943f9782b415d7a0249b083))




---  
