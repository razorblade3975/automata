# Cellular Automata Visualizations

A collection of interactive cellular automata visualizations built with HTML5 Canvas and JavaScript.

## Live Demo

Visit the GitHub Pages site to try out the visualizations: 
[https://razorblade3975.github.io/automata/conways-game-of-life-unified.html](https://razorblade3975.github.io/automata/conways-game-of-life-unified.html)
[https://razorblade3975.github.io/automata/elementary-cellular-automaton.html](https://razorblade3975.github.io/automata/elementary-cellular-automaton.html)

## Visualizations

### 1. Conway's Game of Life
**File:** `conways-game-of-life-unified.html`

An implementation of Conway's Game of Life with advanced pattern management:
- **Unified Pattern System**: All patterns are editable - no distinction between presets and custom patterns
- **Pattern Editor**: 30×60 grid editor with movement controls (↑↓←→)
- **Interactive Controls**: Draw/erase modes, adjustable speed, grid size, and cell size
- **Pattern Library**: Includes classics like Glider, LWSS, Gosper's Glider Gun, Pentadecathlon, and more
- **Real-time Statistics**: Track generations, population, births, and deaths

### 2. Elementary Cellular Automaton
**File:** `elementary-cellular-automaton.html`

Explore all 256 rules of elementary cellular automata:
- **Visual Rule Editor**: Click to toggle outputs for each of the 8 neighborhood configurations
- **Preset Rules**: Quick access to famous rules (30, 90, 110, 184, etc.)
- **Multiple Initial States**: Single cell, random, or alternating patterns
- **Adjustable Parameters**: Cell size, grid size, and animation speed

### 3. Graph Cellular Automaton
**File:** `graph-cellular-automaton.html`

Cellular automata on graph structures instead of grids:
- **Multiple Graph Types**: Random, Grid, Ring, and Complete graphs
- **Various Update Rules**: Majority, Parity, Threshold, and Conway-like rules
- **Interactive Nodes**: Click to toggle initial states
- **Dynamic Visualization**: Watch patterns emerge on non-grid structures

### 4. Organic Cellular Automaton
**File:** `organic-cellular-automaton.html`

Creates organic, growth-like patterns:
- **Growth Patterns**: Organic, Coral-like, Dendrite, Crystal, and Lichen patterns
- **Interactive Seeding**: Click to add growth seeds anywhere
- **Age-based Coloring**: Visualize cell age with color gradients
- **Adjustable Parameters**: Growth rate, branching probability, cell size

## Features

All visualizations share common features:
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Interaction**: Draw/erase cells while paused or running
- **Zoom Support**: Mouse wheel to zoom in/out
- **Dark Theme**: Easy on the eyes for extended viewing
- **No Dependencies**: Pure HTML/CSS/JavaScript - no external libraries required

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/razorblade3975/automata.git
   ```

2. Open any HTML file in a modern web browser:
   ```bash
   open conways-game-of-life-unified.html
   ```

Or visit the GitHub Pages site to use them online.

## Controls

### Common Controls
- **Click/Drag**: Draw cells (in draw mode)
- **Right-click/Drag**: Erase cells
- **Mouse Wheel**: Zoom in/out
- **Play/Pause**: Start/stop the simulation
- **Step**: Advance one generation
- **Clear**: Clear the grid
- **Random**: Generate random initial state

### Pattern Management (Conway's Game of Life)
- **Create New Pattern**: Opens the pattern editor
- **Edit**: Modify existing patterns
- **Delete**: Remove patterns from your collection
- **Movement Buttons**: Position patterns in the editor (↑↓←→)

## Technical Details

- Built with vanilla JavaScript and HTML5 Canvas
- Uses `localStorage` for persisting custom patterns
- Efficient grid-based computation for smooth animation
- Responsive canvas sizing and controls

## Contributing

Feel free to fork this repository and submit pull requests for:
- New cellular automaton types
- Additional patterns
- Performance improvements
- UI/UX enhancements
- Bug fixes

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- John Conway for the Game of Life
- Stephen Wolfram for elementary cellular automata research
- The cellular automata community for patterns and inspiration
