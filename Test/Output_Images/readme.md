VisionFlux Processing ToolKit Image Engine

A Lightweight C++ Image Processing Toolkit for PPM and PGM Formats

📌 Overview

VisionFlux Processing ToolKit Image Engine is a modular, CLI-based C++ image processing framework built for educational, research, and lightweight imaging applications.
It supports PPM (P6) and PGM (P5) formats and provides a wide range of transformation and enhancement operations.

The project follows clean modular design practices, separating I/O, processing, memory management, and execution flow for maximum readability and scalability.

📁 Project Structure
VisionFlux Processing ToolKit/
│
├── data/
│   ├── input/        # Source images (.ppm / .pgm)
│   └── output/       # Processed images
│
├── include/          # Header files
│   ├── global.h
│   └── Image.h
│
├── src/              # Source code
│   ├── main.cpp
│   └── global.cpp
│
└── README.md

✨ Features
📥 File Parsing

Read/Write PPM (P6)

Read/Write PGM (P5)

Comment skipping

Robust input validation

🖼 Image Operations
Color & Grayscale

Invert colors

Convert PPM → Grayscale PGM

Auto contrast

Brighten / Darken

Transforms

Horizontal/Vertical flip

90° rotation

Crop

Resize

Effects

Blur

Sharpen

Posterize

Threshold (binary)

Add borders

Merge two images

🧱 Code Architecture
Image.h

Defines the Image structure

Stores width, height, maxValue, and pixel buffer pointer

global.h / global.cpp

Function prototypes and implementations for

PPM/PGM I/O

Memory operations

Image transformations

Filtering & enhancement

main.cpp

User menu

Mode selection (PPM/PGM)

Calls processing functions

Writes output files

🚀 How to Build & Run
Compile
g++ src/*.cpp -o VisionFlux_Processing_ToolKit

Run
./VisionFlux_Processing_ToolKit

🔧 Future Enhancements

Add PNG/JPEG support

Histogram equalization

Edge detection (Sobel, Canny)

GUI using Qt or ImGui

📝 License

MIT License — free for academic and personal use.

👤 Author

Hammad Ashfaq - BCSF24M003
Muhammad Huzaifa Farrukh - BCSF24M001
Huzayfa Siddique - BCSF24M049
Computer Science — Punjab University, Allama Iqbal Campus, Lahore