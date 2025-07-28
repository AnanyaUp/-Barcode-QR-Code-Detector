#  QR & Barcode Detector using OpenCV and Pyzbar

This project is a Python-based tool for automatically detecting, decoding, and extracting information from **QR codes** and **barcodes** found in scanned image documents. It uses `OpenCV` for image processing and `pyzbar` for decoding, with batch processing support and CSV export of results.

---

##  Features

-  Detects both QR codes and 1D barcodes from `.jpg` and `.png` images
-  Draws bounding boxes and overlays decoded data on the image
-  Decodes content (text, URLs, numbers, etc.) using `pyzbar`
-  Processes multiple images using `glob`
-  Exports results to a structured CSV file
-  Saves annotated images to a results folder

---

