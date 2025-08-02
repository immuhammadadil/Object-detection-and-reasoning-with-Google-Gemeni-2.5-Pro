#  Object Detection and Visual Reasoning using Google Gemini 2.5 Pro

This project demonstrates how to use **Google Gemini 2.5 Pro** to perform **object detection**, **image captioning**, **visual reasoning**, and **OCR** — all directly through a single API. The notebook combines multimodal capabilities to interpret and analyze images using natural language prompts.

>  No local detection models like YOLO are needed. Everything runs through the Gemini API.

---

##  Features

-  Load and analyze images from local files or URLs
-  Use Gemini 2.5 Pro Vision for:
  - Object Detection  
  - Image Captioning  
  - Visual Reasoning  
  - Text Extraction (OCR)
-  Clean and parse JSON responses from Gemini
-  Visualize detections with bounding boxes and labels

---

## 📁 Installations Required

pip install -U google-genai ultralytics

## Setup Required

Generate a Gemini API key by visiting Google AI Studio.
https://aistudio.google.com/apikey

Replace the placeholder api_key="..." with your actual API key inside the notebook.

Run all cells sequentially.


## Example Use Cases
Image-based visual Q&A

Captioning and annotating media

Automating labeling pipelines for ML training

Explainable AI through natural language prompts


## Output Example
Prompt: "Detect the 2D bounding boxes of objects in this image."

Response: Gemini returns JSON-like object detection results which are parsed and plotted.


## Model Used
Google Gemini 2.5 Pro Vision

Handles object detection and reasoning directly via API
