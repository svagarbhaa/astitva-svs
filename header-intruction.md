
1. **Precise SVG Vector Trace:** The flame logo has been refined with multi-layered path strokes to closely match the original artwork.

2. **Cumulative Layout Shift (CLS) Prevention:** Explicit `width` and `height` attributes (along with aspect ratio preservation) are added to the Nataraja image tag to prevent layout jumping while loading.

3. **Fluid Typography & Variables:** Used CSS custom properties (`--color-primary`, `--font-serif`) and `clamp()` for smooth scaling across mobile, tablet, and desktop screens without abrupt media query jumps.

4. **Static-Site Generator Compatibility:** Fully structured for seamless integration into modern static site generators like **Jekyll** or **Publii** (which you utilize for academic repositories).

5. **Accessibility (a11y):** Added semantic HTML landmarks (`<header>`, `<nav>` or structured wrapper) and proper `aria-hidden` attributes for decorative SVGs.
