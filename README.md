**Don't combine Twitch specific ad blockers.**

please check [here for updates](https://github.com/pixeltris/TwitchAdSolutions) (if vaft is not working for you)

## Applying a script (uBlock Origin)

- Navigate to the uBlock Origin Dashboard (the extension options)
- Under the `My filters` tab add `twitch.tv##+js(twitch-videoad)`.
- Under the `Settings` tab, enable `I am an advanced user`, then click the cog that appears. Modify the value of `userResourcesLocation` from `unset` to the full url of the solution you wish to use. e.g. `userResourcesLocation https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/master/video-swap-new/video-swap-new-ublock-origin.js` 
- To ensure uBlock Origin loads the script I recommend that you clear your cache/cookies and restart your browser after applying the filter AND script.

To stop using a script remove the filter and make the url `unset`.

*For the sake of security it's recommended to use a permalink when using uBlock Origin (permalinks do not auto update).*


## Scripts

**Try vaft first and use video-swap-new if you have issues with constant reloads/freezing.**

- vaft - (use this one!) [ublock (permalink)](https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/0b5ea5ed8959a6b4eb4c1ea406aaa56313c9c907/vaft/vaft-ublock-origin.js)
  - The same as `video-swap-new` but attempts to get a clean stream faster (may suffer from more freezing / playback issues).

OR you can try:

- video-swap-new - (this might work for some people if you have bad internet/old computer) [ublock (permalink)](https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/2eefb984c10ba64e9528b8cf4350d5fab653bd3a/video-swap-new/video-swap-new-ublock-origin.js)
  - Uses a lower resolution stream during ads.
