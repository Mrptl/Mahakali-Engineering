---
name: Industrial Precision System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e2bfb4'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#a98a80'
  outline-variant: '#5a4139'
  surface-tint: '#ffb59e'
  primary: '#ffb59e'
  on-primary: '#5d1800'
  primary-container: '#f75f28'
  on-primary-container: '#521400'
  inverse-primary: '#ad3300'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c2c7cf'
  on-tertiary: '#2c3138'
  tertiary-container: '#8c9199'
  on-tertiary-container: '#252a31'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59e'
  on-primary-fixed: '#3a0b00'
  on-primary-fixed-variant: '#842500'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#dee3eb'
  tertiary-fixed-dim: '#c2c7cf'
  on-tertiary-fixed: '#171c22'
  on-tertiary-fixed-variant: '#42474e'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-xl:
    fontFamily: Manrope
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Manrope
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  title-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  mono-label:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 128px
  component-gap: 24px
---

## Brand & Style

This design system is engineered for the heavy-industry and enterprise manufacturing sector, prioritizing a sense of scale, reliability, and technical sophistication. The aesthetic is **Cinematic Minimalism**—a blend of high-end editorial layouts and engineering precision. 

The brand personality is authoritative and stoic, evoking the feeling of a world-class manufacturing floor. It utilizes a "Dark Mode" foundational layer to create a premium, high-contrast environment where "Industrial Orange" acts as a functional beacon for action and status. The interface relies on cinematic photography of industrial machinery, treated with subtle desaturation and dark overlays to ensure UI elements remain legible while maintaining a sense of immense physical power and engineering excellence.

## Colors

The palette is rooted in industrial materials: charcoal, steel, and graphite. 

- **Charcoal Black (#1A1A1A):** The primary canvas. Used for deep backgrounds to create a cinematic, high-end feel.
- **Graphite (#2B2B2B):** Used for secondary containers and surface differentiation.
- **Steel Gray (#3A3F46):** Employed for borders, subtle dividers, and inactive states, mimicking the appearance of brushed metal.
- **Industrial Orange (#F15A24):** The high-visibility accent. This is reserved strictly for primary calls to action, critical status indicators, and active navigational highlights.
- **White & Light Gray:** Used predominantly for typography and high-contrast UI components (like secondary buttons) to ensure peak readability against dark backgrounds.

## Typography

The typography system uses a pairing of **Manrope** for expressive, geometric headlines and **Inter** for utilitarian, highly legible body and UI text.

- **Display & Headlines:** Set in Manrope with tight letter-spacing and bold weights to mimic the impact of architectural signage. Large-scale headings should be used to anchor sections on full-width photography.
- **Body Text:** Set in Inter for its neutral, technical character. Line heights are generous (1.5x+) to provide breathing room in dense data environments.
- **Data & Labels:** Small caps and medium weights are used for technical specifications and metadata to provide an organized, engineering-led hierarchy.

## Layout & Spacing

This design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. 

The philosophy is "Generous & Structural." Large-scale industrial photography often spans the full width of the viewport, while content is constrained to a central container with significant lateral margins (64px). Vertical spacing (section-gap) is intentionally large (128px) to reinforce the premium, "unrushed" feel of luxury enterprise software. 

Elements are aligned to a strict 8px baseline grid to ensure mathematical precision in all component relationships.

## Elevation & Depth

Hierarchy is established through transparency and tonal layering rather than traditional drop shadows.

- **Glassmorphism Navigation:** Primary navigation bars use a background blur (20px) with a semi-transparent dark fill (40% opacity) and a subtle 1px top border in Steel Gray.
- **Tonal Layering:** Surfaces are stacked using color—Darkest (#1A1A1A) for the base, slightly lighter Graphite (#2B2B2B) for elevated cards or panels.
- **Technical Insets:** Instead of shadows, use subtle 1px "inner" borders (Steel Gray) to give elements an etched, manufactured appearance.
- **Overlays:** Dark linear gradients (0% to 60% opacity) are applied over full-width imagery to ensure white typography remains punchy and compliant with accessibility standards.

## Shapes

The shape language is disciplined and professional. 

- **Primary Corners:** A "Soft" setting (4px/0.25rem) is used for buttons and input fields to provide a modern touch without appearing "bubbly" or consumer-oriented.
- **Container Corners:** Larger cards or sections may use 8px (0.5rem) to differentiate them from smaller interactive elements.
- **Industrial Accents:** Decorative elements (like the status dot in the reference) remain perfectly circular to contrast against the otherwise rectilinear grid.

## Components

### Buttons
- **Primary:** Industrial Orange background with White text. Bold weight. No shadow. 4px radius.
- **Secondary:** Transparent with a 1px White or Steel Gray border. White text.
- **Ghost/Glass:** Used in navigation; transparent with background-blur and White text.

### Input Fields
- Dark background (#2B2B2B) with a subtle bottom border or 1px Steel Gray outline. 
- Focus state uses an Industrial Orange 1px border.

### Cards
- Graphite (#2B2B2B) background with high-contrast White headings. 
- Use large imagery within cards when possible, maintaining the cinematic aesthetic.

### Status Indicators
- Small circular dots using a traffic-light system: Orange (Primary/Warning), Green (Operational), Red (Critical).

### Navigation
- Top-mounted, full-width glassmorphic bar.
- Direct, bold labels in Manrope.
- Right-aligned "Contact" or "Portal" button in Industrial Orange to provide a persistent anchor point.