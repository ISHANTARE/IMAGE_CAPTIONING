# Image Captioning & Segmentation App

This project combines **panoptic segmentation** using Facebook's `Mask2Former` with **context-aware image captioning** using Salesforce's `BLIP-2`.

## Features

- Upload or use a URL to analyze any image
- Detect and label objects using panoptic segmentation
- Generate a natural language caption mentioning detected objects
- Visualize results with colored masks and overlayed captions

## Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/image-captioning-segmentation.git
cd image-captioning-segmentation
pip install -r requirements.txt
