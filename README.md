# ad-manager-firebot-setup
Ad Manager for Twitch streams. Two parts 1) A timer that will give a 60 second notification for streamer and chat that an ad is coming up (both in chat and in the Firebot overlay), sound notification of the same (via TTS), followed by customized ad duration  and 2) A customizable on stream start ad run to mitigate pre-roll ads.

# Compatibility
+ Firebot 5.58.0+

# Install
+ Download
    + Ad Manager.firebotsetup
    + countdowns.html
+ Import the downloaded firebotsetup file
    + You will need to edit the preset effect to change the location of the html file

# Usage
+ Customize
    + Change the Event '[Ads] Run Starting Screen Ads'
        + Delay timer, currently set at 60 seconds (or 1 minute)
        + Ad Break for desired duration, currently set to 180 seconds (or 3 minutes) to prevent pre-rolls
        + Toggle Ads Starting Soon Countdown to use the preset effect list OnScreenTimer
    + Change the Time-Based 'Ad_tmr'
        + Timer interval for when you would like to have the ad run, currently set at 3540 seconds (or 59 minutes)
        + Ad Break for desired duration, currently set at 180 seconds (or 3 minutes) to prevent pre-rolls
        + Announce for content
        + Text to Speech for content or swap for any other audio alert
        + Add an event for OBS stopped streaming to disable the Ad_tmr effect
    + Change the TTS
        + This setup uses a custom tts, that is not included

# Credits
Modeled after a setup posted by Cinnabadger
