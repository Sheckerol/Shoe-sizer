# Foot Measurement Cards

A simple, local "flash card" app for recording foot measurements used to build
parametric shoe lasts (matching the **Build Shoe Last** dialog).

## Usage

Open `index.html` in any web browser. No server or install needed — everything
is saved **locally in your browser** (via `localStorage`), just like flash cards.

## What you can record per card

- **Name** (e.g. "My Right Foot — June 2026")
- **Sizing System** (US Men, US Women, UK, EU, Japan cm, Mondopoint)
- **Size**, **Width**, **Side** (Left / Right / Pair), **Color**
- **Measurements (mm)** — each with a *Foot* value, a *Last (Bottom)* value, and an *Adapt* flag:
  - Length
  - Ball Girth
  - Instep Girth
  - Ball Width
  - Heel Height
- **Notes** (templates used, fit notes, etc.)

## Features

- Add, edit, duplicate, and delete cards
- Search across all cards
- **Export** all cards to a JSON file for backup, and **Import** them back
  (useful for moving between devices, since data is stored per-browser)

## Note on local storage

Cards live in the browser you use. Clearing browser data will remove them — use
**Export** periodically to keep a backup.
