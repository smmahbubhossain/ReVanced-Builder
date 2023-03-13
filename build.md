CLI: revanced-cli-2.21.0-all.jar  
Integrations: revanced-integrations-0.99.25.apk  
Patches: revanced-patches-2.164.25.jar  

### YouTube
- add `enable-timestamps-speed` patch
- fix: `hide-mix-playlists` patch hiding video description under some videos inotia00/ReVanced_Extended#454
- fix: `hide-suggested-actions` patch is broken
- fix: `Hide shorts player subscriptions button` does not work at tablet layout and old layout
- fix(sponsorblock): when the button container is hidden, skip button is in the wrong place
- refactor: change some setting default values
- refactor(default-video-speed): now, default video speed does not apply when playing live video
- refactor(hide-music-button): apply better patch method
- refactor(litho): minor optimization
- refactor(overlay-button): reduced the size of overlay buttons (previously reduced by 20% → now reduced by 30%)
- refactor(overlay-button/copy-url): now, long pressing the copy link button copies the link with timestamp inotia00/ReVanced_Extended#108
- refactor(overlay-button/speed): adjust the space spacing of speed dialog
- refactor(sponsorblock): adjust the space spacing of timestamps
- crowdin translation update
`Arabic`, `Chinese Simplified`, `French`, `Italian`, `Japanese`, `Korean`, `Portuguese (Brazilian)`, `Spanish`, `Ukrainian`, `Vietnamese`

### YouTube Music
- add disable-auto-captions patch inotia00/ReVanced_Extended#328
- fix: hide-get-premium patch breaks account popup layout in tablet inotia00/ReVanced_Extended#426
crowdin translation update
`Spanish`, `Ukrainian`

### ETC
- add support YouTube v18.09.39
- code cleanup
- remove deprecated manifest permission

※ Compatible ReVanced Manager: v0.0.56
※ courtesy: inotia00
  
**App Versions:**  
YouTube: 18.09.39  
Music (arm64-v8a): 5.47.53  
Music (arm-v7a): 5.47.53  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or Music  

[revanced-magisk-module](https://github.com/kazimmt/ReVanced-Builder)  
