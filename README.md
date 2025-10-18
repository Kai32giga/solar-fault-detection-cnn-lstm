
# Solar Panel Fault Detection using Deep Learning

## Overview
This project focuses on developing a **deep learning–based fault detection system** for solar panels using a hybrid **CNN–LSTM model**. 
It identifies and classifies faults or dust accumulation from image and sensor data, ensuring real-time monitoring and improved solar system efficiency.

## Objectives
- Automate detection of solar panel faults and dust accumulation.
- Improve efficiency and reliability of solar power generation.
- Utilize image and sensor data for accurate fault classification.

## Dataset
You can use (or reference) publicly available datasets for solar panel fault or dust detection.

### Example Sources
- [Solar Panel Surface Dust Dataset (Kaggle)](https://www.kaggle.com/datasets/sumithbhongale/solar-panel-images-dust-detection)
- [Solar Panel Fault Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/sahityakmr/solar-panel-fault-detection)

### Example Structure
```
/dataset
    ├── images/
    │     ├── normal/
    │     ├── fault/
    └── sensors.csv  (temperature, voltage, current, irradiance)
```

## Tools & Libraries
- **Programming:** Python
- **Deep Learning:** TensorFlow, Keras
- **Data Handling:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Cloud Deployment:** AWS EC2, S3, Lambda
- **Model Types:** CNN, LSTM

## Approach
1. **Data Preprocessing**
   - Image resizing, normalization, and augmentation.
   - Sensor data cleaning and scaling.
2. **Model Architecture**
   - CNN for feature extraction.
   - LSTM for temporal pattern recognition.
3. **Training & Evaluation**
   - 80/20 train-test split.
   - Optimized using Adam optimizer and categorical cross-entropy loss.
4. **Performance Metrics**
   - Accuracy: **~95%**
   - Precision, Recall, F1-Score, Confusion Matrix

## Results
- Achieved **95% classification accuracy** in detecting faulty or dusty panels.
- Improved fault localization and detection reliability.
- Reduced false positives through CNN–LSTM hybridization.

## How to Run
```bash
# Clone this repository
git clone https://github.com/pratikjadhav/solar-panel-fault-detection.git
cd solar-panel-fault-detection

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook solar_panel_fault_detection.ipynb
```

## Future Work
- Integrate IoT sensors for live monitoring.
- Deploy as a web dashboard using Streamlit or Flask.
- Expand dataset for multi-fault detection.

## Author
**Pratik Jadhav**  
Master’s Student, Data Science  
📫 [LinkedIn](https://www.linkedin.com/in/pratik-jadhav5343727)  
📦 [GitHub](https://github.com/pratikjadhav)
