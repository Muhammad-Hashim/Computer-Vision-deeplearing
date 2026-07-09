Yes. Since your goal is **computer vision researcher/engineer**, I would not give you 100 random “OpenCV draw a rectangle” projects.

I checked current YouTube material. There are genuine end-to-end tutorials covering **custom dataset collection → annotation → model training → testing/inference**, full multi-project CV courses, facial recognition, LSTM-based action recognition, U-Net segmentation, DeepSORT tracking, and Vision Transformers. ([YouTube][1])

**My recommendation for you: complete these 100 projects in order.**

One important rule:

> **Project 1–30:** Follow the tutorial.
>
> **Project 31–60:** Watch, close the video, then rebuild.
>
> **Project 61–80:** Change the dataset and problem.
>
> **Project 81–100:** Build your own architecture/pipeline and read a related paper.

Otherwise you will finish 100 tutorials and still be a professional copy-paster. A rather crowded profession.

---

# Phase 1 — CNN and Image Classification

Start here because PyTorch computer-vision material commonly introduces the complete training loop through CNN image classification: dataset loading, architecture, training, validation, and model saving. ([YouTube][2])

| #  | Project                            | YouTube search                                             |
| -- | ---------------------------------- | ---------------------------------------------------------- |
| 1  | MNIST Handwritten Digit Classifier | `MNIST CNN PyTorch project from scratch Python`            |
| 2  | CIFAR-10 Image Classifier          | `CIFAR10 CNN PyTorch complete project`                     |
| 3  | Cats vs Dogs Classifier            | `cats dogs deep CNN image classifier Python`               |
| 4  | Fashion Item Classifier            | `Fashion MNIST CNN PyTorch project`                        |
| 5  | Traffic Sign Recognition           | `traffic sign recognition CNN Python deep learning`        |
| 6  | Plant Disease Classification       | `plant disease detection CNN Python deep learning project` |
| 7  | Brain Tumor MRI Classification     | `brain tumor classification CNN PyTorch project`           |
| 8  | Pneumonia X-Ray Classification     | `pneumonia detection chest xray CNN PyTorch`               |
| 9  | Skin Cancer Image Classification   | `skin cancer classification deep learning Python project`  |
| 10 | Waste Classification               | `waste classification CNN deep learning Python`            |

**Do not skip Project 1–10.**

Traffic-sign tutorials, for example, include CNN-based classification and real-time camera inference. ([YouTube][3])

---

# Phase 2 — Transfer Learning

Now stop training every network blindly from zero.

| #  | Project                           | YouTube search                                           |
| -- | --------------------------------- | -------------------------------------------------------- |
| 11 | Cats vs Dogs with ResNet          | `ResNet transfer learning PyTorch cats dogs`             |
| 12 | Flower Classification with ResNet | `flower classification ResNet PyTorch transfer learning` |
| 13 | Food Image Classifier             | `food classification EfficientNet PyTorch project`       |
| 14 | Bird Species Classification       | `bird species classification deep learning PyTorch`      |
| 15 | Dog Breed Recognition             | `dog breed classification transfer learning PyTorch`     |
| 16 | Crop Disease Classifier           | `crop disease EfficientNet deep learning Python`         |
| 17 | Car Model Recognition             | `car model classification deep learning PyTorch`         |
| 18 | Animal Species Recognition        | `animal classification transfer learning PyTorch`        |
| 19 | Medical Image Classifier          | `medical image classification transfer learning PyTorch` |
| 20 | Custom Image Classifier           | `deep CNN image classifier any images Python`            |

A good exact tutorial here is **“Build a Deep CNN Image Classifier with ANY Images”**, which builds a custom classifier using Python, TensorFlow, and Keras. ([YouTube][4])

---

# Phase 3 — Object Detection with YOLO

This is where your real CV engineering journey starts.

Current Ultralytics tooling supports several major vision task families, including object detection, segmentation, pose estimation, and classification. ([Ultralytics Docs][5])

