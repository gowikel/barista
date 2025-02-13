# Barista: Crafting Visual Bar Charts in Go

Barista is a command-line tool written in Go that generates horizontal bar chart PNG images.  Perfect for quickly visualizing data and embedding charts in documents or presentations.

## Features

*   Creates segmented horizontal bar charts.
*   Outputs PNG images for easy embedding.
*   Simple command-line interface.
*   Customizable segment colors (currently random, but future versions may offer more control).
*   Clear text labels for each segment.

## Installation

```bash
  go install github.com/gowikelbarista@latest
```

## Usage

```bash
  barista -o output.png "Phase A:3" "Phase B:1" "Phase C:2" "Phase D:4"
```

- -o output.png: Specifies the output filename (default: bar_chart.png).
- "Phase A:3" "Phase B:1"...: List of phase names and durations, separated by colons.

## License

This project is licensed under the Unlicense - see the LICENSE file for details.
