# CliniScan

Streamlit app for Chest X-Ray classification with optional Grad-CAM and DICOM support.

## Features
- Upload JPG/PNG or DICOM (.dcm)
- Load a trained `model.pth` (2-class or multi-class)
- Grad-CAM visualization (requires pytorch-grad-cam)

## Quick start (Colab)
1. Install dependencies:
pip install -r requirements.txt
pip install git+https://github.com/jacobgil/pytorch-grad-cam.git

2. Run:
streamlit run app.py

