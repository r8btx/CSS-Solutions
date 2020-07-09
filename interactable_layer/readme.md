# Interactable Layer

## Demo

https://r8btx.github.io/CSS-Solutions/interactable_layer

## Goal

Providing an interactive layer in both mouse and touch environment.

## Feature(s)

Here are implemented features:  

- Transparent layer that changes its opacity on :hover.
- One-time animation to cancel the initial transition effect of changing opacity.
- A second layer that blocks interaction for .5 seconds to prevent accidental link activations.
    - .5 second in touch environment activates context menu (link doesn't activate)
- A loading message while an image background loads.
- An image link.

## Possible Modifications

Here are possible modifications: 

- Replace the second layer functionality so the .5 second delay is reduced/removed.
    - z-index transition does not work as intended in some environments (commented out in layer.css).
- Place other interactable elements such as input fields and buttons.
