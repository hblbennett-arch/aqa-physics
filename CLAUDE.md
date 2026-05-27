# AQA A Level Physics Paper 1 Revision Site

## Project Overview
Interactive revision site for AQA A Level Physics Paper 1 (7408/1). Provides worked solutions to all past paper questions (June 2017–2024) with detailed thinking sections, mark scheme analysis, JSXGraph diagrams, and examiner insights.

## Live Site
- https://hblbennett-arch.github.io/aqa-physics/output/index.html

## Folder Structure
- `output/` — deployed HTML (index + paper pages)
- `output/papers/` — one HTML file per paper sitting
- `data/raw/` — PDFs and text extracts (NOT committed)
- `docs/` — workflow documentation

## Tech Stack
- KaTeX CDN v0.16.9 for maths/physics notation
- JSXGraph CDN v1.8.0 for interactive diagrams
- Single self-contained HTML per paper (no build step)
- Vanilla JS for interactivity (step reveals, tab switching)
- GitHub Pages from main branch root

## Key Rules
1. **Units on every step** — physics mark schemes award marks for correct units
2. **Follow mark scheme method** — read the actual MS .txt file, don't use shortcuts
3. **Data booklet tags** — verify against official AQA data booklet PDF, never from training knowledge
4. **JSXGraph in hidden panels** — lazy-init after panel is visible (same as edexcel-maths)
5. **MCQs explain ALL options** — correct answer AND why each wrong option is wrong
6. **Strategy blocks** — scenario ID, assumptions, command words, traps, time allocation

## Topic Categories (Paper 1)
1. Measurements & Errors
2. Particles & Radiation
3. Waves
4. Mechanics
5. Materials
6. Electricity
7. Periodic Motion (SHM, resonance, damping)

## Available Papers
June 2017, 2018, 2019, 2020, 2021, 2022, 2023, 2024
(2020/2021 were Nov sittings due to COVID but labelled June by PMT)
