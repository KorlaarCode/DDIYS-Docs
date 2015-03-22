## All known GET parameters with description

## `w` Width
The `w` parameter stands for the image width. Must be `100 < w < 800`.

## `h` Height
The `h` parameter stands for the image height. Must be `50 < h < 400`.

## `uuid` UUID
The `uuid` parameter stands for user's UUID. A valid UUID is 32 characters long.

## `font` Font
The `font` parameter stands for the font that should be used in the signature.
It is an int ranging from 1 to 9, as seen in the following image:


![fonts](http://hypixel.maxkorlaar.com/dynamic-signatures/fonts-preview.php)

## `displayOutdated`, `displayOutdated_x` and `displayOutdated_y` Display warning for outdated stats.
The `displayOutdated_x` and `displayOutdated_y` parameters define the position where the warning should appear.
If `displayOutdated` is not set or is 0, no warning will be shown. If it is 1, then a small warning triangle will show up
at the specified coords. If it is 2, the triangle will show up with some text next to it stating for how long the
stats are already outdated.
