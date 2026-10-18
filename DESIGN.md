---
version: "1.0"
name: "Kliuba Oleh — Swiss-Brutalist Designer Portfolio"
description: "Bilingual (UA/EN) Swiss-Brutalist modular grid portfolio for Kliuba Oleh with Be Vietnam Pro typography, #DFEAE8 primary canvas with papercut overlay texture, and synchronized PC/Mobile layouts."
colors:
  background-primary: "#DFEAE8"
  surface-secondary: "#BBC9C7"
  ink-primary: "#05090A"
  ink-secondary: "#0E191E"
  border-strong: "#05090A"
  border-subtle: "#0E191E"
typography:
  display-hero:
    fontFamily: "Be Vietnam Pro"
    fontWeight: 700
    textTransform: "uppercase"
    lineHeight: 0.94
    letterSpacing: "-0.03em"
  h1-section:
    fontFamily: "Be Vietnam Pro"
    fontWeight: 700
    textTransform: "uppercase"
    lineHeight: 1.0
    letterSpacing: "-0.025em"
  h2-card:
    fontFamily: "Be Vietnam Pro"
    fontWeight: 700
    textTransform: "uppercase"
    lineHeight: 1.1
    letterSpacing: "-0.015em"
  body-primary:
    fontFamily: "Be Vietnam Pro"
    fontWeight: 500
    lineHeight: 1.55
    letterSpacing: "0em"
  label-meta:
    fontFamily: "Be Vietnam Pro"
    fontWeight: 700
    textTransform: "uppercase"
    lineHeight: 1.2
    letterSpacing: "0.06em"
rounded:
  none: "0px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "40px"
  xl: "64px"
components:
  button-brutalist:
    backgroundColor: "{colors.ink-primary}"
    textColor: "{colors.background-primary}"
    typography: "{typography.label-meta}"
    rounded: "{rounded.none}"
    padding: "16px 24px"
  card-project:
    backgroundColor: "{colors.background-primary}"
    textColor: "{colors.ink-primary}"
    rounded: "{rounded.none}"
---

## Overview

Swiss International Typographic Style collided with architectural Brutalism. Exposed hairline and heavy structural grid lines (`1.5px` and `2px solid #05090A`), zero border-radius (`0px`), stark hard-offset shadows (`6px 6px 0px #05090A`) on interactive elements, and raw typographic authority anchored by the slogan **"STAND OUT OR SIT OUT"**.

## Colors

- **Primary Canvas (`#DFEAE8`):** Soft Ice Mint base with full-bleed papercut texture (`DESIGNSYNDROME-PAPERCUT-TEXTURE59.jpg`) blended via `mix-blend-mode: overlay` at subtle controlled opacity so the tactile creases enrich the surface without shifting the `#DFEAE8` hue.
- **Secondary Surface (`#BBC9C7`):** Muted Sage-Grey for index cells, hover highlights, tag badges, and structural dividers.
- **Primary Ink & Grid (`#05090A`):** Deep Obsidian for all primary typography, exposed Swiss-Brutalist grid lines, and primary CTA blocks (contrast ratio against `#DFEAE8` is **16.1:1**, exceeding WCAG AAA).
- **Secondary Dark Slate (`#0E191E`):** Dark Slate Teal for secondary blocks, inverted statement bands, and hover states.

## Typography

- **Exclusive Typeface:** `Be Vietnam Pro` from the user's Google Drive folder `BeVietnamPro`.
- **Headings Rule:** Every heading, section title, project title, service title, and slogan is set in **ALL CAPS (`text-transform: uppercase`)** with **Bold (`font-weight: 700`)** styling.
- **Body & Labels:** `Medium (500)` and `Light (300)` for crisp editorial legibility.

## Layout & Spacing

- **Synchronized Dual Format (PC & Mobile):** Identical visual language, modular grid cells, content, and functionality adapted cleanly to Desktop (`12-column` Swiss modular grid) and Mobile (`single-column / 2-column` compact Swiss-Brutalist grid with sticky bottom/thumb-zone quick actions), plus an interactive viewport switcher (`AUTO / PC / MOBILE`) in the top utility bar so the user can inspect both versions side-by-side at any time.
