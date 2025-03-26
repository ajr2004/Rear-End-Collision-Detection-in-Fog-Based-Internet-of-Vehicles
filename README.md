# 📌 Rear-End Collision Detection in Fog-Based Internet of Vehicles

## 📹 Demonstration Video
A demonstration of the dataset generation process using PTV Vissim under various fog conditions is available on YouTube. Watch the video here:

[![Dataset Generation Demo](https://img.youtube.com/vi/G0tXEq5pQ0A/0.jpg)](https://youtu.be/G0tXEq5pQ0A)

This video showcases:
- Simulated traffic under different fog intensities.
- The process of extracting vehicle movement data.
- Challenges in detecting rear-end collisions in low-visibility conditions.

## 📖 Overview
This project focuses on detecting rear-end collisions in foggy conditions using deep learning models trained on simulated traffic data.

## 📂 Repository Structure
```plaintext
📁 rear-end-collision-detection-in-fog-based-internet-of-vehicles
│── 📁 codes  # Preprocessing, training, and evaluation scripts
│── 📁 dataset  # Simulated traffic data under various fog conditions
│── 📁 demo  # Demonstration videos
│── 📁 models  # Pretrained models and checkpoints
│── 📄 README.md
```

## 📊 Dataset Generation
The dataset was created using:
- **PTV Vissim**: Simulating real-world traffic conditions.
- **OpenStreetMap Data**: Real-world road intersections were imported for accurate simulation.
- **Fog Simulation**: Different levels of fog were applied to observe the impact on vehicle behavior.

## 🏗 Model Architecture
- **Deep Recurrent Neural Network (DRNN) with BiLSTM**
- **Feature Extraction**: Speed, acceleration, distance between vehicles.
- **Training**: Tuned hyperparameters for optimal performance.
- **Evaluation Metrics**: MSE, RMSE, Precision, Recall.

## 🚀 Installation & Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo-name.git
   cd rear-end-collision-detection-in-fog-based-internet-of-vehicles
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the dataset preprocessing script:
   ```sh
   python preprocess.py
   ```
4. Train the model:
   ```sh
   python train.py
   ```
5. Evaluate the model:
   ```sh
   python evaluate.py
   ```

## 📌 Future Scope
- Enhancing model accuracy with more real-world data.
- Implementing real-time processing for IoV deployment.
- Exploring additional deep learning architectures.

---

🔗 **Watch the demo video**: [YouTube Link](https://youtu.be/G0tXEq5pQ0A)
