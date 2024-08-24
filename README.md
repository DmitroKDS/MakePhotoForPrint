---

# MFest Image Processing System

This program is developed for MFest to automate the creation of large-format paintings based on customer orders. The system processes an order file, retrieves corresponding images via an API, resizes them to their actual dimensions, and then compiles them into canvases for printing.

## Key Features

- **Order Processing:** Reads orders from a file and retrieves corresponding images using an API.
- **Image Handling:** Resizes images to their actual dimensions and organizes them into canvases for printing.
- **Automated Workflow:** Facilitates the creation of large-format paintings by automating image processing and canvas compilation.

## How to Use

1. **Upload Orders File:** Users upload an orders file through the web interface.
2. **Image Retrieval:** The system retrieves images associated with the order from the API.
3. **Canvas Creation:** Images are resized to real dimensions and combined into canvases.
4. **Download Canvases:** The processed canvases are available for download zip file with log and canvases.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DmitroKDS/MakePhotoForPrint.git
   ```

2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python MakePhotoForPrintApp.py
   ```

---
