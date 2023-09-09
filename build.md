YouTube: 18.32.39  
Music (arm64-v8a): 6.18.52  
Music (arm-v7a): 6.18.52  
Twitter: 10.6.0-release.0  
Twitch: 15.4.1  
TikTok: 31.2.4  
Reddit: 2023.35.0  
Spotify: 8.8.66.563  
Backdrops: 4.52  
NyxMusicPlayer: 2.2.7  
Spotify-Lite: 1.9.0.45033  
IconPackStudio: 2.2 build 012  
TickTick (arm-v7a): 6.7.0.2  
TickTick (arm64-v8a): 6.7.0.2  
Tasker: 6.2.12-rc  
Instagram (arm64-v8a): 275.0.0.27.98  
Instagram (arm-v7a): 275.0.0.27.98  
InShorts (arm64-v8a): 5.6.6  
InShorts (arm-v7a): 5.6.6  
Music-Extended (arm64-v8a): 6.17.52  
Music-Extended (arm-v7a): 6.17.52  
YouTube-Extended: 18.35.35  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-3.1.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.117.1.apk  
Patches: ReVanced/revanced-patches-2.190.0.jar  

### [2.190.0](https://github.com/ReVanced/revanced-patches/compare/v2.189.0...v2.190.0) (2023-09-03)
### Bug Fixes
* **Infinity for Reddit - Spoof client:** Support latest version ([8a5311b](https://github.com/ReVanced/revanced-patches/commit/8a5311b1e645ca2aab1e416d647cf52bf0be6e7f))
### Features
* **Photomath:** Support latest version ([5a2cad0](https://github.com/ReVanced/revanced-patches/commit/5a2cad077f03880ee1417c5cfd448bbdea4c07e2))
* **Twitch:** Support version `16.1.0` ([#2923](https://github.com/ReVanced/revanced-patches/issues/2923)) ([d9834a9](https://github.com/ReVanced/revanced-patches/commit/d9834a9abb43390af4cb33f5dd5a0e2d3b7060e2))

---
CLI: ReVanced/revanced-cli-3.1.0-all.jar  
Integrations: YT-Advanced/revanced-integrations-0.119.0.apk  
Patches: YT-Advanced/revanced-patches-2.190.1.jar  

### [2.190.1](https://github.com/YT-Advanced/ReX-patches/compare/v2.190.0...v2.190.1) (2023-09-09)

# YouTube
- **feat(youtube)**: add support version `v18.35.xx`
- **feat(youtube/hide-player-flyout-panel)**: Hide Caption footer https://github.com/YT-Advanced/YT-Advanced/issues/111
- **fix(youtube/hide-player-flyout-panel)**: Not worked
 https://github.com/YT-Advanced/YT-Advanced/issues/112
- **fix(youtube/custom-playback-speed)**: Does not work on tablet devices
- **fix(youtube/custom-playback-speed)**: When user opens the sharing panel, the custom playback speed panel opens
- **fix(youtube/hide-layout-components)**: Custom filters are separated by commas instead of line-by-line
- **fix(youtube/hide-layout-components)**: Expandable chip under videos not hidden in related videos
- **fix(youtube/old-quality-layout)**: Does not work on tablet devices 
- **fix(youtube/overlay-button)**: Overlay button not hidden when scrubbing seekbar https://github.com/YT-Advanced/YT-Advanced/issues/7
# YouTube Music
- **feat(music)**: Add `enable-old-style-library-shelf` patch
- **feat(music)**: Add `enable-playback-speed` patch
- **feat(music)**: Add `hide-button-container-labels` patch
- **feat(music)**: Add `hide-emoji-picker` patch
- **feat(music)**: Add `hide-flyout-panel` patch
- **feat(music)**: Add `hide-radio-button` patch
- **feat(music)**: Add `hide-sample-button` patch
- **feat(music)**: Add `hide-tooltip-content` patch
- **feat(music)**: Add `hook-download-button` patch
- **feat(music)**: Add `remember-playback-speed` patch
- **feat(music)**: Add `return-youtube-dislike` patch https://github.com/YT-Advanced/YT-Advanced/issues/108
- **feat(music)**: Delete `share-button-hook` patch
- **feat(music)**: Remove decoding-patch that are no longer used
- **feat(music/amoled)**: Patch now applies the amoled theme to the comment input box as well
- **feat(music/enable-custom-filter)**: Separate filters by line instead of commas
- **feat(music/settings)**: Apply material style to alert dialog
- **feat(music/settings)**: Change some default value
- **feat(music/settings)**: Remove divider from settings
- **feat(music/settings)**: When installing for the first time, a reboot dialog is shown
- **feat(music/shared-resource-id)**: If the target resource ID is not found, empty index is returned instead of generating patch exception
- **feat(music/hide-get-premium)**: Patch now also hides the premium membership label in settings
- **fix(music/settings)**: Blank screen appears when text input dialog is shown
- **refactor(music/settings)**: Change settings structure
---  
