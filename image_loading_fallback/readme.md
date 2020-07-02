# CSS Image Fallback

## Goal

Providing an alternative display to an image when the resource is loading or has failed to load.  

## Feature(s)

Here are implemented features:  

- Display a load indicator (spinner) while loading
- Place a chosen image on top of the load indicator when the load finishes
- When the image fails to load, indicate the load has failed

Note: CSS Image Fallback cannot display indicators when displaying image is blocked in browser settings

## Possible Modifications

Here are possible modifications: 

- Customize load indicator and load fail indicator
- Replace load indicator and load fail indicator with texts instead of used SVG files (see the above note)
