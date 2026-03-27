<div align="center">

# Document Scanner

Computer vision project for detecting document edges, recovering perspective, and rectifying photographed pages.

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.8+-5C3EE8?logo=opencv)](https://opencv.org/)
[![MATLAB](https://img.shields.io/badge/MATLAB-R2023b-0076A8?logo=mathworks)](https://www.mathworks.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

[Live Demo](https://mangeshraut712.github.io/Document-Scanner---Computer-Vision-Project) · [Quick Start](QUICKSTART.md) · [Changelog](CHANGELOG.md)

</div>

## Overview

This repository implements a document scanning pipeline that detects page boundaries, estimates line structure, and rectifies the image into a cleaner top-down view. The project ships both Python and MATLAB implementations, plus a simple browser demo for quick testing.

## Table of Contents

- [Features](#features)
- [Stack](#stack)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- Edge detection and Hough-based line finding.
- Corner identification and homography-based rectification.
- Python and MATLAB implementations of the same workflow.
- Web demo for trying the pipeline without installation.
- Tests and documentation for the main processing steps.

## Stack

- Python
- OpenCV
- NumPy
- Matplotlib
- MATLAB
- Vanilla HTML, CSS, and JavaScript for the demo

## Quick Start

### Web demo

```bash
cd web
open index.html
```

### Python

```bash
pip install -r requirements.txt
python src/python/document_scanner.py
```

### MATLAB

```matlab
cd src/matlab
run_scanner
```

## Project Structure

```text
.
├── src/python/           # Python scanner implementation
├── src/matlab/           # MATLAB scanner implementation
├── web/                  # Browser demo
├── tests/                # Python tests
├── examples/             # Sample input images
├── QUICKSTART.md         # Short setup guide
└── CHANGELOG.md          # Release notes
```

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.
