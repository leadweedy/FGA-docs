## Step 1
Force-stop FGA or restart your phone and see if that works.  
This is a quick-fix for battery optimization issues.

## Other screen recorders
Don't use other screen recorders with FGA, if you do, force-stop FGA if it doesn't work properly.  
When recording for bug-reports for FGA, use the inbuilt recorder from `More options/Advanced/Record screen`.

## PlayStore?
No more ([#616](https://github.com/Fate-Grand-Automata/FGA/issues/616)).
Download it from [here](https://github.com/Fate-Grand-Automata/FGA/releases)

## Error on install?
Android 7 or above needed.  
The latest version of Nox doesn't work.

## Where's 'Script Mode', Lottery, FP, Support Image Maker?
The app automatically detects which script can be run on the current screen.  
It will show the relevant option when you click on the PLAY button.  
Support Image Maker shows up as a button on the bottom-left corner of the popup if you click on the PLAY button on the support screen.

## Where's the PLAY button?
The PLAY button only appears when you switch your phone to horizontal mode, for example when you start FGO. If it still doesn't appear you can try a combination of stopping and starting accessibility and force-closing FGA until it appears.

If the button disappears overnight or when you lock your screen, then battery optimization is at fault. See [#314](https://github.com/Fate-Grand-Automata/FGA/issues/314).

## Having trouble on Emulators?

See [Running on Emulators](Running-on-Emulators)

# IMPORTANT: Make sure the game looks as FGA wants it to

If you're having trouble, this is mostly related.
See [Game Area detection](Game-Area-detection)

## Clicking on PLAY doesn't open the popup to start scripts?
Game booster/Game mode or other app blocking notifications/popups when a game (FGO) is running.
Turn them OFF. Known to happen on some LG, Samsung and Motorola.

For LG:
Turn OFF Game Tools since it has the feature to prevent ALERTS from showing up.  
This prevents the dialog which lets you pick AutoSkill config from showing up.  
https://www.lg.com/us/support/help-library/lg-g7-thinq-gaming-tools-CT10000027-20150726480680

On other phones, if you have something like a Game Booster that blocks alerts from other apps when playing a game, turn it OFF.
Instructions would vary depending on your device, so Google.

## Worked before, doesn't work now

See [#314](https://github.com/Fate-Grand-Automata/FGA/issues/314)

## Keeps asking for Accessibility even after turning it ON

See [#314](https://github.com/Fate-Grand-Automata/FGA/issues/314)

## Uses skills on the wrong servant or doesn't use skills at all

Do you have skill confirmation ON in FGO?  
If so, either turn that OFF or turn ON `More options/Skill confirmation` in FGA.

## Not picking NP/cards on Attack screen OR Got stuck in some info screen

Is it just your phone lagging badly? If so, either get a new phone or try increasing the delays in `More options/Fine-tune`.

## Doesn't work on some screens

1. Check that you're not placing the PLAY button in a weird place.  
   See [Where should I place the PLAY button?](#where-should-i-place-the-play-button)

2. Is there some overlay on your phone/emulator screen that can screw up image matching?  
   For example:
   
   <img src="img/overlay.jpg" width="300">

## Where should I place the PLAY button?

Bottom-left corner is ideal. While you can drag the button around to other places, there is a possibility of screwing things up if it comes in the way of image matching.

## Merlin's costume is not detected

For a long time, a wrong Merlin image was part of FGA. It was corrected in version 1474.

If you see a colored image in your Support/Merlin folder, you need to correct the image:

1. Install latest canary
2. Delete merlin_c.png in your Merlin support folder
3. Go to FGA's `More Options` -> `Storage` and choose `Extract Default Support Images`
4. Stop FGA's accessibility service
5. Force close FGA and clear its cache
6. Restart FGA

After that, Merlin's costume should be detected.