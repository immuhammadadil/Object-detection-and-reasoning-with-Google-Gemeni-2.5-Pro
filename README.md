#  Object Detection and Visual Reasoning using Google Gemini 2.5 Pro

This project demonstrates how to use **Google Gemini 2.5 Pro** to perform **object detection**, **image captioning**, **visual reasoning**, and **OCR** — all directly through a single API. The notebook combines multimodal capabilities to interpret and analyze images using natural language prompts.

>  No local detection models like YOLO are needed. Everything runs through the Gemini API.




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


## Detection & Captioning Example
---

Object Detection & Captioning Example:
<img width="1278" height="832" alt="download" src="https://github.com/user-attachments/assets/7c0fed52-0aed-4f83-8a70-8d0d2ab9e0e3" />

Here are a few caption options for the image, ranging from descriptive to more thematic:

**Descriptive:**

*   Four iconic military aircraft, including a P-51 Mustang, F-86 Sabre, F-16 Fighting Falcon, and F-22 Raptor, flying in formation against a clear blue sky.
*   A stunning display of aviation history and modern air power.
*   Different generations of U.S. Air Force aircraft soaring together.

**Thematic/Evocative:**

*   Generations of flight: From propeller power to stealth technology, a breathtaking showcase of American air superiority.
*   The ultimate heritage flight: Witnessing the evolution of military aviation in one frame.
*   Past, present, and future of air power, beautifully captured in formation.
*   A tribute to the legacy and innovation of the U.S. Air Force.
*   Soaring through history: An incredible lineup of legendary aircraft.

**Short & Punchy:**

*   Air power through the ages!
*   Generations of flight.
*   Iconic aircraft in formation.
*   Heritage Flight goals.

**You can also add relevant hashtags:**
#AirForce #Aviation #HeritageFlight #MilitaryAircraft #FighterJets #P51Mustang #F86Sabre #F16 #F22Raptor #Airshow #USAF #Aircraft #Flight #HistoryOfFlight


Handles object detection and reasoning directly via API
