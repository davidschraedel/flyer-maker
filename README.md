# Flyer Maker

A browser-based flyer and invite maker for events that should look like a person made them, not a template or a machine.

Most generated invites share the same tells: neon palettes, confetti, clip-art icons on every line, every inch filled, and copy that announces the vibe instead of showing it. Flyer Maker is built to avoid those. It gives you real design constraints, plenty of control, and a little controlled randomness, so you can fix a typo or move one word without regenerating the whole thing or opening a full design suite.

## Principles

- **Commit to a style.** Each style is a real rule set (palette logic, type pairing, texture, layout, procedural ornaments), not a skin.
- **Hierarchy first.** One thing is clearly biggest, and the rest steps down.
- **Whitespace on purpose.** Empty space is a design tool.
- **Show, don't tell.** The example copy models specific details over adjectives ("Chili on the stove. Dessert around nine.").
- **Answer the hidden questions.** Parking, plus-ones, kids, when it ends, and an easy next step.
- **You stay in control.** Styles set defaults, but every color, font, weight, tilt, and position can be overridden.

## Features

### Content & Typography
- **Structured event copy**: Editable title, host, date and time, venue, address, selling line, things to bring, perks, hidden-question notes, and next step.
- **Six starting design styles**: Riso two-ink, Swiss grid, 2020 minimalist, Clip-art Deluxe, Old printer, and Zine collage.
- **Type pairings & weights**: 5 curated pairings (Bricolage Grotesque, Fraunces, Space Grotesk, Space Mono, Archivo, Syne) with adjustable title weight (300–900), body weight (300–700), title size scale (20%–160%), and body text size scale (50%–150%).
- **Curated color palettes**: 16 high-contrast classic palettes + procedural harmonic color generation, with manual color pickers for paper and inks.
- **Tactile textures**: Grain, halftone dots, coarse fiber, vintage paper, subtle grid, or clean ink.

### Precision Placement & Spacing
- **Direct canvas manipulation**: Click and drag title, info, copy, or photo right on the flyer preview with touch support for phones.
- **Visual element selection**: Interactive bounding box indicators with corner grips and badge. Click empty flyer space, the stage background, toggle a tab, or press `Escape` to unselect.
- **Granular sliders**: Dedicated X and Y coordinate sliders with quick-zero resets.
- **Tilt & angle control**: Tilt any element from -20° to +20° to give layouts hand-pasted character.
- **D-Pad nudging**: Step buttons (↑, ↓, ←, →) with 4px fine and 16px coarse increments.
- **Alignment controls**: Quick Left, Center, or Right alignment per element or across the flyer.
- **Vertical rhythm**: Block gap multiplier (0.2x–2.0x) and a 1-click **Auto-Fit & Space** tool to naturally distribute content.

### Controlled Randomness
- **4-way shuffle grid**:
  - **Layout**: Cycle composition structures and text anchor placements.
  - **Texture**: Roll texture overlays.
  - **Scatter & Tilt**: Randomize element angles and scatter for copy and photo only, keeping background decor intact.
  - **Background Decor**: Randomize procedural background ornaments (riso ink circles, zine tape and squiggles, clip-art starbursts) without disturbing text layout or photo positions.
- **Per-control dice**: Quick randomizers for color palette, font pairing, and example copy.

### Photos & Imagery
- **Photo uploads**: Add, reposition, scale (30%–180%), and tilt photos directly on the flyer.
- **Style-aware blend modes**: Switch between translucent **Riso Ink Blend** (multiply pass overlapping background inks) and solid **Opaque Cutout** when working in the Riso style.

### Formats, Safety & Export
- **Canvas sizes**: Poster (4:5), Square (1:1), Story (9:16), and Letter (Print), with an optional Story safe-zone guide.
- **Readability guard & copy lint**: Live WCAG contrast checks and canvas overflow alerts that guide without blocking.
- **Undo, redo & autosave**: Full history with `Cmd/Ctrl+Z` shortcuts and automatic local storage persistence.
- **High-resolution export**: Instant PNG export at web sizes (1080px, 1600px) and print-ready 300 DPI (2550px).
- **Recipe files**: Save complete flyer recipes (`.json`) to recreate a design exactly, or load "look only" to apply a saved visual style to new event words.
- **Theme support**: Dark and light modes with system preference auto-detection.

## Privacy

Everything runs locally in your browser. Your text, photos, and recipes stay on your device and are never transmitted to an external server. Web fonts load from Google Fonts.