| #  | Project                       | YouTube search                                       |
| -- | ----------------------------- | ---------------------------------------------------- |
| 21 | Basic YOLO Object Detector    | `YOLO object detection Python complete project`      |
| 22 | Custom YOLO Detector          | `train YOLO custom dataset complete tutorial Python` |
| 23 | Helmet Detection              | `helmet detection YOLO Python project`               |
| 24 | PPE Safety Detection          | `PPE detection YOLO computer vision Python`          |
| 25 | Fire and Smoke Detection      | `fire smoke detection YOLO Python project`           |
| 26 | Face Mask Detection           | `face mask detection deep learning Python CNN YOLO`  |
| 27 | Pothole Detection             | `pothole detection YOLO Python complete project`     |
| 28 | Traffic Sign Detection        | `traffic sign detection YOLO Python`                 |
| 29 | Vehicle Detection             | `vehicle detection YOLO Python computer vision`      |
| 30 | Wildlife Detection            | `wildlife animal detection YOLO Python`              |
| 31 | Drone Object Detection        | `drone object detection YOLO Python project`         |
| 32 | Construction Worker Detection | `construction PPE detection YOLO Python`             |
| 33 | Retail Product Detection      | `retail product recognition YOLO custom dataset`     |
| 34 | PCB Defect Detection          | `PCB defect detection YOLO deep learning`            |
| 35 | Industrial Defect Detector    | `industrial defect detection YOLO Python project`    |

## Very important exact tutorial

Search:

> **Train Yolov8 object detection on a custom dataset | Computer vision engineer**

The tutorial explicitly covers **data collection, annotation, dataset structure, training, and testing**. ([YouTube][1])

Also use:

> **Full YOLO and Object Detection Tutorial from Scratch**

It includes custom YOLO workflows, object tracking, small-object detection and multiple YOLO versions. ([YouTube][6])

---

# Phase 4 — Detection + Tracking

Now the question changes.

Before:

> What is this?

Now:

> What is this, and **where did it move?**

YOLO plus DeepSORT and YOLO tracking tutorials are available as complete Python computer-vision builds. ([YouTube][7])

| #  | Project                        | YouTube search                                    |
| -- | ------------------------------ | ------------------------------------------------- |
| 36 | YOLO + DeepSORT Object Tracker | `YOLOv8 DeepSORT object tracking Python`          |
| 37 | Vehicle Tracking               | `vehicle tracking YOLO DeepSORT Python`           |
| 38 | Vehicle Counter                | `vehicle counting YOLO tracking Python project`   |
| 39 | People Counter                 | `people counting YOLO Python computer vision`     |
| 40 | Line Crossing Counter          | `YOLO line crossing object counter Python`        |
| 41 | Football Player Tracking       | `football player tracking YOLO ByteTrack Python`  |
| 42 | Basketball Player Tracking     | `basketball tracking YOLO computer vision Python` |
| 43 | Customer Tracking in Store     | `retail customer tracking YOLO DeepSORT`          |
| 44 | Traffic Flow Analytics         | `traffic analysis YOLO object tracking Python`    |
| 45 | Vehicle Speed Estimation       | `vehicle speed estimation YOLO Python project`    |

There is a full vehicle tracking/counting tutorial and a football-player YOLO + ByteTrack build on YouTube. ([YouTube][8])

---

# Phase 5 — Face AI

| #  | Project                    | YouTube search                                              |
| -- | -------------------------- | ----------------------------------------------------------- |
| 46 | Face Detection             | `deep face detection Python TensorFlow project`             |
| 47 | Face Recognition           | `deep facial recognition app Python deep learning`          |
| 48 | Face Attendance System     | `deep learning face recognition attendance Python`          |
| 49 | Facial Emotion Recognition | `facial emotion recognition CNN TensorFlow Python`          |
| 50 | Age Estimation             | `age estimation deep learning OpenCV Python project`        |
| 51 | Gender Classification      | `gender classification CNN computer vision Python`          |
| 52 | Face Anti-Spoofing         | `face anti spoofing deep learning Python project`           |
| 53 | Drowsiness Detection       | `deep drowsiness detection YOLO PyTorch Python`             |
| 54 | Head Pose Estimation       | `head pose estimation deep learning computer vision Python` |
| 55 | Gaze Estimation            | `gaze estimation deep learning Python computer vision`      |

## Strong exact course

Nicholas Renotte has a multi-part **Deep Facial Recognition App** project that goes from the paper/concept into code and data collection. ([YouTube][9])

For drowsiness detection, there are step-by-step real-time camera projects using transfer learning and YOLO/PyTorch-oriented workflows. ([YouTube][10])

---

# Phase 6 — Human Pose and Action Recognition

This is an important specialization.

You are no longer processing a single image only.

You start learning:

```text
Frame 1
   ↓
Frame 2
   ↓
Frame 3
   ↓
Temporal sequence
   ↓
Action
```

