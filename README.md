# Cricket Shot Classification and Analysis using Machine Vision

This project uses computer vision and deep learning techniques to classify different types of **batting shots** in cricket. By analyzing video frames, the system detects and classifies shots like cover drives, pull shots, straight drives, etc., and compares them against top players' performances to assess **shot effectiveness**.

## Project Overview

The project consists of the following components:

- **Shot Detection**: Extracts frames from cricket videos and detects batsman activity using OpenCV.
- **Shot Classification**: Uses a Convolutional Neural Network (CNN) model to classify each shot frame.
- **Comparison Module**: Compares a player's shot quality to elite players' baseline data for performance analytics.
- **Visualization**: Annotates frames and generates reports with predicted shot types and comparison metrics.

## 🧠 Technologies Used

- Python 🐍
- OpenCV 🎥
- TensorFlow / Keras 🤖
- NumPy & Pandas 🧮
- Matplotlib 📊
- Jupyter Notebook 📒

## 📂 Project Structure

```
.
├── mv-project-final.ipynb       # Jupyter notebook with entire project pipeline
├── /models                      # Pre-trained models for classification
├── /dataset                    # Video and image datasets used
├── /output                     # Output videos and result CSVs
├── README.md                   # Project description and instructions
```

### Prerequisites

Install the necessary Python libraries:

```
pip install opencv-python tensorflow numpy pandas matplotlib
```

### Run the Project

1. Clone this repo:
   ```
   git clone https://github.com/your-username/cricket-shot-classifier.git
   cd cricket-shot-classifier
   ```

2. Launch the Jupyter notebook:
   ```
   jupyter notebook mv-project-final.ipynb
   ```

3. Run each cell to process the video, classify the shots, and generate analytics.


## 📈 Sample Results

- **Shot Types Detected**: Cover Drive, Pull Shot, Square Cut, Straight Drive
- **Player Comparison**: Matches player's shots with elite profiles (Virat Kohli, Steve Smith, etc.)
  

## 📊 Applications

- Cricket coaching and training
- Automated sports analytics
- Broadcasting enhancement with real-time annotations
- Player scouting and evaluation
