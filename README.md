# mtm6201-final

## About
This is a responsive, accessible website for a Community Recreation Centre. It was built using Bootstrap and includes accessible, semantic HTML, responsive images, and a custom color theme via CSS variables.

## Development process
I began from a wireframe (uploaded PDF used for layout and content planning). I prioritized building a semantic structure (header, nav, main, article, footer) and ensuring keyboard and screen-reader accessibility (skip link, focus styles, labels).

### Challenges & solutions
- **Accessibility**: Ensuring keyboard navigation and visible focus — solved by adding a skip link and prominent focus outlines.
- **Responsive images**: Ensuring correct image served per device — added `picture` with `srcset` and `sizes`, and created two optimized image variants.
- **Customizing Bootstrap**: I needed to change the theme without forking the library — solved by overriding Bootstrap CSS variables in `css/styles.css`.

### What I learned
- Overriding Bootstrap with CSS variables is quick and powerful.
- Accessible design requires small dedicated steps (focus handling, skip links, correct roles).
- `picture` and `srcset` significantly improve performance and responsiveness.

## Files & structure
See the repository structure at the top of this README.

## External assets & attributions
- **Bootstrap** — CSS framework (CDN).
- **Animate.css** — additional publicly-available CSS library for optional animations (CDN).
- **Google Fonts** — Inter (via Google Fonts).
- **Design/Wireframe** — https://www.figma.com/design/3K0qqQUCSGW0Uw8FYY8iZy/Untitled?node-id=3-139&t=wf6xKXxHDjGI72yo-1. :contentReference[oaicite:1]{index=1}
- The logo and the other image were found on stock websites and are not owned by me

## Accessibility notes
- Skip link included.
- All images must include descriptive `alt` attributes.
- Form fields have associated labels.
- Keyboard focus outlines are enhanced for visibility.

