# 🎮 ML-PACMAN: Gesture-Controlled Pac-Man

ML-PACMAN is an interactive, browser-based adaptation of the classic Pac-Man game that leverages **AI-powered hand gesture recognition** for control. Instead of using a keyboard, players navigate the game using real-time hand movements detected via webcam.

A fine-tuned **MobileNet model** powers gesture recognition, while an integrated dashboard provides real-time insights into model performance and gameplay metrics.

---

## ✨ Features

- 🖐️ **Custom Gesture Recognition**  
  Train and fine-tune a MobileNet model to map hand gestures to game controls.

- 🎥 **Real-Time Interaction**  
  Use your webcam to control Pac-Man with intuitive hand movements.

- 📊 **Performance Metrics Dashboard**  
  Monitor:
  - Confidence scores  
  - Loss curves  
  - Model predictions  

- 📈 **Data Visualization**  
  Explore datasets using:
  - UMAP projections  
  - Real-time inference feedback  

- 🕹️ **Classic Gameplay**  
  Experience the original Pac-Man mechanics with an AI-driven twist.

---

## 🎮 Demo

Check out the demo videos:

- ▶️ https://drive.google.com/file/d/1fq-5OsQW3Xrk3sSSQKDDa_rUDsokO9cw/view?usp=drive_link  
- ▶️ https://drive.google.com/file/d/1ea_ewyBiWCiTkgAGFawg1BiHHMFN2UX2/view?usp=drive_link  

---

## 🧠 How It Works

1. Webcam captures real-time hand gestures  
2. TensorFlow.js runs a fine-tuned MobileNet model in-browser  
3. Model predicts gesture direction  
4. Predictions are mapped to Pac-Man controls  
5. Dashboard visualizes model confidence and performance  

---

## 🔧 Technologies Used

- ⚛️ **React** — Interactive frontend UI  
- 🤖 **TensorFlow.js** — In-browser ML inference  
- 🧠 **MobileNet** — Pretrained model fine-tuned for gesture recognition  
- 📊 **D3.js** — Data visualization (UMAP, metrics, charts)  
- 🎥 **WebRTC** — Real-time webcam access  

---

## 🚀 Installation

Follow these steps to run ML-PACMAN locally:

### 1. Clone the repository
git clone https://github.com/GayathriBalaji98/VisualizationWithAIPacMan.git
cd VisualizationWithAIPacMan

### 2. Install dependancies
npm install

### 3. Start the development server
npm start

### 4. Play the game
Open your browser and start controlling Pac-Man!
