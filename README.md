# MotionTrack_Running_AI
AI-powered running analysis using YOLO11 Pose to detect body movement, foot strikes, cadence, knee angles, gait symmetry, and visualize running metrics through an analysis dashboard.
# 🏃 MotionTrack Running AI

An AI-powered running analysis system that uses **YOLO11 Pose** to analyze running movements from video and transform pose data into meaningful running metrics.

## 🎥 Demo
<img width="1584" height="672" alt="Image" src="https://github.com/user-attachments/assets/12d695bc-1980-4fb4-bf3e-2fc929d6536a" />
Watch the project demonstration on Aparat:

[▶️ Watch the Demo Video](https://www.aparat.com/v/fsjfpch)

## 📊 Features

* **Pose Estimation** using YOLO11 Pose
* **Foot Strike Detection**
* **Cadence Analysis**
* **Knee Angle Analysis**
* **Left/Right Gait Symmetry**
* Running movement visualization
* Analysis charts and metrics
* Video-based running analysis dashboard

## 🧠 How It Works

The system processes a running video using **YOLO11 Pose** to detect human body keypoints.

The extracted pose data is then analyzed to identify running events and calculate movement-related metrics such as cadence, knee angles, foot strikes, and gait symmetry.

The results are presented through an analysis dashboard for easier interpretation of the running data.

## 🛠️ Technologies

* Python
* YOLO11 Pose
* Ultralytics
* OpenCV
* NumPy
* Pandas
* Data Visualization

## 📁 Project Workflow

```text
Running Video
      ↓
YOLO11 Pose Estimation
      ↓
Body Keypoint Extraction
      ↓
Motion Analysis
      ↓
Running Metrics
      ↓
Analysis Dashboard
```

## 📈 Example Metrics

The current project analyzes metrics including:

| Metric             | Description                                      |
| ------------------ | ------------------------------------------------ |
| Cadence            | Estimated running steps per minute               |
| Foot Strike        | Detected left and right foot-strike events       |
| Knee Angle         | Knee joint angle during running                  |
| Gait Symmetry      | Comparison of left and right movement            |
| Pose Visualization | Visual representation of detected body keypoints |

## 🎯 Project Goal

The goal of MotionTrack Running AI is to demonstrate how **Computer Vision and Pose Estimation** can be used to transform raw video into interpretable movement and running metrics.

This project combines **Computer Vision, Pose Estimation, Video Processing, Data Analysis, and Dashboard Development** in a single workflow.

## 👩‍💻 Author

**Maryam Hekmat**

AI / Machine Learning / Computer Vision

🌐 Website: [maryamhekmatai.com](https://maryamhekmatai.com)

🔗 GitHub: [Maryam-hekmat](https://github.com/Maryam-hekmat)
