# Remove Logo From Background Photoshop Action

`Version 1.01`

Super simple action for removing background logos or other graphics from product images. Requires an image with the logo by itself.

#### Installation:

1. Download [Remove-Logo-From-Background.atn](https://github.com/neoqueto/remove-logo-from-background/raw/main/Remove-Logo-From-Background.atn "Remove-Logo-From-Background.atn")
2. Run Photoshop
3. Open the Actions panel (default shortcut: Alt + F9)
4. Open the Actions panel menu by clicking the hamburger icon
5. Click on "Load Actions..."
6. Locate "Remove-Logo-From-Background.atn"

#### Prerequisites:

1. Make sure to have at least two layers in the document:
    1. The topmost layer should contain the entire unwanted graphic
    2. The layer underneath should contain the unwanted graphic partially obstructed by the subject
2. Background layer is optional, if used, it should be at the very bottom
3. The topmost layer must be selected before running the action

#### Usage:

Simply select the "Remove Logo From Background" action from the Actions panel and press "Play selection" (►)

#### Limitations:

1. Creates jagged edges (fixable)
2. Untested on black backgrounds
3. Can leave JPEG artifacts behind
4. May not work well with semi-transparent obstructions (eg. plastic bottle, stained glass, thin fabric)
5. Currently not a batch process that works across many files
