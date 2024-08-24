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

## Requirements
- Python 3.x
- `flask`
- `requests`
- `pillow`
- `openpyxl`

## Images
- **Main Page:** <img width="1313" alt="Screenshot 2024-08-24 at 23 41 00" src="https://github.com/user-attachments/assets/718e060d-0be5-4e62-9496-0e4fea53cea4">
- **Process Page:** <img width="1313" alt="Screenshot 2024-08-24 at 23 41 43" src="https://github.com/user-attachments/assets/73a251ed-8f59-4e83-96f8-51cd966b0d52">
- **Downloading Page:** <img width="1313" alt="Screenshot 2024-08-24 at 23 41 50" src="https://github.com/user-attachments/assets/44640786-0ef0-454b-bf08-11838bb93365">

---
