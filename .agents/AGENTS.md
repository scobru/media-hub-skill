# AGENTS.md - Workspace Agent Instructions for Gimmie

This file defines the project-scoped rules and behavioral guidelines for AI agents operating on the `gimmie` workspace.

## 🎯 Primary Purpose
`gimmie` is a free, legal, client-side entertainment dashboard SPA. All modifications must preserve its zero-cost, legal-only, offline-first, and high-aesthetic design goals.

## 📋 Essential Rules

1. **Strictly Legal & Free Content**:
   - Only include legal sources (Tubi, Pluto TV, YouTube, Internet Archive, itch.io, Lichess, Standard Ebooks, etc.).
   - Never reference unlicensed or pirated platforms.

2. **Unbreakable Links Strategy**:
   - Use dynamic search URL queries (`https://tubitv.com/search/[Query]` or `https://www.youtube.com/results?search_query=[Query]`) instead of numeric IDs.
   - Never leave dummy `#` links.

3. **Cover & Logo Resolution**:
   - Pass content titles through `getContentCoverUrl(title)` in `app.js`.
   - Ensure accurate Wikimedia Commons posters for classic films and official logos for YouTube channels.

4. **Zero Backend Dependencies**:
   - Keep all logic in client-side HTML/CSS/JS.

5. **HTML Layout Validation**:
   - Double-check all closing tags (`</aside>`, `</main>`) to prevent layout breaking.
