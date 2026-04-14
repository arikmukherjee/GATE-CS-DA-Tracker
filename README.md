# GATE CS/DA Preparation Tracker

A lightweight single-page study tracker built with plain HTML, Tailwind CSS, and JavaScript.

This app helps GATE aspirants track their study progress across the CS and DA syllabi by marking topics as completed, revised, and practiced.

## Features

- Switch between **GATE CS** and **GATE DA** syllabi
- Track progress on individual topics using three states:
  - Completed
  - Revised
  - Practiced
- Summary dashboard showing:
  - Total topics
  - Completed topics
  - Revised topics
  - Overall progress percentage
- Import and export progress as JSON files
- Reset tracked progress for the selected exam
- Light / dark theme toggle with persistent preference
- Responsive layout using Tailwind CSS

## Usage

1. Open `index.html` in your browser.
2. Use the exam buttons at the top to switch between `CS` and `DA`.
3. Select a subject tab to view topics grouped by subtopic.
4. Check the boxes for progress tracking.
5. Export progress to save your current state.
6. Import a saved JSON file to restore progress.
7. Toggle the theme for light or dark mode.

## Included Syllabi

The tracker currently includes the following subject coverage:

- **GATE CS**
  - Engineering Mathematics
  - Digital Logic
  - Computer Organization and Architecture
  - Programming and Data Structures
  - Algorithms
  - Theory of Computation
  - Compiler Design
  - Operating System
  - Databases
  - Computer Networks
- **GATE DA**
  - Probability and Statistics
  - Linear Algebra
  - Calculus and Optimization
  - Programming & Data Structures
  - DBMS & Warehousing
  - Machine Learning
  - Artificial Intelligence

## Notes

- Progress is stored locally in the browser using `localStorage`.
- The app runs entirely on the client side and requires no backend.
- Uses Tailwind CSS from CDN and Lucide icons for the UI.

## Development

No build step is required. Simply open `index.html` in a browser to use the app.

## Future Improvements

Potential enhancements include:

- Search or filter topics
- Add per-topic notes or comments
- Add deadline and schedule tracking
- Add printable or exportable study plans
