# Exif Analyzer Script

This script analyzes photo metadata to create a histogram of the focal lengths used by camera.

## Features
- Scans a folder of images and extracts focal length metadata
- Outputs:
  - `focal_length_histogram.csv`: 35-mm-equivalent focal length histogram
  - `camera_focal_usage.csv`: Camera, native-mm, 35-mm-eq, count
  - `focal_length_histogram.png`: Bar chart of focal length usage

## Requirements
- Python 3
- [exiftool](https://exiftool.org/) (must be installed and available in your PATH)
- `matplotlib` Python package

## Installation
Install the required Python package:
```bash
pip install matplotlib
```

Install exiftool (macOS example):
```bash
brew install exiftool
```

## Usage
Run the script with the path to your photo folder:
```bash
python analyze_focal_lengths.py /path/to/photo_folder
```

## Output
- `focal_length_histogram.csv`: Histogram of 35mm-equivalent focal lengths
- `camera_focal_usage.csv`: Usage stats by camera and focal length
- `focal_length_histogram.png`: Bar chart visualization

## License
MIT (add your preferred license here)
