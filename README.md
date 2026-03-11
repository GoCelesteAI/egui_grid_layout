# Learn egui in Neovim — Episode 8: Grid Layout

Build an aligned contact form using `egui::Grid` with rows, columns, and spacing.

## What You'll Build
A contact form with Name, Email, Phone, and Subject fields in an aligned grid, plus a submission summary.

## Prerequisites
- Rust installed (`rustup`)
- Basic Rust knowledge

## Run
```bash
cargo run
```

## Key Concepts
- `egui::Grid::new()` — create aligned rows and columns
- `ui.end_row()` — mark the end of each row
- `.num_columns()` — set column count
- `.spacing()` — control gaps between cells
- Multiple grids with unique string IDs

## Series
[Learn egui in Neovim](https://www.youtube.com/@CelesteAI) — 32-episode series teaching Rust GUI with egui
