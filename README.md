# 🍽️ Table Planner

A simple, single-file drag-and-drop table seating planner. No build step required — just open `index.html` in a browser.

[Use Table Planner Now!](https://cnorlander.github.io/table-planner/)

## Features

- **Drag & drop** guests between tables and reorder within a table (powered by [SortableJS](https://sortablejs.github.io/Sortable/))
- **Split layout** — unassigned guests in a scrollable sidebar on the left, tables in the main area with independent scrolling
- **Settings panel** to define tables and guests (one per line)
- **Smart updates** — adding guests puts them in the "Unassigned" box; removing a table moves its guests back to unassigned; existing assignments are preserved
- **Guest count badges** on every table
- **Auto-save** to localStorage — your layout persists across page reloads
- **Import / Export** — export your seating plan to a plain text file and import it back later
- **Reset button** to clear all data and start fresh
- **Print-friendly** — hides the unassigned box, settings, and toolbar; tables expand fully with no scrollbars

## Usage

1. Open `index.html` in any modern browser.
2. Click **⚙️ Settings** to add your table names and guest names (one per line).
3. Click **Update Guests** to build the board.
4. Drag guests from the **Unassigned** sidebar onto tables and reorder as needed.
5. Click **📤 Export** to save your plan as a `.txt` file, or **📥 Import** to load one.
6. Click **🖨️ Print** to print your seating plan.
7. Click **🗑️ Reset** to clear everything and start over.

## Tech

- Single HTML file, zero build steps
- [SortableJS](https://cdn.jsdelivr.net/npm/sortablejs@1.15.6/Sortable.min.js) via CDN
- localStorage for persistence
