# Mitti Studio: 3D Custom Pottery Shop

A single-page 3D pottery shop built with Three.js, HTML, CSS and JavaScript. Customers shape a piece on a potter's wheel, see the price update live, and check out over WhatsApp.

## Features

- Five piece types: pot, dish, vase, cooking pot and cup, each with several styles
- Adjustable height, width and opening, plus handle count and handle style
- Patterns (flowers, leaves, fish, birds, dots, stripes), glaze colors and matte, satin or glazed finishes
- Live rupee pricing, a cart drawer and WhatsApp checkout
- Designs saved in the browser (localStorage)
- Scroll-driven shape morphing, drag to turn the piece, a kiln intro and a kiln save animation

## How it works

- Each piece is a lathe shape built from a curve profile, so changing a slider rebuilds the curve.
- The throwing rings come from a generated bump texture; patterns are drawn on a canvas and used as a texture.
- There is no backend: the cart and saved designs live in the browser, and orders go out as a pre-filled WhatsApp message.

## Run it

Open `index.html` in a browser. It loads Three.js and fonts from a CDN, so it needs an internet connection.

