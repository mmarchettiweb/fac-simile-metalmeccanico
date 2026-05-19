# Industrial Precision System (Padova B2B Metalworking Website)

## Colors

The palette is derived from raw and processed materials found in a precision machine shop.

- **Primary (Steel Blue):** Used for structural elements, headers, and core navigation to establish authority and trust.
- **Secondary (Slate Grey):** Employed for technical text, icons, and secondary actions, providing a grounded, metallic feel.
- **Safety Orange (CTA):** Reserved exclusively for primary actions, alerts, and critical touchpoints, mimicking the high-visibility markers used in factory environments.
- **Cool Silver (Neutral):** Acts as the background canvas and divider color, creating a clean, sterile environment that highlights the blue and grey tones.

| Role | Token | Hex |
| --- | --- | --- |
| Primary | `primary` | `#0a2344` |
| Primary Container | `primary-container` | `#23395b` |
| On Primary | `on-primary` | `#ffffff` |
| On Primary Container | `on-primary-container` | `#8da3cb` |
| Inverse Primary | `inverse-primary` | `#b1c7f1` |
| Secondary | `secondary` | `#5b5f62` |
| Secondary Container | `secondary-container` | `#dde0e3` |
| On Secondary | `on-secondary` | `#ffffff` |
| On Secondary Container | `on-secondary-container` | `#5f6366` |
| Tertiary | `tertiary` | `#431300` |
| Tertiary Container | `tertiary-container` | `#672200` |
| On Tertiary | `on-tertiary` | `#ffffff` |
| On Tertiary Container | `on-tertiary-container` | `#ff7c43` |
| Background | `background` | `#f6f9ff` |
| On Background | `on-background` | `#161c22` |
| Surface | `surface` | `#f6f9ff` |
| Surface Dim | `surface-dim` | `#d4dbe2` |
| Surface Bright | `surface-bright` | `#f6f9ff` |
| Surface Container Lowest | `surface-container-lowest` | `#ffffff` |
| Surface Container Low | `surface-container-low` | `#eef4fc` |
| Surface Container | `surface-container` | `#e8eef6` |
| Surface Container High | `surface-container-high` | `#e3e9f1` |
| Surface Container Highest | `surface-container-highest` | `#dde3eb` |
| On Surface | `on-surface` | `#161c22` |
| On Surface Variant | `on-surface-variant` | `#44474e` |
| Inverse Surface | `inverse-surface` | `#2b3137` |
| Inverse On Surface | `inverse-on-surface` | `#ebf1f9` |
| Outline | `outline` | `#74777f` |
| Outline Variant | `outline-variant` | `#c4c6cf` |
| Surface Tint | `surface-tint` | `#4a5f83` |
| Error | `error` | `#ba1a1a` |
| On Error | `on-error` | `#ffffff` |
| Error Container | `error-container` | `#ffdad6` |
| On Error Container | `on-error-container` | `#93000a` |

## Typography

Typography reflects systematic clarity. We use **IBM Plex Sans** for headings to leverage its engineered, corporate-industrial heritage. **Inter** is utilized for body copy due to its exceptional readability in data-dense layouts. A tertiary monospaced font, **JetBrains Mono**, is introduced for labels, technical specifications, and part numbers to reinforce the "technical documentation" aesthetic. All caps should be used sparingly for labels to denote importance and mimic industrial labeling.

| Role | Font Family | Size | Weight | Line Height | Letter Spacing |
| --- | --- | --- | --- | --- | --- |
| `headline-xl` | IBM Plex Sans | 48px | 700 | 56px | -0.02em |
| `headline-lg` | IBM Plex Sans | 32px | 600 | 40px | -0.01em |
| `headline-md` | IBM Plex Sans | 24px | 600 | 32px | normal |
| `body-lg` | Inter | 18px | 400 | 28px | normal |
| `body-md` | Inter | 16px | 400 | 24px | normal |
| `label-sm` | JetBrains Mono | 12px | 500 | 16px | 0.05em |
| `headline-lg-mobile` | IBM Plex Sans | 28px | 600 | 36px | normal |

## Spacing

- **unit**: 4px
- **margin-mobile**: 16px
- **gutter**: 24px
- **margin-desktop**: 64px
- **max-width**: 1440px

## Layout

This design system utilizes a **Fixed Grid** model based on an 8px technical rhythm. The desktop layout is centered on a 12-column grid with 24px gutters, ensuring that content feels structured and balanced.

On mobile, the layout collapses to a 4-column grid with 16px margins. Spacing between elements should be "tight" but intentional, emphasizing high data density without feeling cluttered. Use hairline dividers (1px) in Slate Grey to separate sections, echoing the precision of a technical drawing.

## Elevation & Depth

In line with the "High-Precision" theme, this design system eschews soft, ambient shadows in favor of **Low-Contrast Outlines** and **Tonal Layering**.

Depth is conveyed through:
1. **Stroke Hierarchy:** Using 1px or 2px solid borders to define containers.
2. **Surface Tiers:** Shifting background colors slightly between Cool Silver and white to denote hierarchy.
3. **Inset States:** Buttons and inputs use inner shadows or darker borders when pressed to simulate mechanical depression.
4. **Grid Overlays:** Subtle, non-intrusive 24px grid lines may be used in the background of hero sections to create a "drafting table" depth.

## Shapes

The shape language is strictly **Sharp (0)**. There are no rounded corners in this design system. Every button, input field, card, and modal features 90-degree angles to represent the hardness and precision of machined metal.

Angled "clipped corners" (45-degree chamfers) may be used as a stylistic accent on primary decorative elements or container tags to mimic industrial CNC chamfering.

## Components

### Button
- **Structure**: Text label (`body-md` or `label-sm`), 90-degree angles.
- **States**: 
  - **Default**: Primary button has a metallic gradient (subtle brushed aluminum) or solid Primary/Tertiary color.
  - **Hover**: Smooth hover transitions, possibly intensifying the border or background.
  - **Active/Pressed**: Inset state using inner shadow or darker borders simulating mechanical depression.
- **Spacing**: Uses baseline 8px rhythm.

### Input / Form Fields
- **Structure**: Label (`label-sm`), text field, sharp edges.
- **States**: 
  - **Default**: 90-degree angles, 1px or 2px solid border (Outline).
  - **Active/Pressed**: Inner shadow or darker Outline variant.

### Card
- **Structure**: Container for text/imagery/actions.
- **Styling**: Sharp 90-degree corners. 1px or 2px solid borders (`outline` or `outline-variant`). Background color tiering between Cool Silver (`surface-dim`) and white (`surface-container-lowest`).

### Divider
- **Structure**: 1px hairline divider.
- **Color**: Slate Grey (`outline-variant`), to separate sections like a technical drawing.

### Hero Area
- **Styling**: Can use subtle metallic gradients simulating brushed aluminum. May include subtle, non-intrusive 24px grid lines in the background to create a "drafting table" depth.

## Motion & Interaction
- Smooth scroll
- Hover transitions on buttons and cards. Hover state on buttons should feel "mechanical" (sharp transitions, inset simulating depression).
