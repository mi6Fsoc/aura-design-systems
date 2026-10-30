---
version: "neuform-staff-featured-2026-05-22"
name: "Platform Architecture"
description: "Platform Architecture Pricing Section is designed for comparing plans and supporting conversion decisions. Key features include plan comparison blocks and conversion-oriented actions. It is suitable for subscription pricing pages and plan comparison experiences."
colors:
  primary: "#6BA6E2"
  secondary: "#F3F4F6"
  accent: "#1E5496"
  background: "#0D151E"
  surface: "#F3F4F6"
  text-primary: "#FFFFFF"
  text-secondary: "#A1A1AA"
  border: "#A2A1AE"
typography:
  display-lg:
    fontFamily: "Inter"
    fontSize: "64px"
    fontWeight: 500
    lineHeight: "1.04"
    letterSpacing: "0"
  body-md:
    fontFamily: "Playfair Display"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: "1.6"
  label-md:
    fontFamily: "JetBrains Mono"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: "1.2"
spacing:
  base: "8px"
  gap: "16px"
  card-padding: "24px"
  section-padding: "80px"
rounded:
  card: "2px"
  control: "2px"
  pill: "9999px"
components:
  card:
    background: "Use the surface token with subtle borders and HTML-matched shadow depth"
    radius: "Match the declared card radius token"
  button:
    background: "Use primary or accent colors for the main action"
    radius: "Use the control or pill radius based on the source HTML"
---
# Platform Architecture
Source: Neuform staff featured templates. Author: Samnang Aing (@samnang). Views: 173; favorites: 11; remixes: 1.
Tags: pricing, section, animated, bento, billing, cta.
## Overview
Platform Architecture Pricing Section is designed for comparing plans and supporting conversion decisions. Key features include plan comparison blocks and conversion-oriented actions. It is suitable for subscription pricing pages and plan comparison experiences.

Our Philosophy The ecosystem was built flawed. By design. Commercial data suffers from the same foundational errors it did a decade ago. We know. We watched it happen. 01 Usage pricing is a toxic incentive Inaccurate da…
## Composition
Use the attached HTML reference as the source of truth. Preserve the visible hierarchy, first-screen composition, section rhythm, density, and interaction tone before adapting copy or content.
Key visible headings include: The ecosystem was built flawed. By design.; Usage pricing is a toxic incentive; If you can't verify it, you can't trust it; AI requires unrestricted data to function.
## Colors
Anchor the palette in primary #6BA6E2, secondary #F3F4F6, accent #1E5496, background #0D151E, surface #F3F4F6, text-primary #FFFFFF. Keep background, surface, text, and border roles distinct so generated layouts retain the same contrast pattern as the source.
## Typography
Use Inter for display moments and Playfair Display for body copy unless the HTML clearly demands a compatible fallback. Labels and technical metadata should use JetBrains Mono or an equivalent mono face.
## Layout
Keep spacing deliberate and stable. Favor the same grid direction, max-width behavior, card density, and responsive stacking seen in the HTML. Do not replace distinctive source structures with generic SaaS sections.
## Components
Authentication and CTA controls should preserve the source button hierarchy, input density, and focused conversion path.
## Motion
Preserve existing motion cues such as masked reveals, staggered entrance, hover lift, scroll-triggered transitions, and ambient movement. Keep easing smooth and restrained.
## WebGL & Effects

If the source includes canvas, WebGL, Three.js, gradients, particles, or atmospheric effects, rebuild them as supporting layers behind the content. Keep effects performant, responsive, and secondary to the interface.

## Guardrails
- Do not flatten the source into a generic card grid.
- Do not swap the color mode unless the source clearly supports it.
- Preserve the first viewport signal, focal object, and visual density.
- Keep buttons, cards, and badges aligned to the same radius and border language.