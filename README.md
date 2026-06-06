# Zoom Lens Magnifier

An interactive circular magnifying glass effect built with pure HTML, CSS, and JavaScript. Upload any image to see the zoom lens in action.

## Features

- Circular zoom lens that follows your cursor
- Custom image upload (drag & drop or file picker)
- Adjustable zoom level and lens size
- Smooth enter/exit animations
- Touch device support
- Zero dependencies — single-file implementation

## How It Works

The same image is rendered in two layers. The upper layer is scaled up with CSS `scale()`, and a circular viewport is carved out using `mask-image: radial-gradient(...)`.

## Live Demo

[Live Demo on Vercel](https://zoom-lens-beryl.vercel.app)

## License

MIT
