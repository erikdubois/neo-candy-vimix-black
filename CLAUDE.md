# CLAUDE.md — neo-candy-vimix-black

## Project overview

Standalone repo for the **neo-candy-vimix-black** folder-icon theme — the same folder set as
`erikdubois/surfn-vimix-black` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-vimix-black/` — folders only. Packaged as `neo-candy-vimix-black-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-vimix-black/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
