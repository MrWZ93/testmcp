# TestMCP: Multi-format Data Analysis Tools

This repository contains a collection of Python tools for data viewing, analysis, and processing with specific focus on scientific data formats.

## Key Components

### 1. File Viewer
`file_viewer.py` - A PyQt6-based application for viewing and processing various file formats including:
- HDF5 (.h5)
- TDMS
- ABF
- CSV

Features include:
- Multi-channel data visualization
- Data processing (filtering, baseline correction, etc.)
- File metadata viewing
- Note-taking functionality

### 2. H5 Reader
`h5_reader.py` - A dedicated HDF5 file analysis tool with advanced visualization options.

### 3. Histogram Analysis
`histogram3.py` - A specialized tool for histogram generation and statistical analysis of data.

## Setup

### Creating Virtual Environment
```bash
# On macOS/Linux
source setup_environment.sh

# On Windows
setup_environment.bat
```

### Requirements
Main dependencies include:
- numpy
- pandas
- h5py
- scipy
- matplotlib
- PyQt6
- nptdms (optional)
- pyabf (optional)

## Usage

Run the individual tools directly:
```bash
python file_viewer.py
python h5_reader.py
python histogram3.py
```

## License
[MIT License](LICENSE)