| #  | Project                    | YouTube search                                              |
| -- | -------------------------- | ----------------------------------------------------------- |
| 56 | Human Pose Estimation      | `human pose estimation deep learning Python project`        |
| 57 | Exercise Rep Counter       | `AI exercise counter pose estimation Python`                |
| 58 | Push-Up Counter            | `pushup counter pose detection Python computer vision`      |
| 59 | Squat Counter              | `squat counter pose estimation Python`                      |
| 60 | Posture Correction System  | `posture detection computer vision Python AI`               |
| 61 | Sign Language Recognition  | `sign language action recognition LSTM Python`              |
| 62 | Human Activity Recognition | `human activity recognition CNN LSTM video Python`          |
| 63 | Fall Detection             | `fall detection pose estimation deep learning Python`       |
| 64 | Violence Detection         | `violence detection video deep learning CNN LSTM Python`    |
| 65 | Lip Reading AI             | `deep learning lip reading Python project Nicholas Renotte` |

## You absolutely should build #61

Search:

> **Sign Language Detection using ACTION RECOGNITION with Python | LSTM Deep Learning Model**

The project uses keypoints and an LSTM-oriented action-recognition pipeline. ([YouTube][11])

For general video activity recognition, CNN + LSTM project tutorials are also available. ([YouTube][12])

And project #65:

> **Build a Deep Learning Model that can LIP READ using Python**

([YouTube][13])

This one is particularly good for you because it moves beyond basic image classification.

---

# Phase 7 — Image Segmentation

Now understand this difference:

### Classification

```text
Image → Dog
```

### Detection

```text
Image → Dog + bounding box
```

### Segmentation

```text
Image → exact dog pixels
```

| #  | Project                  | YouTube search                                             |
| -- | ------------------------ | ---------------------------------------------------------- |
| 66 | U-Net from Scratch       | `PyTorch image segmentation U-Net everything from scratch` |
| 67 | Car Segmentation         | `Carvana U-Net PyTorch segmentation project`               |
| 68 | Road Segmentation        | `road segmentation YOLO U-Net Python project`              |
| 69 | Brain Tumor Segmentation | `brain tumor segmentation U-Net PyTorch project`           |
| 70 | Lung Segmentation        | `lung segmentation U-Net deep learning Python`             |
| 71 | Polyp Segmentation       | `polyp segmentation U-Net PyTorch project`                 |
| 72 | Cell Nuclei Segmentation | `cell nuclei segmentation U-Net Python deep learning`      |
| 73 | Crop Segmentation        | `crop segmentation U-Net deep learning Python`             |
| 74 | Crack Segmentation       | `crack segmentation deep learning U-Net Python`            |
| 75 | Flood Water Segmentation | `flood segmentation satellite image U-Net Python`          |

## Exact tutorial I recommend

> **PyTorch Image Segmentation Tutorial with U-NET: everything from scratch baby**

It covers U-Net implementation, dataset setup, training, and supporting utilities using the Carvana segmentation dataset. ([YouTube][14])

For road segmentation, a custom YOLO segmentation project is also available. ([YouTube][15])

For brain MRI:

> `Brain Tumor Segmentation System Using PyTorch & UNet`

([YouTube][16])

---

# Phase 8 — Geospatial and Satellite Computer Vision

**Hashim, this phase is especially important for you.**

Because you already want to build **Epoch Earth** and have discussed satellite/geospatial systems.

| #  | Project                               | YouTube search                                              |
| -- | ------------------------------------- | ----------------------------------------------------------- |
| 76 | Satellite Land Cover Classification   | `satellite land cover classification deep learning PyTorch` |
| 77 | Satellite Image Segmentation          | `satellite image segmentation U-Net PyTorch Python`         |
| 78 | Road Extraction from Satellite Images | `road extraction satellite imagery U-Net deep learning`     |
| 79 | Building Detection                    | `building detection satellite images YOLO Python`           |
| 80 | Water Body Segmentation               | `water segmentation satellite imagery U-Net Python`         |
| 81 | Forest Detection                      | `forest classification satellite imagery deep learning`     |
| 82 | Deforestation Detection               | `deforestation detection satellite deep learning Python`    |
| 83 | Flood Mapping                         | `flood mapping satellite imagery deep learning Python`      |
| 84 | Crop Type Classification              | `crop classification satellite imagery CNN Python`          |
| 85 | Change Detection                      | `satellite change detection deep learning PyTorch project`  |

Satellite deep-learning collections include PyTorch/U-Net land-cover segmentation, road segmentation, and other remote-sensing pipelines. ([GitHub][17])

### My strong recommendation

When you reach Project #78, use:

