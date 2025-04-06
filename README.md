# Smart Driving Assist System

> YOLOv8 기반 보행자 및 차선 탐지 + 실시간 음성 알림 + 상황 요약 시스템
A real-time pedestrian and lane detection system using YOLOv8.  
The system provides audio alerts and generates contextual summaries based on the current road environment using the OpenAI API.

## Project Overview

This project implements a lightweight, real-time driving assist system that:
- Detects pedestrians using an object detection model (YOLOv8)
- Identifies lane boundaries using both traditional and deep learning-based methods
- Provides TTS-based audio alerts for critical events (e.g., pedestrian detected, lane departure)
- Generates natural language summaries of the current driving context via ChatGPT

## Features

- Pedestrian detection with YOLOv8
- Lane detection using Canny + Hough transform or segmentation
- Audio feedback using TTS (pyttsx3 or gTTS)
- Contextual summarization with ChatGPT API

## Datasets

| Task                | Dataset                    | Source |
|---------------------|-----------------------------|--------|
| Pedestrian Detection | INRIA / Roboflow            | https://www.kaggle.com/datasets/andrewmvd/inria-person-object-detection |
| Lane Detection       | TuSimple / CULane           | https://github.com/TuSimple/tusimple-benchmark |

## Tech Stack

- Python 3.x
- YOLOv8 (Ultralytics)
- OpenCV
- pyttsx3 / gTTS
- OpenAI ChatGPT API

## Future Work

- Integrate depth estimation for pedestrian distance measurement
- Visual driver dashboard with status indicators
- Deploy as a Streamlit or Flask-based application


**Soyoung Park**  
🔗 GitHub: [@soyoungpark-tech](https://github.com/soyoungpark-tech)  
📫 Email: your@email.com  
📝 Blog (Project in Progress): [[Add link to your blog post here]](https://blog.naver.com/thdud4961)

