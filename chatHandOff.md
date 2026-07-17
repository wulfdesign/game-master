# 🕯️ Chat Hand-Off: GameMaster.io Landing Portal (v0.3.7.40)

**Date:** 2026-07-16  
**Status:** **LANDING PAGE DEPLOYED & STABILIZED** 🏆🐈  
**Live URL:** `https://wulfdesign.github.io/game-master/`

---

## 1. What This Repo Is

This is the **public landing page** for GameMaster.io. It's a simple gateway that routes visitors to:
*   The **static demo site** (`game-master-public` repo / GitHub Pages)
*   The **live web application** (once a domain is set up)

It does NOT contain any internal tools, backend code, or build scripts.

## 2. Current State

*   `index.html` — Landing page with hero section, feature cards, and responsive navigation links
*   `style.css` — Styling for the landing page, including responsive QR code alignment
*   `assets/` — Images, media, and generated QR code graphics (`qr-code-gamemaster.png` and print-friendly version)

## 3. Completed Work

*   [x] **Patreon Link:** Updated to live link `https://www.patreon.com/c/wulfdesign` across all pages.
*   [x] **QR Code:** Generated themed QR code and positioned it in the footer container, aligned right to match the card grid and main header splash.
*   [x] **Early Access Form:** Connected the live Google Form waitlist signup (`https://forms.gle/ALxXRXVbAMFGyCPV6`) to all CTA buttons.

## 4. Notes for Next Agent

*   This is a **public repo** — do NOT add internal tools, local file paths, or private project references
*   The static site exporter (`scrape_portal.py`) lives in the **private** `rpg-agentic-webapp/tools/` directory
*   The static demo pages live in the sibling `game-master-public/` repo