```text
Input:
Sentinel-2 / aerial imagery

Model:
U-Net

Output:
Road segmentation mask
```

Then build:

```text
GeoTIFF
   ↓
Python preprocessing
   ↓
Image tiles
   ↓
U-Net
   ↓
Road mask
   ↓
Vectorization
   ↓
GeoJSON
   ↓
Mapbox
```

That is a **real Hashim-level project**, not another cat versus dog notebook.

---

# Phase 9 — OCR and Document Vision

| #  | Project                            | YouTube search                                           |
| -- | ---------------------------------- | -------------------------------------------------------- |
| 86 | Automatic Number Plate Recognition | `automatic number plate recognition YOLO EasyOCR Python` |
| 87 | Handwritten Digit OCR              | `CNN OCR PyTorch handwritten digits Python`              |
| 88 | Handwritten Text Recognition       | `handwritten text recognition deep learning Python CRNN` |
| 89 | Receipt OCR                        | `receipt OCR deep learning Python project`               |
| 90 | Invoice AI                         | `invoice extraction computer vision OCR Python project`  |
| 91 | ID Card Reader                     | `ID card OCR YOLO EasyOCR Python`                        |
| 92 | Meter Reading AI                   | `meter reading OCR YOLO Python computer vision`          |

A complete number-plate recognition tutorial using Python, YOLO, and EasyOCR is available from Computer Vision Engineer. ([YouTube][18])

For your portfolio, change it to:

> **Pakistan Number Plate Recognition System**

Pipeline:

```text
Camera
  ↓
YOLO plate detector
  ↓
Crop plate
  ↓
Perspective correction
  ↓
OCR
  ↓
Plate validation
  ↓
Database
  ↓
Vehicle history API
```

That is much more useful than copying the tutorial exactly.

---

# Phase 10 — Vision Transformers and Modern CV

Now enter modern computer vision.

| #   | Project                             | YouTube search                                             |
| --- | ----------------------------------- | ---------------------------------------------------------- |
| 93  | Vision Transformer Image Classifier | `Vision Transformer image classification PyTorch project`  |
| 94  | ViT from Scratch                    | `Vision Transformer from scratch PyTorch computer vision`  |
| 95  | CLIP Image Search Engine            | `CLIP semantic image search Python project`                |
| 96  | Zero-Shot Image Classification      | `CLIP zero shot image classification Python`               |
| 97  | SAM Image Segmentation App          | `Segment Anything SAM Python computer vision project`      |
| 98  | Image Caption Generator             | `image captioning CNN LSTM PyTorch Python project`         |
| 99  | Visual Question Answering System    | `visual question answering computer vision Python project` |
| 100 | Production Vision AI Platform       | `YOLO FastAPI Docker computer vision deployment project`   |

There are current project tutorials for ViT image classification and implementing ViT from scratch in PyTorch. ([YouTube][19])

---

# The 10 projects I most strongly recommend for you

Do **not** randomly choose projects.

Based on your goal of becoming a **computer vision specialist/researcher and eventually building a CV company**, my top 10 for you are:

| Priority | Project                             |
| -------- | ----------------------------------- |
| 🥇 1     | Satellite Road Segmentation         |
| 🥈 2     | Custom YOLO Object Detector         |
| 🥉 3     | YOLO + DeepSORT Tracking            |
| 4        | Pakistan Number Plate Recognition   |
| 5        | U-Net from Scratch                  |
| 6        | Human Action Recognition CNN + LSTM |
| 7        | Deep Facial Recognition from Paper  |
| 8        | Vision Transformer from Scratch     |
| 9        | Satellite Change Detection          |
| 10       | Production Vision AI Platform       |

---

# The exact order I want you to follow

```text
PROJECT 1–10
CNN
↓
Understand training loop

PROJECT 11–20
Transfer Learning
↓
Understand pretrained models

PROJECT 21–35
YOLO
↓
Object Detection

PROJECT 36–45
DeepSORT / ByteTrack
↓
Video Tracking

PROJECT 46–55
Face AI
↓
Embeddings and recognition

PROJECT 56–65
Pose + LSTM
↓
Temporal Computer Vision

PROJECT 66–75
U-Net
↓
Segmentation

PROJECT 76–85
Satellite Computer Vision
↓
Your specialization starts

PROJECT 86–92
OCR
↓
Multi-model CV pipelines

PROJECT 93–100
ViT + CLIP + SAM + Deployment
↓
Modern Computer Vision Engineer
```

## My honest recommendation for you

