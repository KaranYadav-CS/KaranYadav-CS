# Cloud-Based-Vision-Project

**Cloud-Based Computer Vision System using Microsoft Azure AI Vision Studio**

A cloud-based computer vision project built using Microsoft Azure for face detection, facial attribute analysis, and image intelligence workflows.

![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Platform](https://img.shields.io/badge/platform-cloud-blue)
![Azure](https://img.shields.io/badge/cloud-Microsoft%20Azure-0078D4)
![Domain](https://img.shields.io/badge/domain-computer%20vision-purple)
![Service](https://img.shields.io/badge/service-Azure%20AI%20Vision-orange)

---

## Overview

Cloud-Based-CV-Project is a beginner-friendly cloud computer vision implementation developed using **Microsoft Azure AI Vision Studio**.

This project demonstrates how cloud AI services can analyze images and detect faces without requiring local machine learning model training or GPU setup.

The project focuses on:

- face detection in images
- face bounding box generation
- face mask detection
- facial attribute extraction
- JSON-based output analysis
- Azure cloud AI workflow understanding

This repository contains project documentation, sample outputs, screenshots, and implementation details.

---

## Project Objective

Traditional computer vision projects often require:

```text
Dataset Collection
    ↓
Model Training
    ↓
GPU Configuration
    ↓
Deployment
```

This project explores an alternative cloud-first workflow:

```text
Image Input
    ↓
Azure AI Vision Service
    ↓
Cloud Processing
    ↓
Face Detection + Attributes
    ↓
Results Output
```

This reduces development complexity and allows faster deployment of AI solutions.

---

## Features

### Implemented Features

- Human face detection
- Face localization using bounding boxes
- Face mask detection
- Facial attribute analysis
- JSON output visualization
- Azure Vision Studio experimentation

### Current Supported Detection

```text
Image Upload
    ↓
Face Detection
    ↓
Bounding Box Generation
    ↓
Attribute Analysis
```

Detected attributes include:

- face presence
- face mask detection
- face landmarks
- pose-related metadata

---

## Project Workflow

```text
User Uploads Image
        ↓
Azure AI Vision Studio
        ↓
Face Detection Model
        ↓
Detected Attributes
        ↓
JSON Output
```

This workflow is fully cloud-based.

No local training is required.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Microsoft Azure AI Vision Studio | Computer vision analysis |
| Azure Cognitive Services | Cloud AI APIs |
| GitHub | Version control and repository hosting |
| JSON | Output data format |

---

## Azure Service Used

Primary service:

```text
Azure AI Vision Studio
```

Feature used:

```text
Detect Faces in an Image
```

Capabilities used:

- face detection
- facial attributes
- face mask analysis
- bounding box generation

---

## Project Demonstration

### Azure Vision Studio Interface

The project uses Azure Vision Studio for uploading and analyzing images.

---

### Sample Detection Flow

```text
Input Image
    ↓
Azure Face Detection
    ↓
Detected Face #1
    ↓
Face Mask Status
```

Sample output:

```json
{
  "Face #1": {
    "Face mask": "No"
  }
}
```

---

## Repository Structure

```text
Cloud-Based-CV-Project/
│
├── README.md
├── LICENSE
```

Repository structure is intentionally minimal because this project focuses on Azure cloud experimentation.

---

## How to Run

### Step 1: Create Azure Resource

Create an Azure AI Vision resource in Microsoft Azure.

---

### Step 2: Open Vision Studio

Visit:

```text
https://portal.vision.cognitive.azure.com/
```

---

### Step 3: Select Feature

Choose:

```text
Detect faces in an image
```

---

### Step 4: Upload Image

Upload:

- custom image
- sample image

---

### Step 5: View Results

Outputs available:

- detected attributes
- JSON results
- face bounding boxes

---

## Sample Result

### Input

```text
Human Face Image
```

### Output

```text
Face Detected Successfully
Face Mask: No
```

---

## Cloud Benefits

Using Azure provides:

- scalable cloud AI processing
- no GPU dependency
- fast deployment
- managed AI services
- production-ready cloud APIs

---

## Learning Outcomes

This project helped in understanding:

- cloud-based AI systems
- Azure AI Vision Studio
- Azure Cognitive Services
- face detection workflows
- AI service integration
- cloud computer vision pipelines

---

## Implementation Status

| Component | Status |
|---|---|
| Azure resource setup | Completed |
| Vision Studio configuration | Completed |
| Face detection | Completed |
| Bounding box detection | Completed |
| Face mask detection | Completed |
| JSON output analysis | Completed |
| Documentation | Completed |

---

## Future Improvements

Planned future upgrades:

- emotion detection
- age estimation
- gender analysis
- object detection
- OCR integration
- image captioning
- REST API integration
- Python SDK implementation

---

## Limitations

Current limitations:

- demo-based implementation
- no custom model training
- no real-time webcam integration
- no API automation yet
- no local deployment

This project is primarily focused on learning Azure computer vision workflows.

---

## Use Cases

Potential applications:

- smart surveillance
- attendance systems
- mask detection systems
- visitor analytics
- cloud AI experimentation

---

## Author

**Karan Yadav**

B.Tech CSE (AI & ML)  
Chandigarh University  

Research Interests:

- Artificial Intelligence
- Machine Learning
- Computer Vision
- Cloud Computing
- Azure AI Services

GitHub:

```text
https://github.com/Karan898989
```

---

## License

This project is licensed under the MIT License.

---
