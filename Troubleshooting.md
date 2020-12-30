## Why can't I find it on PlayStore?
The app was unlisted until proper JP support. See [#616](https://github.com/Fate-Grand-Automata/FGA/issues/616).
Links to canary builds in that issue.

## What is the state of JP support?
The canary version kind of works right now. I have checked on multiple phones but still not to the point I would advertise that it would work for everyone.

## Why does it show an error when installing?
Your phone/emulator should be Android 7 or later to use the app.

## Can't find 'Script Mode' option?
There should be a new script displayed on top in the list of scripts when you start. This one would automatically decide which script out of Lottery/FP/Gift Box/Support Image Maker to run.

## Can't start scripts (Mostly LG phones)?

Turn OFF Game Tools since it has the feature to prevent ALERTS from showing up.  
This prevents the dialog which lets you pick AutoSkill config from showing up.  
https://www.lg.com/us/support/help-library/lg-g7-thinq-gaming-tools-CT10000027-20150726480680

## Having trouble on Emulators?

See [Running on Emulators](Running-on-Emulators)

# IMPORTANT: Make sure the game looks as FGA wants it to

If you're having trouble, this is mostly related.
See [Game Area detection](Game-Area-detection)

## Worked before, doesn't work now

Your phone manufacturer's battery optimization is killing the app.

1. Go to https://dontkillmyapp.com and follow the steps properly for your phone manufacturer.
   I mean it when I say properly. I've had cases of people not following those instructions properly and wasting my time for no reason.
2. Restart your phone after following the above steps. You might be able to get away by Force Closing or Clearing the Cache for the app.
3. If that doesn't work, see if there are apps on your phone that can kill FGA, like some 3rd party battery saver.
4. If still doesn't work, there's nothing more I can do for you. There's no point in bothering me with this issue, it's how your phone works.

## Keeps asking for Accessibility even after turning it ON

Same steps as [Worked before, doesn't work now](#worked-before-doesnt-work-now)

## Uses skills on wrong servant or doesn't use skills at all

Do you have skill confirmation ON in FGO?
If so, either turn that OFF or turn ON `More options/Skill confirmtaion` in FGA.

## Not picking NP/cards on Attack screen OR Got stuck in some info screen

Is it just your phone lagging badly? If so, either get a new phone or try increasing the delays in `More options/Fine-tune`.

## Doesn't work on some screens

1. Check that you're not placing the PLAY button in a wierd place.  
   See [Where should I place the PLAY button?](#where-should-i-place-the-play-button)

2. Is there some overlay on your phone/emulator screen which can screw up image matching?  
   For example:
   
   <img src="img/overlay.jpg" width="500">

## Where should I place the PLAY button?

If you have a non-16:9 phone, it is best to place the PLAY button outside FGO on the blue borders.

<img src="img/outside.jpg" width="500">

If your phone is 16:9, the default placement at bottom-left corner is ideal. While you can drag the button around to other places, there is possibility of screwing things up if it comes in the way of image matching.

<img src="img/inside.jpg" width="500">