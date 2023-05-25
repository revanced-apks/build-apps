CLI: revanced-cli-2.22.0-all.jar  
Integrations: revanced-integrations-0.108.0.apk  
Patches: revanced-patches-2.174.0.jar  

### [2.174.0](https://github.com/revanced/revanced-patches/compare/v2.173.0...v2.174.0) (2023-05-24)


### Bug Fixes

* **readme-generator:** attempt sorting versions with `FlexVer` ([#2059](https://github.com/revanced/revanced-patches/issues/2059)) ([a54c464](https://github.com/revanced/revanced-patches/commit/a54c464522fa2a6a2d2525c8cb0ec961c2cc771c))
* **spotify/disable-capture-restriction:** make compatible with latest versions ([#2095](https://github.com/revanced/revanced-patches/issues/2095)) ([e48f127](https://github.com/revanced/revanced-patches/commit/e48f1278da2a9d82e70be41fa2c4c480c574816b))
* **twitter:** correctly resolve to integrations methods ([c655416](https://github.com/revanced/revanced-patches/commit/c655416a91f0a32cfe82b1384f5958cace891833))
* **youtube/integrations:** allow playback of embedded videos  ([#2092](https://github.com/revanced/revanced-patches/issues/2092)) ([8a43d75](https://github.com/revanced/revanced-patches/commit/8a43d75e2db63c47bb9ad1b75027df0868c094e5))
* **youtube/remember-video-quality:** fix default video quality/speed being applied when resuming app. ([#2112](https://github.com/revanced/revanced-patches/issues/2112)) ([f68a41c](https://github.com/revanced/revanced-patches/commit/f68a41ce9f9a78818d3f28b069e70b8c66125f53))
* **youtube/return-youtube-dislikes:** fix temporarily frozen video after opening a shorts ([#2126](https://github.com/revanced/revanced-patches/issues/2126)) ([e0877e3](https://github.com/revanced/revanced-patches/commit/e0877e33814ba396e64e18a577064aa5be952413))
* **youtube/settings:** fix non functional back button in settings ([#2178](https://github.com/revanced/revanced-patches/issues/2178)) ([46da834](https://github.com/revanced/revanced-patches/commit/46da83430f69b451f971bf5e9261e9d64d1a365c))
* **youtube/sponsorblock:** fix skip button in wrong location when full screen and comments visible ([#2051](https://github.com/revanced/revanced-patches/issues/2051)) ([30a954c](https://github.com/revanced/revanced-patches/commit/30a954cac83a66fbb25589edc487797ea5f19986))
* **youtube/sponsorblock:** fix toast shown when scrubbing thru a paused video ([#2152](https://github.com/revanced/revanced-patches/issues/2152)) ([c6c23ff](https://github.com/revanced/revanced-patches/commit/c6c23ff0d9a18e3ef3d4b9b28ffa562a2eceb58b))
* **youtube/theme:** apply custom seekbar color to video thumbnails ([#2085](https://github.com/revanced/revanced-patches/issues/2085)) ([d497027](https://github.com/revanced/revanced-patches/commit/d4970273ad10f62cd9455ef9b847c686147f7dca))
* **youtube/vanced-microg-support:** depend on `client-spoof` patch ([83a4905](https://github.com/revanced/revanced-patches/commit/83a490575c60adf21db926df3013f539c6d33068))


### Features

* **candylinkvpn:** add `unlock-pro` patch ([#2157](https://github.com/revanced/revanced-patches/issues/2157)) ([7159f86](https://github.com/revanced/revanced-patches/commit/7159f867801300d4ae32937743de59421de76238))
* **messenger:** add `disable-switching-emoji-to-sticker-in-message-input-field` patch ([#2099](https://github.com/revanced/revanced-patches/issues/2099)) ([ac5532a](https://github.com/revanced/revanced-patches/commit/ac5532a65c353b1964d9b7d990341fc7362e510d))
* **messenger:** add `disable-typing-indicator` patch ([#2115](https://github.com/revanced/revanced-patches/issues/2115)) ([5d1de4f](https://github.com/revanced/revanced-patches/commit/5d1de4f4eab83e61cfc1c4aaee74179afcb9431f))
* **reddit:** add `sanitize-sharing-links` patch ([#2192](https://github.com/revanced/revanced-patches/issues/2192)) ([9593e4b](https://github.com/revanced/revanced-patches/commit/9593e4b5db604957545b4ab6747c82fb815ac08b))
* **reddit:** remove compatibility version constraints ([#2226](https://github.com/revanced/revanced-patches/issues/2226)) ([f1288e4](https://github.com/revanced/revanced-patches/commit/f1288e4bb8fb1b9f394d73fd814d97db8704b8e0))
* **syncforreddit:** add `disable-ads` patch ([#2066](https://github.com/revanced/revanced-patches/issues/2066)) ([c1de5d6](https://github.com/revanced/revanced-patches/commit/c1de5d6e433263b9a17305fa1c65807921594731))
* **trakt:** add `unlock-pro` patch ([#2210](https://github.com/revanced/revanced-patches/issues/2210)) ([1e8dcae](https://github.com/revanced/revanced-patches/commit/1e8dcae6f540455b8698703bbded5f52fd0c6300))
* **twitch:** add `auto-claim-channel-points` patch ([#2131](https://github.com/revanced/revanced-patches/issues/2131)) ([80fb670](https://github.com/revanced/revanced-patches/commit/80fb6701b52a8c6c6bada5546dffe3438f0e4879))
* use consistent names for patches ([6347146](https://github.com/revanced/revanced-patches/commit/634714690086168e63d6aa9475893135cb58db68))
* **vsco:** add `unlock-pro` patch ([#2168](https://github.com/revanced/revanced-patches/issues/2168)) ([7ffd1a0](https://github.com/revanced/revanced-patches/commit/7ffd1a09a7bcf09bc7e7d5f3c8c8613ca34c8c59))
* **youtube/copy-video-url:** add tap and hold functionality to copy video url buttons ([#2174](https://github.com/revanced/revanced-patches/issues/2174)) ([95bbf46](https://github.com/revanced/revanced-patches/commit/95bbf46e77a608bd7ba8f0073d50fef01012d4df))
* **youtube/hide-player-overlay:** make it toggleable in settings ([#2044](https://github.com/revanced/revanced-patches/issues/2044)) ([f693d55](https://github.com/revanced/revanced-patches/commit/f693d55caf1e0b72bb1f4c39b1eeb59436191e02))
* **youtube/hide-shorts-components:** hide navigation bar ([24f376a](https://github.com/revanced/revanced-patches/commit/24f376a4b8d6bdccc32ffff0d983f22eb4940791))
* **youtube/settings:** add reset button to edit preference dialog ([#2047](https://github.com/revanced/revanced-patches/issues/2047)) ([ede765a](https://github.com/revanced/revanced-patches/commit/ede765ae3c506909ee8a99517b99b6f5f113f01a))
* **youtube/video-speed:** change custom video speeds inside app settings ([#2114](https://github.com/revanced/revanced-patches/issues/2114)) ([d97815a](https://github.com/revanced/revanced-patches/commit/d97815af18e645fd0fa087db0174bcc2a771ec72))
* **youtube:** add capability to filter from protobuf buffer ([b738b6b](https://github.com/revanced/revanced-patches/commit/b738b6bf3506f222844ef4bca99a91f78d331391))
* **youtube:** add `hide-load-more-button` patch ([#2078](https://github.com/revanced/revanced-patches/issues/2078)) ([7170802](https://github.com/revanced/revanced-patches/commit/71708022a06453f6f56c19d686fc505286523391))
* **youtube:** add `hide-filter-bar` patch ([6cc5f61](https://github.com/revanced/revanced-patches/commit/6cc5f61e0712fe25cd45b137773decaf4b9bb582))
* **youtube:** add `hide-shorts-components` patch ([64868f4](https://github.com/revanced/revanced-patches/commit/64868f41be9f567cb54d9214fafbf849d08b64d2))
* **youtube:** add options to disable toasts on connection error ([#2159](https://github.com/revanced/revanced-patches/issues/2159)) ([99916ae](https://github.com/revanced/revanced-patches/commit/99916aefaaea3b94e94e2901d70493fdb18a3dab))
* **youtube:** import / export of revanced settings ([#2077](https://github.com/revanced/revanced-patches/issues/2077)) ([b59cb3e](https://github.com/revanced/revanced-patches/commit/b59cb3ed60293aaf81067ff3469863add09c6b13))
* **youtube:** move video settings to `Video` settings category ([#2010](https://github.com/revanced/revanced-patches/issues/2010)) ([f4b9180](https://github.com/revanced/revanced-patches/commit/f4b918075a70d1a4ed9ac7e9c1f0e0acd1c77404))
* **youtube:** support version `18.19.35` ([491f292](https://github.com/revanced/revanced-patches/commit/491f292182a419cb5399de768560ae4daa7c86cb))




  
**App Versions:**  
YouTube: 18.19.35  
Music (arm64-v8a): 6.03.51  
Music (arm-v7a): 6.03.51  
Twitter: 9.90.0-release.0  
Reddit: 2023.20.1  
Twitch: 14.6.1  
TikTok: 27.8.3  
Spotify-Lite: 1.9.0.29900  
Spotify: 8.8.36.522  
Backdrops: 4.52  
MyExpenses: 3.4.9  
IconPackStudio: 2.1 build 028  
TickTick (arm64-v8a): 6.6.3.1  
NyxMusicPlayer: 2.2.2  
Tasker: 6.1.33  
Instagram-arm64 (arm64-v8a): 284.0.0.22.85  
Instagram-arm (arm-v7a): 284.0.0.22.85  
Facebook-arm64 (arm64-v8a): 415.0.0.34.107  
InShorts-arm64 (arm64-v8a): 5.4.13  
Facebook-arm (arm-v7a): 415.0.0.34.107  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  
