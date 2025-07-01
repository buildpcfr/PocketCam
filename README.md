# PocketCam

A minimal landing page showcasing the PocketCam camera.

Open `index.html` in your browser to view the page.

## Overview

The landing page consists of:

- A header with the PocketCam brand name.
- A tagline and short product description.
- A main product image and a "Buy Now" button.
- A gallery featuring three example photos.

These sections can be seen in `index.html` starting at line 8.

## Replacing Images and Text

1. Edit `index.html` in a text editor.
2. Update the `<h1>`, `<h2>` and `<p>` elements with your own text.
3. Replace the `src` URLs in the `<img>` tags to use your images. Be sure to keep the `alt` text descriptive.

## Customizing Styles

All colors and fonts are defined in `style.css`:

- Body background and font are set in lines 1–7.
- Header and button colors are defined at lines 9–13 and 35–44 respectively.

Modify these values to change the look of the page. To use a different font, update the `font-family` property.

### Enabling Dark Mode

You can create an optional dark theme by adding a `.dark-mode` class to the `body` element and overriding colors in `style.css`:

```css
body.dark-mode {
  background-color: #222;
  color: #eee;
}
header.dark-mode {
  background-color: #000;
}
button.buy-btn.dark-mode {
  background-color: #444;
}
```

Toggling the `dark-mode` class will switch the site to dark colors.
