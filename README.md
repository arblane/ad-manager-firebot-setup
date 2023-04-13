# ad-manager-firebot-setup

Ad Manager for Twitch streams. Two parts 1) A timer that will give a 60 second notification for streamer and chat that an ad is coming up (both in chat and in an overlay), sound notification of the same (via TTS), followed by customized ad duration  and 2) A customizable on stream start ad run to mitigate pre-roll ads.

# Install
To install, download the file "Ad Manager.firebotsetup" and the 2 PNG files (or use your own).

Import setup for Firebot by going to Settings > Setups > Import Setup.

Choose the file "Ad Manager.firebotsetup" from the location you just downloaded it to, then click Import setup.

# Usage

## Customize
+ Change the Event '[Ads] Run Starting Screen Ads'
    + Image/Gif for content and location
    + Ad Break for desired duration, it is currently set to 180 seconds to prevent pre-rolls

+ Change the Time-Based 'Ad_tmr'
    + Timer interval for when you would like to have the ad run, currently set at 1500 seconds (or 25 minutes)
    + Image/Gif x2 for content and location
    + Announce for content
    + Text to Speech for content, or swap for any other audio alert
    + Ad Break for desired duration

# Credits
Modeled after a setup posted by Cinnabadger