# Spark AR Components
A humble yet passionate attempt to provide reusable Spark AR Studio components for everybody.

## How to use blocks
 - Download the files
 - In Spark AR Studio, go to `File` > `Import From Computer...`
 - Pick the downloaded block that you want to use
 - In Assets pane, find your imported block under `Blocks`, drag and drop it anywhere in your scene (though directly dropping it inside `Device` > `Camera` is a good idea)
 - Open patch editor if not already open
 - Drag and drop your instance of the block (the one inside the `Scene` pane, *not* the one from `Assets` pane) into the patch editor.
 - You can now use your block!

## Hue Shift
A block that outputs hue-shifting colors (rainbow effect). Can be used directly at patch for any color input. Adjustable duration and enable switch. Just connect the `Color` output to any port of type `Color` and enjoy the rainbow effect.