**Do not aim to “finish 100 YouTube projects.”**

Aim to do this:

```text
30 tutorial projects
+
30 rebuilt without tutorial
+
20 custom dataset projects
+
10 paper implementation projects
+
10 production projects
=
100 serious CV projects
```

For **every single project**, your GitHub repository should contain:

```text
project-name/
│
├── README.md
├── requirements.txt
├── configs/
├── data/
├── notebooks/
├── src/
│   ├── datasets/
│   ├── models/
│   ├── training/
│   ├── evaluation/
│   └── inference/
├── train.py
├── evaluate.py
├── inference.py
├── tests/
├── Dockerfile
└── results/
```

And your README must answer:

```text
1. What problem am I solving?
2. What is the dataset?
3. How did I preprocess data?
4. Which model did I use?
5. Why this model?
6. What is the loss function?
7. Which optimizer?
8. Which metrics?
9. What failed?
10. What did I improve?
11. How can the model be deployed?
```

**This is the road I would personally put you on:** first complete Projects **1–30**, but after #30, stop blindly following YouTube. From #31 onward, rebuild and modify. Your backend background already gives you an advantage; the missing muscle is model training, visual-data pipelines, experimentation, and CV reasoning.

[1]: https://www.youtube.com/watch?v=m9fH9OWn8YM&utm_source=chatgpt.com "Train Yolov8 object detection on a custom dataset | Step by ..."
[2]: https://www.youtube.com/watch?v=CtzfbUwrYGI&utm_source=chatgpt.com "Image Classification CNN in PyTorch"
[3]: https://www.youtube.com/watch?v=SWaYRyi0TTs&utm_source=chatgpt.com "Traffic Signs Classification Using Convolution Neural ..."
[4]: https://www.youtube.com/watch?v=jztwpsIzEGc&utm_source=chatgpt.com "Build a Deep CNN Image Classifier with ANY Images"
[5]: https://docs.ultralytics.com/tasks/detect?utm_source=chatgpt.com "Object Detection"
[6]: https://www.youtube.com/watch?v=N3adGK66myE&utm_source=chatgpt.com "Full YOLO and Object Detection Tutorial from Scratch"
[7]: https://www.youtube.com/watch?v=jIRRuGN0j5E&utm_source=chatgpt.com "Yolov8 object detection + deep sort object tracking | Computer ..."
[8]: https://www.youtube.com/watch?v=Z3uquMElyzI&utm_source=chatgpt.com "Real-Time Vehicle Tracking & Counting with YOLOv8 – Full ..."
[9]: https://www.youtube.com/playlist?list=PLgNJO2hghbmhHuhURAGbe6KWpiYZt0AMH&utm_source=chatgpt.com "Build a Facial Recognition App // Deep Learning Project // ..."
[10]: https://www.youtube.com/watch?v=qwUIFKi4V48&utm_source=chatgpt.com "Real-time Drowsiness Detection Tutorial | Transfer Learning ..."
[11]: https://www.youtube.com/watch?v=doDUihpj6ro&utm_source=chatgpt.com "Sign Language Detection using ACTION RECOGNITION with ..."
[12]: https://www.youtube.com/watch?v=QmtSkq3DYko&utm_source=chatgpt.com "Human Activity Recognition using TensorFlow (CNN + LSTM ..."
[13]: https://www.youtube.com/watch?v=uKyojQjbx4c&utm_source=chatgpt.com "Build a Deep Learning Model that can LIP READ using Python ..."
[14]: https://www.youtube.com/watch?v=IHq1t7NxS8k&utm_source=chatgpt.com "PyTorch Image Segmentation Tutorial with U-NET: everything ..."
[15]: https://www.youtube.com/watch?v=EYc3o39437w&utm_source=chatgpt.com "Road Segmentation Using YOLO11-Seg | Train Custom ..."
[16]: https://www.youtube.com/watch?v=uqlXV8xjBKk&utm_source=chatgpt.com "Advance Project 94: Brain Tumor Segmentation System Using ..."
[17]: https://github.com/lake-thomas/satellite-image-deep-learning?utm_source=chatgpt.com "lake-thomas/satellite-image-deep-learning"
[18]: https://m.youtube.com/watch?ref=morioh.com&v=73REqZM1Fy0&utm_source=chatgpt.com "Automatic number plate recognition with Python, Easyocr and ..."
[19]: https://www.youtube.com/watch?v=wr4vchc42Gw&utm_source=chatgpt.com "Image classification using Vision Transformer (ViT) with your ..."
