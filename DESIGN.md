# Institutional Slate Design System

### 1. Overview & Creative North Star
**Creative North Star: The Sovereign Architect**
Institutional Slate is a design system built for high-stakes strategic environments. It rejects the playful, rounded aesthetics of consumer tech in favor of "Architectural Authority." The system is characterized by sharp corners (0px radius), deep monochromatic depths, and a layout that favors asymmetrical editorial pacing over rigid grid-block repetition. It bridges the gap between traditional corporate "Navy" and the cutting-edge transparency of digital asset strategy.

### 2. Colors
The palette is rooted in a deep "Midnight Navy" (#00081e) that provides a sense of gravity and stability.

*   **The "No-Line" Rule:** Sectioning is achieved through color-blocking and tonal shifts (e.g., moving from `surface` to `surface_container_low`). 1px solid borders are strictly forbidden for layout containers, except when used as a vertical accent "rule" to emphasize professional hierarchy.
*   **Surface Hierarchy:** 
    *   `surface` (#faf9ff): The default canvas for high-readability body text.
    *   `surface_container_low`: Used for large-scale section transitions.
    *   `surface_container_highest`: Used for secondary information cards.
*   **The "Glass & Gradient" Rule:** Navigation and floating headers must use `glass-header` (80% opacity with 20px backdrop blur) to maintain a sense of space and modern transparency.
*   **Signature Textures:** Hero sections utilize the "Navy Gradient" (#00081e to #0a1f44) with soft, organic glow orbs in the background to prevent a flat, dated corporate feel.

### 3. Typography
Typography is the primary driver of the system's "High-End Editorial" personality.

*   **Display/Headline:** *Space Grotesk*. A high-contrast, technical sans-serif that feels both industrial and modern.
*   **Body/Label:** *Inter*. A neutral, highly legible face for dense strategic content.
*   **The Scale (Ground Truth):**
    *   **Hero Headers:** 4.5rem (72px) or 3rem (48px) with `tracking-tighter`.
    *   **Section Headers:** 2.25rem (36px) or 1.875rem (30px).
    *   **Body Text:** 1.125rem (18px) for primary insights; 0.875rem (14px) for secondary metadata.
    *   **Micro-Labels:** 0.75rem (12px) with 0.2em letter spacing for an "archival" look.

### 4. Elevation & Depth
Elevation is expressed through layering and opacity rather than physical height (shadows).

*   **The Layering Principle:** Use the `surface-container` tiers to "stack" content. A `surface_container_lowest` card on a `surface_container_low` background creates depth through pure value contrast.
*   **Ambient Shadows:** While the system uses a `shadow-sm` for floating headers, shadows on cards should be avoided in favor of high-contrast background shifts.
*   **Structural Accents:** 2px solid vertical lines in `secondary` or `primary` colors are used to "anchor" text blocks, providing a visual cue of importance without boxing content in.

### 5. Components
*   **Buttons:** Sharp-edged (0px radius). Primary buttons use `secondary_container` with bold typography. Hover states should use a subtle `scale-95` or `opacity` shift.
*   **Cards:** Bento-style grid implementation. Use varying spans (e.g., 8-column vs 4-column) to create a rhythmic, non-linear reading path.
*   **Input Fields:** Underlined or minimally bordered with `outline_variant`. Focus states should use `primary`.
*   **Timelines:** Use the "Professional Trajectory" pattern—a single vertical `outline_variant` line with solid color nodes to denote milestones.

### 6. Do's and Don'ts
*   **Do:** Use extreme white space (Spacing 3) to allow complex ideas "room to breathe."
*   **Do:** Use `uppercase` and high letter-spacing for labels to evoke a sense of premium branding.
*   **Don't:** Use rounded corners. This system relies on the precision of 90-degree angles.
*   **Don't:** Use drop shadows on interactive elements; rely on tonal changes and scale transformations instead.
*   **Don't:** Mix the headline and body fonts. *Space Grotesk* is for impact; *Inter* is for information.