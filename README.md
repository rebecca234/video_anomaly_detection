# Video Anomaly Detection using Spatio-Temporal Convolutional Network (STCN)

## **Overview**

This project implements a video anomaly detection system using a Spatio-Temporal Convolutional Network (STCN). The model analyzes sequences of video frames to identify anomalies by learning spatio-temporal patterns. The project is implemented in Python using Jupyter Notebook, making it interactive and user-friendly.

---

## **Features**

- **Notebook-based Workflow**: All components of the project, including preprocessing, training, and evaluation, are implemented in a single Jupyter Notebook (`main.ipynb`).
- **Deep Learning Architecture**: The STCN model leverages 3D convolutions for spatio-temporal feature extraction.
- **Evaluation Metrics**: The project uses accuracy, precision, recall, F1-score, and ROC-AUC for evaluation.
- **Real-time Capability**: The notebook is designed to process and analyze new videos for anomalies.

---

## **Project Structure**

```
video-anomaly-detection/
├── main.ipynb            # Jupyter Notebook containing the entire workflow
├── README.md             # Project documentation
├── requirements.txt      # List of dependencies
└── sample_videos/        # (Optional) Folder for sample video files
```

---

## **Setup Instructions**

### **1. Prerequisites**

- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- Required libraries (see `requirements.txt`)

### **2. Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/video-anomaly-detection.git
   cd video-anomaly-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Add Videos:
    Create a new folder where the main.ipnby file is located and name it as videos
    
    Add the video files which you want to analyse.

### **3. Run the Notebook**

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open `main.ipynb` and follow the steps outlined in the notebook.

---

## **Usage**

### **Preprocessing**

- Extract frames from videos, resize them, and normalize pixel values.
- Group frames into sequences of fixed length (e.g., 16 frames per sequence).

### **Training**

- Train the STCN model on the preprocessed dataset using the notebook.
- Save the trained model for future use.

### **Evaluation**

- Use the evaluation section of the notebook to compute metrics like accuracy and ROC-AUC.

### **Real-Time Detection**

- Analyze new videos by loading the pre-trained model and processing sequences in real time.

---

## **Results**

- **STCN Performance**:
  - **Accuracy**: 98.42%
  - **Precision**: 97.80%
  - **Recall**: 95.69%
  - **F1-Score**: 96.73%
  - **ROC-AUC**: 0.975
- These results demonstrate the model's robustness and effectiveness in detecting video anomalies.

---

## **Future Work**

- **Dataset Expansion**: Include more diverse anomaly types.
- **Model Enhancement**: Integrate attention mechanisms to improve feature extraction.
- **Deployment**: Convert the notebook into a deployable web application or API.

---

## **Contributing**

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## **License**

This project is licensed under the MIT License. See the LICENSE file for details.

---

## **Acknowledgments**

- Dataset: [UCF-Large Crime Dataset](https://www.kaggle.com/code/parvishkakarapalli/data-analysis/input).
- Framework: Built using PyTorch.

For any queries, contact [(nrebeccaaishwarya@gmail.com))].

