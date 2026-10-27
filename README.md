# Carousel Libraries QA Lab

Static GitHub Pages test lab for Embla, Flickity, Glide, Keen, Owl, Slick, and Splide.

Deploy `index.html` at repository root, enable GitHub Pages for main / (root). CDN internet access required.

Includes 9 cases per library (63 instances total). Not every case is natively supported by every library: for example Owl vertical is not a vertical slider and Glide free dragging is approximated by threshold changes. These cases are deliberately kept visible for cross-library comparison; verify actual capabilities before treating as feature parity.

For VWO Editor testing: select text and nested slide elements; edit styles; add/remove slides; use lifecycle controls; inspect the event log and console. Reinitialization after destroy may require a page reload for some engines because their destroy methods alter markup.
