---
name: letrquan GitHub Profile
description: A high-fidelity dark CLI and workspace profile showcase for Zain (@letrquan).
colors:
  bg-dark: "#0B0F19"
  panel-dark: "#0F172A"
  border-slate: "#334155"
  cyan-glow: "#38BDF8"
  emerald-green: "#10B981"
  amber-orange: "#F59E0B"
  rose-red: "#EF4444"
  text-white: "#F8FAFC"
  text-muted: "#94A3B8"
typography:
  display:
    fontFamily: "'JetBrains Mono', 'Fira Code', monospace"
    fontWeight: 700
  body:
    fontFamily: "'Inter', sans-serif"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  window: "10px"
  pill: "6px"
spacing:
  container: "1200px"
---

# Design System: letrquan GitHub Profile

## Overview

**Creative Direction: "Modern Dark CLI & Workspace"**

This GitHub profile showcases Zain's public work record as a software engineer and product builder across AI agents, browser extensions, and native Rust desktop apps.

The aesthetic uses dark developer workspace visuals: terminal windows with syntax highlighting, window control buttons, live execution status indicators, crisp code blocks, and interactive-feeling SVG architecture mockups. It completely avoids generic badge walls, dark-gradient generic heroes, and low-fidelity AI placeholder boxes.

## Color Palette

- **Background Base** (`#0B0F19` / `#111827`): Deep slate dark background with subtle grid overlay.
- **Panel Base** (`#0F172A` / `#131C2E`): Dark terminal & window canvas with 1px slate borders (`#334155`).
- **Primary Accent — Cyan** (`#38BDF8`): Code variables, active tabs, browser extension focus.
- **Secondary Accent — Emerald** (`#10B981` / `#34D399`): Online status indicators, Book CLI agent execution, success states.
- **Warm Accent — Amber** (`#F59E0B`): Desktop widget highlights, V Voice audio waveforms, warning/focus states.
- **Text & Foreground**: Crisp white (`#F8FAFC`) for primary text, muted slate (`#94A3B8`) for descriptions, and dark gray (`#64748B`) for metadata.

## Typography

- **Code & CLI Monospace**: `JetBrains Mono` / `Fira Code` for terminal headers, code blocks, status lines, and tech pills inside SVG assets.
- **Body & Headings**: GitHub default system fonts and `Inter` for clean Markdown reading flow.

## Shared Asset Signature

Every asset in `assets/` is built on the same frame so the four read as one system:

- Canvas corner radius `14px`, clipped, with a `1px #1E293B` outer stroke.
- A `3px` gradient rule across the top edge, tinted to the asset's identity accent (cyan → indigo → emerald for the header, emerald → cyan for Book, cyan → indigo for Better Picture, amber → rose for V Voice).
- A low-opacity radial accent glow anchored at the top-left for depth.
- Inner window chrome at `12px` radius: title bar, three traffic-light dots, and a status bar carrying the repository slug on the right.
- Type scale: mono `11–14.5px` for chrome, labels, and code; `Inter` `12–14px` for prose; `Inter` `42px / 800` for card titles.

## SVGs & Components

1. **`assets/header.svg`** (`1200x440`):
   - Left: a `developer.ts` code block declaring name, role, focus, stack, and principle, closed by a live prompt line.
   - Right: a `// SELECTED WORK` index — three project rows with an identity status dot, a right-aligned primary-language chip, and a one-line summary.

2. **`assets/book-card.svg`** (`1200x480`):
   - Left: project dossier — kicker, title, positioning line, three capability bullets, four stack pills.
   - Right: a terminal session showing a print-mode invocation, project instruction loading, an `explorer` subagent making a `ToolSearch` → `Grep` call, patch application, and hand-off to `validator`.

3. **`assets/better-picture-card.svg`** (`1200x480`):
   - Right: a browser window with a Document Picture-in-Picture overlay — caption bar with a `CC` chip, timeline, elapsed time, and volume control, over a dimmed source tab.

4. **`assets/v-voice-card.svg`** (`1200x480`):
   - Right: a focused document window receiving dictated text, with the floating pill widget layered on top — mic button with an animated voice-activity ring, amber level meter, and a `LISTENING · whisper.cpp · VI` status cluster.

## Do's and Don'ts

### Do:
- Keep all SVG diagrams high-fidelity, representing real project workflows and interfaces.
- Draw arrows, chevrons, and carets as `<path>` geometry. Decorative Unicode (`❯`, `↳`) does not survive font fallback when GitHub proxies the SVG and renders as stray punctuation.
- Assume `JetBrains Mono` and `Inter` are unavailable and size text against the generic `monospace` / `system-ui` fallbacks. Verify by rendering headlessly before committing.
- Maintain WCAG AA contrast for text layers and code syntax colors.
- Use clean Markdown tables and precise technology pills.

### Don't:
- Don't use generic shields.io badge walls or bright neon logos.
- Don't use low-detail placeholder SVG cards with fake terminal prompt lines (`> _`).
- Don't introduce fake metrics or commercial claims. Version numbers, latency figures, memory footprints, token rates, and test counts must be verifiable in the linked repository or they do not appear. Named models go stale — describe the provider surface instead.
- Don't tint decorative elements at random. Level meters and status dots carry the asset's single identity accent.
