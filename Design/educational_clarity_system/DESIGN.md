---
name: Educational Clarity System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#424754'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#727785'
  outline-variant: '#c2c6d6'
  surface-tint: '#005ac2'
  primary: '#0058be'
  on-primary: '#ffffff'
  primary-container: '#2170e4'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#825100'
  on-tertiary: '#ffffff'
  tertiary-container: '#a36700'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-xxl: 3rem
  gutter: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 5rem
  max-width-content: 1200px
---

## Brand & Style

This design system is built on the principles of **Modern Corporate** aesthetics, specifically tailored for the educational sector. The personality is "The Encouraging Mentor"—professional and reliable, yet approachable and clear. It prioritizes cognitive ease, ensuring that the learner's focus remains entirely on the content without visual distraction.

The style utilizes a "Soft Minimalist" approach. By combining ample whitespace, a crisp blue-centric palette, and gentle depth, the interface feels high-quality and premium. It avoids the coldness of pure utility in favor of an inviting, accessible atmosphere that motivates users to progress through their learning journey. Key visual drivers include purposeful contrast, logical grouping via cards, and a refined sense of order.

## Colors

The palette is anchored by a **Professional Blue (#3B82F6)**, used for primary actions, progress indicators, and branding elements to instill a sense of competence and trust. 

- **Primary:** Professional Blue for high-importance interactions.
- **Secondary (Success):** A vibrant emerald green (#10B981) to celebrate achievements and completed lessons.
- **Tertiary (Accent):** A warm amber (#F59E0B) for notifications, streaks, or "points of interest."
- **Backgrounds:** The primary surface is an ultra-soft off-white (#F9FAFB) to reduce eye strain during long reading sessions, while active content lives on pure white (#FFFFFF) cards.
- **Typography:** We use a deep slate (#1E293B) for high-contrast readability against the light background, ensuring WCAG AA compliance.

## Typography

This design system utilizes **Inter** for all text roles. Inter’s tall x-height and neutral character make it exceptionally legible for educational content, from dense instructional paragraphs to quick navigational labels.

For long-form reading, use `body-lg` to prevent fatigue. Use `headline-xl` sparingly for page-level introductions. All labels and functional text should maintain a medium or semibold weight to remain distinct from body copy. On mobile devices, the largest headings scale down to ensure they do not break layout or force excessive scrolling.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid Grid**. On desktop, content is centered within a 1200px container to ensure line lengths for text remain readable. 

- **Desktop:** 12-column grid with 24px (1.5rem) gutters.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px (1rem) margins.

We employ an 8px base unit for all spacing. Vertical rhythm is critical for educational clarity; use `space-xl` between distinct sections and `space-md` between related items within a card.

## Elevation & Depth

Visual hierarchy is established through **Ambient Shadows** and tonal layering. This creates a clear mental model of "Interactive vs. Static."

1.  **Level 0 (Floor):** The background (#F9FAFB). No shadows.
2.  **Level 1 (Cards):** Standard content cards use a subtle, diffused shadow: `0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03)`.
3.  **Level 2 (Hover/Active):** Interactive elements or focused cards lift slightly with a more pronounced shadow: `0 10px 15px -3px rgba(0, 0, 0, 0.08)`.
4.  **Level 3 (Navigation/Modals):** High-level overlays use a heavy blur to separate from the background, often accompanied by a light 1px border (#E2E8F0) for crispness.

## Shapes

The shape language is consistently **Rounded**, promoting an accessible and friendly feel. 

- **Standard Elements:** Buttons, input fields, and small UI components use a 0.5rem (8px) radius.
- **Cards & Containers:** Large content blocks use a 1rem (16px) radius to emphasize their role as distinct learning modules.
- **Interactive Indicators:** Small badges or chips use a full pill-shape (999px) to differentiate them from square-like structural cards.

## Components

- **Buttons:** Primary buttons use the Professional Blue (#3B82F6) with white text. Secondary buttons use a light blue ghost style or a subtle slate border. Padding should be generous (12px 24px) to ensure touch-friendliness.
- **Cards:** The workhorse of this design system. Every card must have a white background, the Level 1 shadow, and 16px rounded corners. Use cards to group lessons, quizzes, or resources.
- **Input Fields:** Use 8px rounded corners and a 1px border (#D1D5DB). When focused, the border should transition to the Primary Blue with a soft 3px outer glow.
- **Progress Bars:** Thin, rounded tracks (#E5E7EB) with a Primary Blue or Secondary Green fill. Include a label-sm percentage for clarity.
- **Navigation:** A clean top-bar or sidebar with high-contrast icons and text. The active state should be indicated by a vertical or horizontal blue "accent bar" rather than just a color change.
- **Chips:** Used for categories or tags. Low-saturation backgrounds with high-saturation text (e.g., light blue background with dark blue text) to keep them readable but non-distracting.