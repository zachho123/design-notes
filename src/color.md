# Color

## General

- Approach a project with a constrained/focused pallete
- Be aware of target demographic, different colors can mean different things to different groups
- In general, lighter elements feel closer and darker elements feel further away
- To make something feel inset on a light background, give it an off-white color (be careful not to make it look like a disabled state)
- Prevent clashing colors ie: background of avatar/headshot images on colored background by adding a white/black border around the image
- Grays don't have to be gray, saturate with some color to give a cooler/warmer feel
- There exists a "rule" that color schemes work best when used proportionately, 60% primary color, 30% secondary color, 10% accent color

## Perceived Brightness

- Every hue has an inherant perceived brightness - luminance
![Hue Luminance Wheel](/images/hue-brightness-wheel.png)
![Hue Luminance Plot](/images/hue-luminance-plot.png)
- Normally, when you want to change how light a color looks, you change the lightness value, however this can result in a loss of saturation
  - Because hues have different perceived brightnesses, you can change the brightness of a color by rotating the hue to the nearest bright color
  - This trick works well with text on colored backgrounds

## Color Psychology

- Black: luxury, sophistication, elegance
- White: 
- Red: error
- Yellow: happy
- Orange:
- Green: wealth, nature, growth, success
- Blue: intelligence
- Purple:

## Light and Dark Themes

When creating a light/dark theme, for background elements, *don't* just invert the colors. We want the same visual queues in both designs (ie: the lighest colored element in the light-themed UI, should remain the lightest color element in the dark-themed UI). For text you *do* want to invert.