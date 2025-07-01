# mantisx-notebook

![](docs/mantisx_notebook.png)

## Overview

This repository contains Jupyter notebooks for analyzing training data from MantisX, a shooting performance analysis system. MantisX provides detailed metrics on shooting performance, including movement patterns, timing, and accuracy data that can be analyzed to improve shooting technique.

## Purpose

The notebooks in this repository are designed to:

- Load and process MantisX training session data
- Perform statistical analysis on shooting performance metrics
- Visualize shooting patterns and trends over time
- Identify areas for improvement in shooting technique
- Track progress across multiple training sessions

## Data Structure

The repository includes sample data from holster draw analysis sessions, stored as JSON files in the `data/holster_draw_analysis/` directory. Each file represents a single training session with detailed performance metrics.

## Getting Started

1. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Open the main analysis notebook:

   ```bash
   jupyter notebook holster_draw_analysis.ipynb
   ```

3. Follow the notebook cells to load your MantisX data and perform analysis

## Requirements

See `requirements.txt` for the full list of Python dependencies needed to run the analysis notebooks.

## License

MIT License

Copyright (c) 2025 Michael Wiesendanger

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
