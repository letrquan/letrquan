---
version: 1
slug: "readme-md"
primary_target: "README.md"
related_targets: ["assets/header.svg","assets/book-card.svg","assets/better-picture-card.svg","assets/v-voice-card.svg"]
---

# GitHub profile README

## Scope and mode

`README.md` is an **Experience** surface: a public work record that lets hiring teams, product evaluators, and potential collaborators enter through real shipped work.

## Audience, job, and action

Visitors need to understand the maker's range, scan selected work, and open the relevant repository. The primary action is following a project link or opening the full repository list.

## Evidence and constraints

Use only verified project descriptions and repository links from `PRODUCT.md` and `README.md`. Preserve GitHub-flavored Markdown compatibility, semantic alternatives for every SVG, and the WCAG 2.2 AA commitment. Do not fabricate adoption, customers, benchmarks, or product capabilities.

## Chosen direction and memorable moment

**Product Test Dossier.** The page opens on a cobalt printed title sheet: Zain's name fills the first image while a field-note rail frames the profile as a public record. The project list works as a measured release index rather than a promo card grid. Cobalt ink, warm paper, safety-orange registration marks, hard rules, folio numbers, and legible diagrams replace neon gradients, floating cards, badge walls, and cyberpunk terminal theater.

## Approved composition

**Title sheet + release index.** Selected by delegated decision: it gives hiring teams an immediate identity read, keeps the three releases easy to scan, and retains enough factual detail for product evaluators and collaborators. The approved composition is implemented directly in `README.md` and `assets/*.svg`; temporary comparison studies were intentionally removed after selection.

## Inventory

| Ingredient | Medium | Commitment |
| --- | --- | --- |
| Title sheet / header | Authored SVG | Cobalt field, large compressed name, paper-white technical type, orange registration mark, hard rule geometry |
| Project releases | Authored SVG | One full-width card per factual project with a recognizable technical diagram and project-specific evidence |
| Body copy and links | GitHub-flavored Markdown / HTML | Semantic text and ordinary links remain selectable and accessible |
| Navigation / index | GitHub-flavored Markdown / HTML | Plain text links, never badges or fake controls |
| Responsive behavior | SVG viewBox + Markdown's native reflow | SVG art keeps internal reading order; text layers below images stay useful at all widths |

## Unresolved decisions

None. Image generation was attempted but not available because the configured local fallback key was invalid; all required visual material is authored as scalable SVG.
