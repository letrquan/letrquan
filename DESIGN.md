---
name: letrquan GitHub Profile
description: A public product-test dossier for an independent software maker.
colors:
  cobalt-ink: "#173B82"
  paper-stock: "#F3F1E8"
  registration-orange: "#F15A24"
  black-ink: "#121212"
typography:
  display:
    fontFamily: "custom SVG letterforms"
    fontWeight: 900
    lineHeight: 0.72
    letterSpacing: "-0.07em"
  body:
    fontFamily: "GitHub system text"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "GitHub system text"
    fontSize: "13px"
    fontWeight: 700
    letterSpacing: "0.12em"
rounded:
  none: "0"
spacing:
  rule-inset: "42px"
  asset-inset: "72px"
components:
  release-link:
    textColor: "{colors.cobalt-ink}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
---

# Design System: letrquan GitHub Profile

## Overview

**Creative North Star: "The Product Test Dossier"**

This is a public work record for an independent software maker. It treats each release as evidence: a named, numbered document with a concise factual description and a direct route to the repository. The visual language belongs to technical publishing rather than a generic developer portfolio—ink, paper, registration marks, rules, and diagrams do the identifying work.

The profile must work inside GitHub's fixed README renderer. Markdown remains selectable, legible, and host-native; authored SVG carries the strong identity moments. The page should feel composed without pretending to be a standalone web app.

**Key Characteristics:**
- Saturated cobalt title sheets against warm off-white fields.
- Safety orange used as a registration signal, not ambient decoration.
- Full-width project dossiers with hard rules and one concise technical diagram each.
- Direct repository links and factual copy in ordinary GitHub reading flow.

## Colors

The palette is printed matter translated into scalable SVG: one dominant ink, one stock, one signal, and one rule color.

### Primary
- **Cobalt Ink** (`cobalt-ink`): Owns the profile header and the primary geometry inside project diagrams.

### Secondary
- **Registration Orange** (`registration-orange`): Marks active points, labels, and small registration squares. It never becomes a background wash.

### Neutral
- **Paper Stock** (`paper-stock`): The off-white field inside every authored project dossier.
- **Black Ink** (`black-ink`): Rules and text inside dossier assets. Outside SVG, GitHub's host colors remain authoritative.

### Named Rules
**The One-Signal Rule.** Orange is a measurement mark: reserve it for a small, high-information portion of an asset.

**The Flat Ink Rule.** Use flat fills and exact rules; gradients, glow, glass, and faux depth do not belong in this system.

## Typography

**Display Font:** Custom outlined SVG letterforms for the header wordmark.

**Body Font:** GitHub system text for all rendered Markdown.

**Label/Mono Font:** GitHub system text set at a compact, bold, tracked scale inside SVG labels.

**Character:** The header uses compressed, heavyweight letterforms as a single printed title. Project names are large, direct, and sans-serif within their dossier assets; ordinary reading copy stays in GitHub's accessible host typography.

### Hierarchy
- **Display** (900, asset-scaled, 0.72 line-height): The custom ZAIN wordmark appears only in the title sheet.
- **Headline** (900, 79–112px in authored SVG): Names each release.
- **Title** (GitHub heading level 3): Labels the Markdown record that precedes each project asset.
- **Body** (GitHub default, 1.5 line-height): Carries factual project descriptions and working notes.
- **Label** (700, 13px, 0.12em tracking): Carries issue, release, and record metadata inside SVG only.

### Named Rules
**The Evidence-First Type Rule.** Display lettering establishes the record once; after that, the reader gets plain language, not ornamental type.

## Layout

The README begins with one full-width title-sheet SVG, then a direct statement and a single repository action. Each selected release follows the same reading order: numbered Markdown heading, full-width dossier asset, factual description, tool line, and direct repository link. Horizontal rules create separations between records rather than wrapping them in cards.

Inside SVG assets, a 42px frame inset, upper and lower rules, and an approximate 72px text inset establish the repeatable dossier grid. The `viewBox` preserves diagrams at any rendered width, while GitHub's Markdown reflows body content naturally on narrow screens.

## Elevation & Depth

There is no shadow vocabulary. Depth comes from hierarchy, hard rules, nested diagram geometry, and the contrast between cobalt ink and paper stock—not from floating surfaces or simulated material effects.

## Shapes

Corners are square (`0`). A dossier is bounded by a precise frame and horizontal rules, not rounded containers. Circles, crosshairs, terminals, and framed rectangles appear only as functional technical diagram geometry.

## Components

### Release Records
- **Character:** A project is a release record, never a marketing card.
- **Shape:** Square, full-width SVG framed by 1–3px rules in its own coordinate system.
- **Color:** Paper stock base; cobalt establishes the technical diagram; orange marks a single active feature.
- **Content:** Numbered Markdown heading, accessible SVG alternative text, factual description, concise technology line, and an ordinary repository link.

### Repository Links
- **Character:** Direct and host-native.
- **Style:** Plain GitHub-rendered links; no badge, button, pill, or fake control treatment.
- **Focus / Hover:** GitHub supplies interaction and keyboard-focus behavior.

### Title Sheet
- **Character:** A printed masthead for a public work record.
- **Shape:** Full-width cobalt SVG bounded by thin paper rules and a crosshair-like registration graphic.
- **Content:** Custom ZAIN lettering, factual role, work domains, issue label, and accessible description.

## Do's and Don'ts

### Do:
- **Do** make each asset explain a real release through a distinct, countable technical diagram.
- **Do** retain ordinary Markdown descriptions and links below images so identity never replaces readable evidence.
- **Do** keep the four-color ink-and-stock palette intact in authored profile assets.
- **Do** use generous whitespace and hard rules to pace a scan through projects.

### Don't:
- **Don't** use dark-gradient heroes, neon glow, cyberpunk terminal theater, glass, or generic SaaS panel stacks.
- **Don't** turn tools into a badge wall; describe the actual work first.
- **Don't** add rounded cards, soft shadows, or pill-shaped controls to dossier assets.
- **Don't** introduce commercial claims, testimonials, metrics, or product capabilities not evidenced by the linked repositories.
- **Don't** retain exploratory mock pages after their composition decision has been implemented; the README and committed SVG assets are the sole source of visual truth.
