# Tunghsiao Liu's Automator Workflows
A collection of Automator workflows that speed up your design / development process.

## Add @2x Suffix.workflow
Add @2x suffix for retina image assets.

## Convert Image Format.workflow
Convert selected images to specific format.

## Copy & Add @2x Suffix.workflow
Copy (duplicate) selected images and rename them with @2x suffix. Useful when you want to downscale with your own method.

## Create @2x Image.workflow
Auto downscale retina images generated by [PNG Express](http://www.pngexpress.com/), or any @2x images

**Note**: Export your original images in retina size, WITHOUT `@2x` suffix.

## Create App Iconset.workflow
Create the following sizes of icon resources for your OS X app:

Filename | Size of canvas (in pixels)
--- | ---
icon_512x512@2x | 1024×1024
icon_512x512    | 512×512
icon_256x256@2x | 512×512
icon_256x256    | 256×256
icon_128x128@2x | 256×256
icon_128x128    | 128×128
icon_32x32@2x   | 64×64
icon_32x32      | 32×32
icon_16x16@2x   | 32×32
icon_16x16      | 16×16

The icon you created should be 1024×1024 with an sRGB color profile. You can read more about icon design guidelines [here](http://developer.apple.com/library/mac/documentation/userexperience/conceptual/applehiguidelines/IconsImages/IconsImages.html).

**Note**: You should always select the original file during the workflow, don’t press any key or click your mouse.

## Remove @2x Suffix.workflow
Remove @2x suffix for retina image assets. Useful when you're doing something wrong and need to recreate downscaled images one more time.

## Rename Selected Files.workflow
What? You just bought [A Better Finder Rename](http://www.publicspace.net/ABetterFinderRename/)?

## Resize Images.workflow
Resize your images to specific size or by percentage.

## RestartFinder.app
Restart your Finder, I packed it as an application since bash script has been limited in Mt. Lion.

## ShowFiles.app
Toggle Hidden files in a simple click, you can execute it in [LaunchBar](www.obdev.at/launchbar/).