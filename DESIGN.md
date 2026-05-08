---
name: Crystal Ruin Aesthetic
colors:
  surface: '#111317'
  surface-dim: '#111317'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e7'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e2e2e7'
  inverse-on-surface: '#2e3034'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#ffabf3'
  on-secondary: '#5b005b'
  secondary-container: '#fe00fe'
  on-secondary-container: '#500050'
  tertiary: '#fff5de'
  on-tertiary: '#3a3000'
  tertiary-container: '#ffd700'
  on-tertiary-container: '#705d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#ffd7f5'
  secondary-fixed-dim: '#ffabf3'
  on-secondary-fixed: '#380038'
  on-secondary-fixed-variant: '#810081'
  tertiary-fixed: '#ffe16d'
  tertiary-fixed-dim: '#e9c400'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#544600'
  background: '#111317'
  on-background: '#e2e2e7'
  surface-variant: '#333539'
typography:
  headline-xl:
    fontFamily: Epilogue
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 32px
  gutter: 16px
  card-padding: 24px
---

## Brand & Style

The design system for 'Battle of the Tribes' is built upon a **Tactile / Skeuomorphic** foundation infused with **High-Contrast** magical elements. It aims to evoke a sense of "magical discovery"—the feeling of finding ancient, weathered technology powered by raw crystal energy. The target audience is mid-core to hardcore gamers who appreciate high-fidelity environmental storytelling within their interface.

The UI should feel heavy, permanent, and grounded in the physical world of the game. Surfaces are inspired by the mossy, weathered stone of the ruins, while interactive elements are supercharged with the vibrant, glowing energy found in the deep crystal caverns. The emotional response is one of epic adventure, mystery, and tactical importance.

## Colors

The palette is a high-contrast battle between environmental "foundation" colors and magical "interactive" colors.

*   **Foundation:** Deep cavern purples and blues (`#0F0B1E`) serve as the primary background layer. Lush forest greens (`#2D4B28`) and weathered stone greys provide secondary surfaces, creating a naturalistic but dark base.
*   **Magic (Interactions):** Glowing Cyan (`#00F0FF`) represents player energy and positive actions. Magenta (`#FF00FF`) is used for rare items and high-intensity magic. Gold (`#FFD700`) is reserved for legendary achievements and critical UI framing.
*   **Contrast:** The default mode is **Dark**, ensuring that glowing crystal accents pop with maximum luminosity against the dim, atmospheric backgrounds.

## Typography

This design system uses a hierarchical blend of characterful display type and high-utility body text.

*   **Headings:** Use **Epilogue** in bold/heavy weights. It provides a geometric yet slightly industrial feel that, when paired with weathered textures, simulates the "bold fantasy" look required. Headlines should use tight letter spacing to feel impactful and monolithic.
*   **Body:** **Be Vietnam Pro** provides a warm, contemporary, and highly readable experience for long-form lore and item descriptions. It balances the "heavy" nature of the headings.
*   **System/Data:** **Space Grotesk** is used for technical data, numbers, and labels, leaning into the "ancient technology" aspect of the crystal ruins.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for primary menus (centered containers) and a **Fluid Grid** for in-game HUD elements. 

*   **Rhythm:** An 8px base unit governs all spacing.
*   **Composition:** Screens should feel "framed." Use ornate, stone-textured borders to constrain the content. Content density is medium-high; the UI should feel rich and filled, much like a treasure-laden cavern, rather than empty and minimalist.
*   **Margins:** Large outer safe areas (32px+) ensure that the UI doesn't interfere with the immersive background artwork.

## Elevation & Depth

Hierarchy is established through **Physical Layering** and **Luminance**:

1.  **Level 0 (Background):** Immersive environmental art (caverns/forests) with a heavy dark vignette.
2.  **Level 1 (Containers):** Stone-textured cards and panels. These do not use soft shadows; instead, they use thick, chiseled bevels and "inner glow" effects to suggest they are carved into the screen.
3.  **Level 2 (Interactive):** Buttons and active icons. These utilize **Outer Glows** in Cyan or Magenta to appear as if they are emitting light. 
4.  **Level 3 (Overlays):** Modals use a heavy backdrop blur (Glassmorphism) tinted with the deep cavern purple, surrounded by a gold ornate frame.

## Shapes

The shape language is **Soft (0.25rem)**, mimicking the natural wear on ancient stone. 

*   **Corners:** Avoid perfect circles or sharp 90-degree angles. A slight radius on all stone elements suggests erosion over time.
*   **Profiles:** Use "Chiseled" edges—45-degree inner bevels on containers to give them a 3D, carved appearance.
*   **Crystals:** Interactive icons and decorative elements should use jagged, hexagonal, or diamond-shaped silhouettes to reinforce the crystal theme.

## Components

*   **Stone-Textured Cards:** Primary containers for units and items. Use a dark grey stone texture with a subtle moss-green gradient at the bottom. Borders are "carved" into the surface.
*   **Glowing Buttons:** High-contrast buttons with a solid color base (Cyan for Primary, Magenta for Secondary). They must feature a pulsating outer glow and a "inner spark" highlight on the top edge.
*   **Ornate Borders:** Use gold or stone-grey filigree to frame the entire screen and major modals. Incorporate crystal nodes at the corners of these frames.
*   **Input Fields:** Recessed "trenches" in the stone UI, with the active state indicated by a cyan line flowing through the bottom of the field like a power conduit.
*   **Health/Resource Bars:** Skeuomorphic "vials" or stone troughs filled with glowing liquids, utilizing a "bubbling" particle effect for added magic feel.
*   **Chips/Tags:** Small crystal shards with text overlaid. The color of the shard (Cyan, Purple, Green) denotes the tribe or element.