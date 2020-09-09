## Where to put Servant/CE images?
Under `Fate-Grand-Automata/support/` folder, put:
- Servant images in `servant` folder
- CE images in `ce` folder
- Friend name images in `friend` folder

The app has some common Servant/CEs inbuilt. You can extract them using the `Extract Default Support Images` option within an AutoSkill config.
The app should extract them automatically when you go to the AutoSkill config screen.
If you want to use any other preferred servant or ce, you have to create their images using `Support Image Maker` script.

Instead of having to select multiple ascension images for a servant, you can put all the images of a servant in a folder and select the folder in settings.

Here's what a typical directory structure looks like:

```
Fate-Grand-Automata/
-- support/
-- -- servants/
-- -- -- ozy4.png
-- -- -- melt4.png
-- -- -- Merlin/
-- -- -- -- merlin1.png
-- -- -- -- merlin2.png
-- -- -- -- merlin3.png
-- -- -- -- merlin4.png
-- -- -- -- merlin_c.png
-- -- -- Waver/
-- -- -- -- waver1.png
-- -- -- -- waver2.png
-- -- -- -- waver3.png
-- -- -- -- waver4.png
-- -- ce/
-- -- -- kscope.png
-- -- -- black_grail.png
-- -- friend/
-- -- -- mathew.png
-- -- -- recon.png
```

## How to use Support Image Maker?

`Support Image Maker` automatically creates images from the Support screen that can be used with the script.
You can also use it from the Friend List which is easier since you don't have to keep refreshing till the desired Servant/CE shows up.

> Support Image Maker is calibrated for NA and JP. It might not work correctly on other servers where an older format of support screen is still used.

1. Set the `Script Mode` option in Settings to `Support Image Maker`.
2. Now, click on `Toggle Service` button, the `Play` button shows itself.
3. Open F/GO. Go to support selection or friend list screen and ensure that the Servant/CE you want is visible (It is important that the complete Servant + CE region is visible).
4. Click on Play. Support Image Namer dialog should pop up.
5. Check the images you want to keep. Type a name for the image (NO NEED for file-format like `.png`).
   For servant images, you can use a folder like: `Nero/asc1`. This will save an image named `asc1.png` in `Fate-Grand-Automata/support/servant/Nero` folder. By grouping in a folder, you can pick a single entry in settings to match with all ascensions and costumes.
6. Click on `Done`. The selected images are saved to the correct folders.
5. Use the images with Auto Support Selection.