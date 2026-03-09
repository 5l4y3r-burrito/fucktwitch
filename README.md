**Don't combine Twitch specific ad blockers.**

please check [here for updates](https://github.com/pixeltris/TwitchAdSolutions) (if vaft is not working for you)

## Applying a script (uBlock Origin)

- Navigate to the uBlock Origin Dashboard (the extension options)
- Under the `My filters` tab add `twitch.tv##+js(twitch-videoad)`.
- Under the `Settings` tab, enable `I am an advanced user`, then click the cog that appears. Modify the value of `userResourcesLocation` from `unset` to the full url of the solution you wish to use. e.g. `userResourcesLocation https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/f8f86706daf90daa534b26bce5b2f01238667d5f/vaft/vaft-ublock-origin.js` 
- To ensure uBlock Origin loads the script I recommend that you clear your cache/cookies and restart your browser after applying the filter AND script.

To stop using a script remove the filter and make the url `unset`.

*For the sake of security it's recommended to use a permalink when using uBlock Origin (permalinks do not auto update).*
## Last Script (forever release)

 (vaftf8) NEW!!! [USE THIS ONE] - https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/f8f86706daf90daa534b26bce5b2f01238667d5f/vaft/vaft-ublock-origin.js

## Script history

 (vaftf55) - https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/f5594de4ef5eadd8d3aa156c24cbc53f17ab606c/vaft/vaft-ublock-origin.js
 (vaft0b5) - https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/0b5ea5ed8959a6b4eb4c1ea406aaa56313c9c907/vaft/vaft-ublock-origin.js
 (vaft914) - https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/914f4ec6bd56b71e75b5da2d70646c825475c3bb/vaft/vaft-ublock-origin.js
 (vaft223) - https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/233bedd48bd44a999e9cb7bc15c200115a522747/vaft/vaft-ublock-origin.js

## Scripts [OLD ARCHIVED] (one of these may work for you)

**Try vaft first and use video-swap-new if you have issues with constant reloads/freezing.**

- vaft - (use this one!) [ublock (permalink)](https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/f8f86706daf90daa534b26bce5b2f01238667d5f/vaft/vaft-ublock-origin.js)
  - The same as `video-swap-new` but attempts to get a clean stream faster (may suffer from more freezing / playback issues).

OR you can try:

- video-swap-new - (this might work for some people if you have bad internet/old computer) [ublock (permalink)](https://raw.githubusercontent.com/pixeltris/TwitchAdSolutions/f8f86706daf90daa534b26bce5b2f01238667d5f/video-swap-new/video-swap-new-ublock-origin.js)
  - Uses a lower resolution stream during ads.
