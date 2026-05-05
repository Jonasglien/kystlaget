---
name: Maritime Adventure
colors:
  surface: '#f6faff'
  surface-dim: '#d4dbe3'
  surface-bright: '#f6faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#edf4fc'
  surface-container: '#e8eff7'
  surface-container-high: '#e2e9f1'
  surface-container-highest: '#dce3eb'
  on-surface: '#151c22'
  on-surface-variant: '#424656'
  inverse-surface: '#2a3137'
  inverse-on-surface: '#eaf1f9'
  outline: '#727687'
  outline-variant: '#c2c6d8'
  surface-tint: '#0054d6'
  primary: '#0050cb'
  on-primary: '#ffffff'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#b3c5ff'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#fcd400'
  on-secondary-container: '#6e5c00'
  tertiary: '#006827'
  on-tertiary: '#ffffff'
  tertiary-container: '#008434'
  on-tertiary-container: '#e6ffe2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#ffe16d'
  secondary-fixed-dim: '#e9c400'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#69ff87'
  tertiary-fixed-dim: '#3ce36a'
  on-tertiary-fixed: '#002108'
  on-tertiary-fixed-variant: '#00531e'
  background: '#f6faff'
  on-background: '#151c22'
  surface-variant: '#dce3eb'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Lexend
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 26px
  label-lg:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  button-text:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 24px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 16px
  margin: 24px
  touch-target-min: 56px
---

## Brand & Style
The brand personality of this design system is adventurous, energetic, and encouraging. It is specifically tailored for children, aiming to transform educational challenges into a maritime quest. The UI should evoke a sense of play and discovery, making users feel like captains of their own learning vessel.

The design style is a hybrid of **Tactile / Skeuomorphic** and **High-Contrast / Bold**. By using "squishy" buttons with physical depth and thick borders, the interface becomes more intuitive for small hands. High-contrast elements and heavy strokes ensure visibility in various lighting conditions, including outdoor play. Maritime motifs—such as stylized waves, anchors, and ship silhouettes—are integrated into the structural components rather than just being decorative overlays.

## Colors
The palette is rooted in a high-vibrancy "Oceanic" theme. The primary blue is saturated to maintain legibility against white backgrounds, while the sun-yellow is used exclusively for interactive accents and calls to action. 

Feedback colors (Green for "Correct/Success" and Red for "Incorrect/Error") are pushed to high-saturation levels to ensure immediate cognitive recognition. A soft, off-white neutral with a blue tint is used for background surfaces to reduce eye strain while maintaining the nautical atmosphere. High contrast ratios (minimum 4.5:1) are maintained across all functional text elements to support outdoor usability.

## Typography
This design system utilizes highly legible, rounded typefaces to accommodate young readers. **Plus Jakarta Sans** provides a friendly, geometric feel for headlines, while **Lexend**—specifically designed to improve reading proficiency—is used for all body text and instructional labels. 

Typography should always be rendered with generous leading (line height) to prevent text crowding. Headlines use heavy weights (700-800) to stand out against vibrant background patterns. All text should be rendered in a dark navy rather than pure black to keep the interface feeling soft and child-friendly.

## Layout & Spacing
The layout follows a **fluid grid** model optimized for mobile handsets. A generous 24px margin ensures that interactive elements are kept away from the screen edges, preventing accidental exits or system gestures.

The spacing rhythm is based on an 8px base unit. For a child-friendly experience, "Negative Space" is prioritized to reduce cognitive load. Gutters are kept wide (16px) to clearly separate different choices in quiz-style layouts. All interactive elements must adhere to a minimum touch target of 56px to accommodate the lower precision of smaller fingers.

## Elevation & Depth
Depth in this design system is achieved through **Tactile layering** rather than traditional ambient shadows. Interactive elements feature a "thick base" effect (a darker shade of the element's color positioned 4-8px below it), creating a 3D button appearance that looks physically pressable.

When a button is pressed, it should "sink" by translating downward along the Y-axis, hiding the base and simulating physical feedback. Non-interactive cards use low-contrast outlines or "waves" at the bottom edge to indicate they are part of the background scenery rather than active buttons. Backdrops may use a subtle paper-texture overlay to add a tactile, physical-game feel.

## Shapes
The shape language is dominated by **Pill-shaped** and extremely rounded forms. There are no sharp corners in this design system; every container, button, and input field uses a minimum radius of 1rem (16px), often graduating to full pill-shapes (3rem) for primary actions.

Maritime shapes are integrated into the UI geometry: 
- **The Wave:** Section dividers use a repeating sine-wave path.
- **The Porthole:** Image containers and profile avatars are always circular.
- **The Sail:** Bottom sheets and modals use asymmetrical rounding on top corners to mimic a sail caught in the wind.

## Components
- **Action Buttons:** Large, high-contrast buttons with a 3D "bottom lip." They use the primary or secondary palette and feature a slight bounce animation on tap.
- **Choice Cards:** Used for quiz answers. Each card features a unique maritime silhouette (anchor, wheel, shell) in the corner to aid non-readers through shape association.
- **The Progress Buoy:** A custom progress bar where a small boat icon "sails" across a wavy line as the user completes tasks.
- **Feedback Overlays:** Full-screen translucent color washes (Green for success, Red for failure) with large animated emojis.
- **Navigation Toggles:** Shaped like toggle switches but styled as "flipping" nautical signal flags.
- **Input Fields:** Oversized text inputs with a thick 3px stroke to ensure they are easily identifiable as editable areas.
- **Score Badges:** Circular containers styled like golden doubloons, featuring high-gloss reflections to signify value.