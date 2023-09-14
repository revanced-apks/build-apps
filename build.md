YouTube: 18.32.39  
Music-Extended (arm64-v8a): 6.19.51  
Music-Extended (arm-v7a): 6.19.51  
YouTube-Extended: 18.31.40  
Music (arm64-v8a): 6.19.51  
Music (arm-v7a): 6.19.51  
Twitter: 10.7.0-release.0  
Twitch: 15.4.1  
TikTok: 31.2.5  
Reddit: 2023.36.0  
Spotify: 8.8.68.565  
Spotify-Lite: 1.9.0.45033  
Backdrops: 4.52  
NyxMusicPlayer: 2.2.7  
IconPackStudio: 2.2 build 012  
TickTick (arm64-v8a): 6.7.0.2  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: inotia00/revanced-integrations-0.117.4.apk  
Patches: inotia00/revanced-patches-2.190.4.jar  

YouTube
==
- fix(youtube/bypass-ambient-mode-restrictions): update fingerprint
- fix(youtube/default-video-quality): default video quality is not applied at cold start
- fix(youtube/hide-suggestions-shelf): not working on tablets https://github.com/inotia00/ReVanced_Extended/issues/1337
- fix(youtube/sponsorblock): change invalid patch name
- fix(youtube/sponsorblock): fetch to latest source
- fix(youtube/spoof-player-parameters): spoofing also applies to shorts videos
- fix(youtube/settings): remove unused string resources
- feat(youtube/translations): update translation
`Korean`, `Vietnamese`


YouTube Music
==
- feat(music): add `replace-dismiss-queue` patch
- feat(music): add `sponsorblock` patch https://github.com/inotia00/ReVanced_Extended/issues/97
- feat(music): add support version `v6.19.51`
- feat(music/hide-flyout-panel): code refactoring
- fix(music/enable-new-layout): change patch description
- fix(music/hook-download-button): change the default external downloader package name https://github.com/inotia00/ReVanced_Extended/issues/1340
- fix(music/hook-download-button): download button not hooked in certain situations
- fix(music/spoof-app-version): add missing dependencies
- refactor(music/settings): integrate the preferences of the `return-youtube-dislike` setting into the existing settings
- feat(music/translations): update translation
`Brazilian`, `Dutch`, `French`, `Japanese`, `Korean`, `Polish`, `Russia`, `Spanish`, `Turkish`, `Vietnamese`


Etc
==
- build: update dependency


※ Compatible ReVanced Manager: [RVX Manager v1.9.7 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.9.7)
---
CLI: j-hc/revanced-cli-3.2.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.117.1.apk  
Patches: ReVanced/revanced-patches-2.190.0.jar  

### [2.190.0](https://github.com/ReVanced/revanced-patches/compare/v2.189.0...v2.190.0) (2023-09-03)
### Bug Fixes
* **Infinity for Reddit - Spoof client:** Support latest version ([8a5311b](https://github.com/ReVanced/revanced-patches/commit/8a5311b1e645ca2aab1e416d647cf52bf0be6e7f))
### Features
* **Photomath:** Support latest version ([5a2cad0](https://github.com/ReVanced/revanced-patches/commit/5a2cad077f03880ee1417c5cfd448bbdea4c07e2))
* **Twitch:** Support version `16.1.0` ([#2923](https://github.com/ReVanced/revanced-patches/issues/2923)) ([d9834a9](https://github.com/ReVanced/revanced-patches/commit/d9834a9abb43390af4cb33f5dd5a0e2d3b7060e2))

---  
