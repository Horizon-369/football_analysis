# Football Analysis Project

## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using **YOLO**, one of the best AI object detection models available. We will also train the model to improve its performance. Additionally, we will assign players to teams based on the colors of their t-shirts using **Kmeans** for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match.
We will use **optical flow** to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement **perspective transformation** to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered.
This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

---

## Screenshot
<img width="875" alt="football analysis" src="https://github.com/user-attachments/assets/addd2b2c-9609-443b-b95c-87335c766a4f" />

---

## Modules Used
The following modules are used in this project:

- **YOLO**: AI object detection model for detecting players, referees, and footballs.
- **Kmeans**: Pixel segmentation and clustering to detect t-shirt colors and assign players to teams.
- **Optical Flow**: Measures camera movement between frames.
- **Perspective Transformation**: Represents scene depth and perspective to measure player movement in meters.
- **Speed and Distance Calculation**: Calculates player speed and distance covered during the match.

---

## Trained Models
- [Trained YOLO v11](https://drive.google.com/file/d/1qmQ4-if3LWij9dlo1GosYZsAsqUn896M/view?usp=sharing)

---

## Sample Videos
- [Sample input video](https://drive.google.com/file/d/1EdQDkZd0iPKWrXE1kiwTQ95ssg-u_o4I/view)

---

## Requirements
To run this project, you need to have the following requirements installed:

- **Python 3.x**
- **ultralytics** (for YOLO)
- **supervision** (for video processing and analysis)
- **OpenCV** (for image and video processing)
- **NumPy** (for numerical computations)
- **Matplotlib** (for visualization)
- **Pandas** (for data analysis and reporting)

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/football-analysis-project.git
   cd football-analysis-project
