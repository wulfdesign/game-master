# 🕯️ Chat Hand-Off: GameMaster.io Landing Portal (v0.3.0)

**Date:** 2026-07-12  
**Status:** **LANDING PAGE DEPLOYED** 🧪🐈

---

## 1. What This Repo Is

This is the **public landing page** for GameMaster.io. It's a simple gateway that routes visitors to:
*   The **static demo site** (`game-master-public` repo / GitHub Pages)
*   The **live web application** (once a domain is set up)

It does NOT contain any internal tools, backend code, or build scripts.

## 2. Current State

*   `index.html` — Landing page with hero carousel, feature overview, and navigation links
*   `style.css` — Styling for the landing page
*   `assets/` — Images and media for the landing page

## 3. Outstanding Work

*   [ ] **Domain Setup:** Once the live webapp has a domain, update the "Launch App" link
*   [ ] **Patreon Link:** Update early access signup link once Patreon is created
*   [ ] **QR Code:** Add a scannable QR code image linking to the GitHub Pages static site

## 4. Notes for Next Agent

*   This is a **public repo** — do NOT add internal tools, local file paths, or private project references
*   The static site exporter (`scrape_portal.py`) lives in the **private** `rpg-agentic-webapp/tools/` directory
*   The static demo pages live in the sibling `game-master-public/` repo
