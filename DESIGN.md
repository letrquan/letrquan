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

## SVGs & Components

1. **`assets/header.svg`**:
   - Full-width dark mode developer terminal window (`1200x460`).
   - Left side: Interactive code block defining developer persona (`developer.ts`) with live cursor prompt line.
   - Right side: Shipped releases index with live status indicators (`● Book CLI`, `● Better Picture`, `● V Voice`).

2. **`assets/book-card.svg`**:
   - High-fidelity terminal UI mockup for Book CLI agent (`1200x480`).
   - Shows active terminal session: task prompt, MCP tool execution, subagent research loop, and test status.

3. **`assets/better-picture-card.svg`**:
   - Browser extension mockup for Better Picture (`1200x480`).
   - Displays floating Picture-in-Picture window with synced subtitles overlay and custom playback controls.

4. **`assets/v-voice-card.svg`**:
   - Windows desktop widget mockup for V Voice (`1200x480`).
   - Features dynamic audio waveform equalizer, hotkey badge `[Win + Alt + V]`, and Whisper latency metrics (`42ms`).

## Do's and Don'ts

### Do:
- Keep all SVG diagrams high-fidelity, representing real project workflows and interfaces.
- Maintain WCAG AA contrast for text layers and code syntax colors.
- Use clean Markdown tables and precise technology pills.

### Don't:
- Don't use generic shields.io badge walls or bright neon logos.
- Don't use low-detail placeholder SVG cards with fake terminal prompt lines (`> _`).
- Don't introduce fake metrics or commercial claims.
