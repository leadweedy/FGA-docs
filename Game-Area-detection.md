## How FGO should look on JP/KR (wide-screen update)

Should fill the entire screen including the notch.

There should be no black bars on the screen. If there are, switch your phone from Gesture Navigation to 3-button navigation.

## How FGO should look

For FGA to work, FGO should be centered on your phone's screen excluding notch (hole on screen for front camera)

This is what your phone should look like:

16:9                                   | Not 16:9, no notch                                                    | Not 16:9, has notch 
---------------------------------------|-----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------
FGO should fill the entire screen      | FGO should be centered on screen with blue borders (no black borders) | FGO should be centered in the area exluding notch with blue borders. Notch area should be black.
<img src="img/inside.jpg" width="300"> | <img src="img/outside-notchless.jpg" width="300">                     | <img src="img/outside.jpg" width="300">

## When to use Ignore notch calculation?
If your phone has a notch, but the notch area is also filled by blue borders, turn ON `Ignore Notch calculation`.

**NOTE:** `Ignore notch calculation` is ignored on servers with the wide-screen update (JP/KR).

## FGO looks different on my phone

Multiple cases may apply to your phone.

### CASE 1: Borders around FGO are black

If FGO is centred on the screen, even if the borders are black, then it might work as it is. If this is case and your phone has a notch, turn ON 'Ignore Notch calculation'.

Otherwise, you'll have to make FGO a full-screen app.  
Only if that doesn't work, check if you can make FGA full-screen too.

For example, this won't work:  
<img src="img/samsung-black.jpg" width="500">

#### Samsung phones
- Open `Settings` app.
- Search for and select `Full screen apps`.
- Turn ON the switch for FGO.

#### Huawei phones
- Open `Settings` app.
- Go to `Display & brightness > More display settings > Full-Screen Display`.
- Turn ON the switch for FGO.

### CASE 2: Your phone has a notch, but the blue borders of FGO extend over the notch

Turn ON `Ignore Notch calculation` in `More options`.

This was the case with Samsung phones before a OneUI update. You might have to do this if you're still on an older version of OneUI.

### CASE 3: Your phone has borders around FGO even at the bottom of screen

LGv60                                  | Google Pixel 4L
---------------------------------------|-----------------------
<img src="img/lg-v60.png" width="300"> | <img src="img/pixel-4L.png" width="300">

The black border are for gesture navigation.

To get rid of them:
- Go to `Settings > System > Gestures > System Navigation`.
- Change to `3-button navigation`.

### CASE 4: Your phone is Android 7 or 8 and has a notch

Notch detection is only possible on Android 9 and above. Either update your phone or find a way to disable notch in your phone's settings.

I don't have any solutions here. If you're a programmer you can fork the code and tweak the regions I guess.

These are some phones that fall into this category:
- Sharp Aquos C10 (SH-Z01) [GP#1061](https://community.gamepress.gg/t/automatic-farming-app-fate-grand-automata/72155/1061)
- Huawei Y7 [#482](https://github.com/MathewSachin/Fate-Grand-Automata/issues/482)
- LG G7 [#455](https://github.com/MathewSachin/Fate-Grand-Automata/issues/455) **JUST UPDATE YOUR ANDROID VERSION**
- Oukitel u18 [#373](https://github.com/MathewSachin/Fate-Grand-Automata/issues/373)

<img src="img/notch-8.jpg" width="500">