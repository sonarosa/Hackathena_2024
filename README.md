# 🚗 Drive.AI  
**AI-Powered Driving Learning Assistance**  
🏆 **Winner – Theme: Road Safety** at **Hackathena 2024**, Jyothi Engineering College, Cheruthuruthy  

---

## 📜 Overview
Drive.AI is an **AI-powered driver learning assistance system** designed to enhance road safety through **real-time object detection**, **context-aware analysis**, and **instant voice feedback**.  
The system combines **YOLOv5**, **OpenAI's language capabilities**, and **Google's Text-to-Speech** to create an intelligent co-pilot that helps drivers make safer decisions while on the road.  

Our project was developed during **Hackathena 2024**, where it was awarded **Winner in the Road Safety category** for its innovative approach to preventing accidents and improving driver awareness.

---

## 🎯 Key Features

### 1️⃣ Object Detection & Analysis
- Detects and analyzes **pedestrians crossing** in real time.
- Identifies **nearby vehicles** such as cars, motorcycles, and trucks.
- Recognizes **animals crossing** using models trained with **Roboflow** datasets.
- Works in **diverse lighting conditions** and **urban/rural environments**.

### 2️⃣ YOLOv5-Powered Vision
- Utilizes the **YOLO (You Only Look Once) v5** model for **fast and accurate** object detection and classification.
- Generates a **JSON output** containing all detected objects with their confidence scores and classifications.

### 3️⃣ AI-Powered Response Generation
- Parses YOLO’s JSON output to extract relevant object information.
- Uses **OpenAI's API** to generate context-aware, instructional responses (e.g., *"Slow down, pedestrian ahead on the left"*).
- Dynamic prompt creation for generating **clear and actionable** driving instructions.

### 4️⃣ Real-Time Voice Instructions
- Integrates **Google's Text-to-Speech (TTS)** to instantly convert AI-generated responses into **natural-sounding voice guidance**.
- Provides **real-time audio alerts** directly to the driver, ensuring minimal distraction while driving.

---

## ⚙️ How It Works
1. **Camera Feed** → Captures the driving environment in real time.
2. **YOLOv5 Detection** → Processes frames to detect and classify objects.
3. **JSON Data Parsing** → Extracts object details like type, position, and proximity.
4. **OpenAI API** → Generates safety instructions based on detected objects.
5. **Google TTS** → Converts instructions into voice guidance for immediate driver action.

---

## 🏆 Hackathon Achievement
- **Event:** Hackathena 2024  
- **Venue:** Jyothi Engineering College, Cheruthuruthy  
- **Theme:** Road Safety  
- **Award:** **Winner – Road Safety Category** 🥇  
- Recognized for **innovative integration of AI and computer vision** to proactively enhance road safety and prevent potential accidents.

---

## 🛠️ Tech Stack
- **Object Detection:** YOLOv5  
- **Data Annotation & Training:** Roboflow  
- **Response Generation:** OpenAI API  
- **Voice Output:** Google Text-to-Speech API  
- **Backend:** Python (Flask)  
- **Deployment:** Local/Edge device processing for minimal latency

---

## 🚀 Future Improvements
- GPS integration for **location-aware safety instructions**.
- Edge AI optimization for **low-power embedded devices**.
- Multilingual voice guidance for broader accessibility.
- Integration with AR HUDs for **visual driving cues**.

---


