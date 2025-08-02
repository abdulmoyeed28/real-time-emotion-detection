# real-time-emotion-detection
Real-time emotion detection system using CNNs to classify facial expressions into seven emotions (Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral) via webcam feed. Built with Python, Keras, and OpenCV, it leverages the FER-2013 dataset for accurate and efficient recognition.


## 🔍 Features
- Real-time webcam emotion detection
- Pretrained model using the FER2013 dataset
- Simple UI with live emotion prediction
- Easy to set up and run locally

## 🧠 Model Details
- CNN trained on FER2013 dataset
- Input: 48x48 grayscale facial images
- Output: Emotion classification (7 classes)

## 📁 Project Structure

```bash
Real-Time-Emotion-Detection/
├── Dataset/                 
├── fer.h5                  # Trained model
├── fer.json                # Model architecture
├── Emotion recognition__.ipynb
├── VideoTester.py          # Real-time webcam emotion detector
├── requirements.txt
├── .gitignore
```

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/abdulmoyeed28/real-time-emotion-detection.git
cd real-time-emotion-detection
```

## 2. Install Dependencies
pip install -r requirements.txt

## 3. Download Dataset (Manual Step)
👉 Please download the FER2013 dataset manually from:  
https://www.kaggle.com/datasets/msambare/fer2013  
🔽 Then place the extracted files into the `Dataset/` folder.

## 4. Run the Project
python VideoTester.py
