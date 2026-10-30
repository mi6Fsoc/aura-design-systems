---
version: "neuform-staff-featured-2026-05-22"
name: "Creator Course Mobile Screens"
description: "Creator Course Hero Section is designed for introducing a product with clear above-the-fold messaging. Key features include headline hierarchy, supporting copy, and a primary call-to-action. It is suitable for homepage hero areas and campaign landing pages."
colors:
  primary: "#FF3B8D"
  secondary: "#FFFFFF"
  accent: "#8B5CF6"
  background: "#FFFFFF"
  surface: "#767680"
  text-primary: "#111827"
  text-secondary: "#4B5563"
  border: "#767680"
typography:
  display-lg:
    fontFamily: "-apple-system"
    fontSize: "64px"
    fontWeight: 500
    lineHeight: "1.04"
    letterSpacing: "0"
  body-md:
    fontFamily: "-apple-system"
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
  card: "8px"
  control: "8px"
  pill: "9999px"
components:
  card:
    background: "Use the surface token with subtle borders and HTML-matched shadow depth"
    radius: "Match the declared card radius token"
  button:
    background: "Use primary or accent colors for the main action"
    radius: "Use the control or pill radius based on the source HTML"
---
# Creator Course Mobile Screens
Source: Neuform staff featured templates. Author: Sourasith Phomhome (@madebysourasith). Views: 36; favorites: 2; remixes: 1.
Tags: hero, section, cta, effect.
## Overview
Creator Course Hero Section is designed for introducing a product with clear above-the-fold messaging. Key features include headline hierarchy, supporting copy, and a primary call-to-action. It is suitable for homepage hero areas and campaign landing pages.

9:41 12:18 / 28:00 1x Creative Sprint A fast-paced course focused on generating, shaping, and refining ideas for creative projects, products, and content. By Daniel Reed 4.9 Lessons 14 Idea Flow 28 min 1 lesson Concept…
## Composition
Use the attached HTML reference as the source of truth. Preserve the visible hierarchy, first-screen composition, section rhythm, density, and interaction tone before adapting copy or content.
Key visible headings include: Creative Sprint; Lessons; AI for Creators; From Sketch to Vision; January 4-10.
## Colors
Anchor the palette in primary #FF3B8D, secondary #FFFFFF, accent #8B5CF6, background #FFFFFF, surface #767680, text-primary #111827. Keep background, surface, text, and border roles distinct so generated layouts retain the same contrast pattern as the source.
## Typography
Use -apple-system for display moments and -apple-system for body copy unless the HTML clearly demands a compatible fallback. Labels and technical metadata should use JetBrains Mono or an equivalent mono face.
## Layout
Keep spacing deliberate and stable. Favor the same grid direction, max-width behavior, card density, and responsive stacking seen in the HTML. Do not replace distinctive source structures with generic SaaS sections.
## Components
Authentication and CTA controls should preserve the source button hierarchy, input density, and focused conversion path.
## Motion
Use subtle reveal and hover states only where they support the source hierarchy. Avoid adding motion that changes the layout character.
## WebGL & Effects

If the source includes canvas, WebGL, Three.js, gradients, particles, or atmospheric effects, rebuild them as supporting layers behind the content. Keep effects performant, responsive, and secondary to the interface.

## Guardrails
- Do not flatten the source into a generic card grid.
- Do not swap the color mode unless the source clearly supports it.
- Preserve the first viewport signal, focal object, and visual density.
- Keep buttons, cards, and badges aligned to the same radius and border language.