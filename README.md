Automated Diagnosis of Brain Pathologies Using Deep Learning and CT Images

This project leverages deep learning models for the automated diagnosis of brain pathologies, including aneurysms, tumors, and cancer, using CT scan images. The primary objective is to develop a robust and accurate tool to assist healthcare professionals in diagnosing critical brain conditions, ultimately improving patient outcomes.

Dataset

The dataset for this project is available on Kaggle: CT Augmented Dataset for GSSOC
This dataset contains labeled CT images categorized into three classes: aneurysm, cancer, and tumor.

Project Structure

Data Collection and Preprocessing: Images are resized, normalized, and augmented to ensure uniformity and enhance model generalization.
Model Implementation: Three pre-trained models (VGG16, ResNet50, EfficientNetB7) were fine-tuned and evaluated on the dataset.
Evaluation Metrics: Performance was assessed using metrics such as accuracy, precision, recall, and F1-score, as well as confusion matrices.

Installation

git clone https://github.com/Jeevaranjani/Deep-learning-project-Automated-Diagnosis-of-Brain-Pathologies-Using-Deep-Learning-and-CT-Images
cd Deep-learning-project-Automated-Diagnosis-of-Brain-Pathologies-Using-Deep-Learning-and-CT-Images
pip install -r requirements.txt

Usage

Data Preparation: Ensure that the dataset is downloaded from the Kaggle link above and placed in the specified folder.
Training Models: Run the scripts to train VGG16, ResNet50, and EfficientNetB7 models. Each script trains the model, evaluates its performance, and outputs relevant metrics and confusion matrices.

Results

VGG16: Achieved ~49% accuracy on the test set, indicating limitations in handling complex classifications.
ResNet50: Achieved high accuracy of ~98%, with robust generalization across classes.
EfficientNetB7: Also demonstrated high accuracy of ~97%, showing strong classification performance.

Future Work

Hybrid Model Development: Combine the strengths of ResNet and EfficientNet with VGG16 to enhance classification accuracy.
Deployment: Integrate the model into clinical software for real-time diagnostics.
Explainability: Implement XAI techniques to visualize model predictions for better interpretability.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

License
This project is licensed under the MIT License.
