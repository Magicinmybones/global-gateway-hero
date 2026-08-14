# Asset Guide

## 1. Reference Summary

The reference is a full-viewport SaaS landing-page hero for a real-time multilingual communication product. Its visual focus is a bright rectangular gateway in a cinematic alien valley at twilight. Centered navigation, oversized two-line display type, supporting copy, and a small contact-sales button are layered over the scene.

## 2. Available Assets

### alien-portal-landscape.webp

Path:
`assets/backgrounds/alien-portal-landscape.webp`

Purpose:
The complete cinematic hero background: a navy and violet twilight sky, coral horizon glow, distant mountain range, rocky moss-covered terrain, reflective water, and the luminous central portal.

Where it appears:
Use it as the full-bleed background of the hero section, behind all navigation and hero copy.

Background:
Opaque RGB image; no transparency. The terrain, atmospheric lighting, reflections, and portal are intentionally combined because they share one perspective and lighting system.

Recommended usage:
Render it with an `<img>` element or CSS background using `object-fit: cover` / `background-size: cover`. Keep the horizontal center anchored so the portal remains centered. A subtle code-built dark overlay may be added at the top to preserve navigation contrast, but do not attempt to reconstruct the terrain or portal separately.

Resolution:
1536 × 1024 pixels.

## 3. Elements Claude Should Recreate

The following should **not** be image assets. Recreate them with HTML, CSS, or simple SVG:

- all navigation labels and spacing
- the small radial sunburst/logo mark at the top center
- the two-line hero headline and its contrasting white/muted-lavender colors
- supporting paragraph copy
- the white contact-sales button
- the small corner-bracket details around the button
- responsive layout, alignment, and typography
- any subtle top vignette or contrast overlay
- all hover states, interactions, and animation

The reference screenshot itself should be used as the source of truth for proportions, type scale, spacing, and overlay placement. The prepared background intentionally contains no interface text, logo, button, or watermark.
