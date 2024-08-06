# mЬetaset
simple tool to read/write exif dta of images

## Overview

This script allows users to read and edit metadata of `.jpg` image files. It extracts metadata using the `PIL` (Pillow) library and provides a user-friendly interface using the `colorama` library for console output. The script also uses `tkinter` for file dialog operations.

## Features

- Read metadata from `.jpg` files
- Convert GPS metadata into a human-readable format
- Generate Google Maps links from GPS metadata
- File selection via a graphical file dialog

## Requirements

- Python 3.x
- `Pillow`
- `colorama`
- `tkinter`

## Installation

Follow these steps to install and run the script:

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/metadata-reader.git
cd metadata-reader
```

### 2. Create a Virtual Environment

It's a good practice to use a virtual environment to manage dependencies:

```bash
python -m venv venv
```
