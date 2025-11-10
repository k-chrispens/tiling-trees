# 🌳 Tiling Tree Builder

A simple, interactive web application for creating Tiling Trees - a problem decomposition method that helps break down complex problems into manageable pieces.

## Features

- **Auto-Branching**: Start typing and branches automatically sprout
  - Type in the root node → 2 child branches appear
  - Fill both branches → a 3rd placeholder branch appears
  - Each filled node automatically generates child branches

- **Pure Browser-Based**: No backend required, all data stored in your browser's localStorage

- **Export Options**:
  - Export to SVG (vector graphics)
  - Export to PNG (raster image)
  - Only filled branches are exported (placeholder branches are excluded)

- **Clean Interface**:
  - Intuitive text inputs for each node
  - Visual tree structure with connecting lines
  - Gradient background and modern styling

## How to Use

1. Open `index.html` in your web browser
2. Start typing your main problem or goal in the root node
3. Two branches will automatically appear below
4. Fill in the branches to break down your problem
5. As you fill branches, new placeholder branches will appear to encourage further exploration
6. Click "Export SVG" or "Export PNG" to save your completed tree
7. Click "Reset Tree" to start over

## Tiling Tree Method

The Tiling Tree method is a problem decomposition technique where you:
1. Start with a complex problem or goal
2. Break it down into 2-3 sub-problems
3. Continue breaking down each sub-problem until you reach actionable tasks
4. The tree structure helps visualize the entire problem space

## Technology

- Pure HTML, CSS, and JavaScript
- No dependencies or frameworks
- SVG for tree rendering
- Canvas API for PNG export
- localStorage for browser persistence

## File Structure

```
tiling-trees/
├── index.html          # Main application (all-in-one file)
└── README.md          # This file
```

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- localStorage
- Canvas API
- SVG

## Privacy

All data is stored locally in your browser. Nothing is sent to any server.
