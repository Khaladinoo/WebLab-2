# Assignment 2 - CSS Layouts and Presentation

## File Organization
- `index.html`: The structural markup containing a container with six lettered boxes (`A` through `F`).
- `styleA.css`: Implements a vertical layout using CSS Flexbox with dynamic vertical spacing (`space-between`), horizontal centering, alternating background colors, and unique border styling for the final element.
- `styleB.css`: Implements an inline horizontal sequence that suppresses wrapping via `white-space: nowrap`, features interactive `:hover` state transitions, dotted border accents, and viewport-locked fixed positioning for element `F`.

## Challenges Faced
1. **Dynamic Vertical Spacing in Version A**: Meeting the requirement that boxes never resize or overlap while gaps scale dynamically with window height was solved using Flexbox on a `100vh` container with `justify-content: space-between`.
2. **Preventing Row Wrapping in Version B**: Keeping boxes strictly on a single horizontal row even on very narrow viewports was achieved through `white-space: nowrap` and `display: inline-block`.
3. **Decoupling Element F from Normal Flow**: Extracting element F to anchor to the bottom-right corner of the browser viewport without altering the unified HTML structure was resolved using `position: fixed`.
