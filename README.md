# Bennett Law Office — Split Layout version

Desktop build of the Paper file **"Logan Bennett Site"**. It's separate from the other Bennett builds (`Bennett-Website`, `Bennett-Blue-Website`, `Bennett-Center-Layout`), each of which lives in its own repository.

Static HTML, no build step: everything is in `index.html`, with fonts and photos in `assets/`.

- 1440px desktop design on a 9-column grid: 20px margins, 10px gutters. Widths are calculated from the column size, so the layout scales with the browser width.
- Sections: split hero (full-bleed photo left, copy right), "A Montana advantage" (off-white), six situations (blue), a scroll moment, and the vehicle list (off-white).
- Scroll moment: a photo starts across columns 4–6, straddling the blue/off-white change. It grows to full screen as you scroll, and then the centered title fades in. Visitors with reduced motion turned on skip the growth.
- Type: Successor Light (titles/subheaders) and Malamocco Book (body), always at their default letter and line spacing.
- Grid guides: shown on localhost and hidden on the live site. Press **G** to toggle them.
- Fonts are trial versions and need web licenses before launch.

Published with GitHub Pages from the `split-layout` branch.
