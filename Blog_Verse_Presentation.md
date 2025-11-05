# Blog Verse — Presentation Deck (16 slides)

This file contains the full slide-by-slide content, speaker notes, image placement, and export instructions for the Blog Verse presentation. Use this to copy into PowerPoint/Google Slides or download the markdown and convert to PDF.

---

Slide 1 — Title slide

- Title: Blog Verse
- Subtitle: A lightweight blogging platform — read & write posts
- Presenter: Mitsav Sharma, BCA 5th Sem
- Institution / date: MERI College of Engineering and Technology — 7 November 2025
- Footer: Demo built with HTML, CSS, JavaScript
- Image: use image 5 (header/logo area)
- Speaker notes: "Good [morning/afternoon], Professor and everyone. I’m Mitsav Sharma from BCA 5th semester. Today I’ll present Blog Verse — a responsive blogging site I built using HTML, CSS, and JavaScript. I’ll walk through the UI, core functionality, how key features work, and show the live-like UI screenshots. Let’s begin."

Slide 2 — Agenda / Outline

- Agenda bullets:
  - Motivation & Goals
  - UI Walkthrough (feed, filters, post view)
  - Core Functionality (search, tags, create post, theme)
  - Implementation overview
  - Demo screenshots & behavior
  - Limitations & Future Work
  - Q&A
- Notes: "Quick roadmap — I’ll cover motivation, UI, functionality, and implementation, then finish with next steps and questions."

Slide 3 — Motivation / Goals

- Title: Why Blog Verse?
- Bullets:
  - Provide a simple platform to read, write, and share short blog posts
  - Designed for classroom demos — easy to extend and inspect
  - Emphasis on UX: quick browsing, tagging, and lightweight authoring
- Speaker notes: "Blog Verse was created..."

Slide 4 — Architecture Overview

- Bullets:
  - Static front-end: HTML pages, CSS for styling, JS for interactivity
  - Data: sample JSON or in-memory data structure (demo)
  - No backend required for the demo; can be adapted to a REST API
- Notes: "Static front-end prototype..."

Slide 5 — Main Feed & Card Layout

- Visual: use image 1 (main feed light-mode)
- Caption: Cards show cover image, title, author, tags, excerpt and actions
- Speaker notes: full description of feed, cards, responsiveness

Slide 6 — Filters & Tag Chips

- Visual: cropped tags from image 1 or 5
- Bullets: clickable chip filters, clear filters button, categories in footer
- Notes: short explanation

Slide 7 — Search, Sort & Theme Toggle

- Visual: use header screenshot (image 1 or 5)
- Bullets: search input, sort dropdown, theme toggle
- Speaker notes: full script about implementation

Slide 8 — Create Post — Authoring Flow

- Visual: image 7 (create post modal)
- Bullets: fields: Title, Author, Cover Image URL, Tags, Content; Publish adds post in-memory; modal for focused editing
- Speaker notes: full script about publishing flow

Slide 9 — Post View — Reading Mode

- Visual: image 6 (post detail modal)
- Bullets: full cover image/title/content; comments area; modal reading view
- Notes: short explanation

Slide 10 — Profile & Quick Actions

- Visual: small profile dropdown (image 5 crop)
- Bullets: view profile/my posts/sign out; new post and theme toggle
- Notes: short

Slide 11 — Footer & Navigation

- Visual: image 3 (dark footer)
- Bullets: quick links, categories, subscribe field
- Notes: short

Slide 12 — Core Front-end Logic

- Bullets: data model: posts array; UI state: filters/search/sort/theme; event flow: DOM event -> handler -> update state -> re-render
- Speaker notes: full

Slide 13 — Interactivity Examples

- Bullets: tag click filter, debounced search, sort reorder, theme toggle
- Notes: short

Slide 14 — Testing & Responsiveness

- Bullets: mobile-first CSS; manual test cases; accessibility checks
- Notes: short

Slide 15 — Limitations & Next Steps

- Bullets: add backend/auth/rich editor/image uploads/pagination
- Notes: full script

Slide 16 — Conclusion & Q&A

- Bullets: simple extensible demo; built with HTML/CSS/JS; thank you; questions
- Notes: full script

Appendix: sample JSON, how to run locally, repo/contact

---