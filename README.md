Explainable Deep Learning Model for Medical Entity Recognition

Overview

This project focuses on **Medical Entity Recognition (MER)** using deep learning and explainable AI techniques. The system identifies important medical entities such as **diseases, medications, and symptoms** from unstructured clinical text.

In addition to accurate entity recognition, the model provides **interpretability** using explainability techniques like attention visualization and SHAP, making it more suitable for healthcare applications.


Objectives

* To extract meaningful medical entities from unstructured text
* To improve accuracy using transformer-based deep learning models
* To enhance transparency using explainable AI techniques
* To make AI systems more reliable for healthcare applications


Technologies Used

* Python
* PyTorch / TensorFlow
* Transformers (BERT Model)
* NumPy, Pandas
* SHAP (Explainable AI)
* Google Colab


Methodology

1. Data preprocessing and cleaning
2. Tokenization using transformer tokenizer
3. Contextual embedding using BERT model
4. Token classification using BIO tagging
5. Model training using AdamW optimizer
6. Evaluation using Precision, Recall, and F1-score
7. Explainability using attention visualization and SHAP

Project Structure

project/
│
├── notebook.ipynb        # Main implementation
├── dataset/              # Dataset files
├── model/                # Model-related code
├── requirements.txt      # Dependencies
└── README.md             # Project documentation

Results

The model achieved strong performance in identifying medical entities:

| Entity Type | Precision | Recall | F1 Score |
| ----------- | --------- | ------ | -------- |
| Disease     | 0.89      | 0.86   | 0.87     |
| Medication  | 0.91      | 0.88   | 0.89     |
| Symptom     | 0.85      | 0.83   | 0.84     |

Overall F1 Score: **0.87**


Explainability

The model includes explainability features:

* **Attention Visualization** to highlight important tokens
* **SHAP (Shapley Values)** to measure token contribution

Example:

> In the sentence *“The patient was diagnosed with pneumonia and prescribed amoxicillin”*,
> the model assigns higher importance to **pneumonia** and **amoxicillin**.


How to Run

1. Clone the repository:

git clone https://github.com/your-username/Explainable-Medical-Entity-Recognition.git

2. Install dependencies:

pip install -r requirements.txt

3. Run the notebook:

Open notebook.ipynb in Google Colab or Jupyter Notebook

Applications

* Clinical decision support systems
* Healthcare data analysis
* Medical research
* Automated medical documentation


Limitations

* Requires high computational resources
* Depends on dataset quality
* Limited handling of complex medical relationships

Future Work

* Use larger biomedical datasets
* Add relation extraction
* Improve explainability techniques
* Deploy in real-world healthcare systems

Contributors

* Swara Verma
* Ayush Rawat
* Satyam Patyal
* Srijan Chauhan

References

* Devlin et al., “BERT: Pre-training of Deep Bidirectional Transformers”
* Lundberg et al., “SHAP: Explainable AI”
* Vaswani et al., “Attention is All You Need”


We would like to thank our project guide and Chandigarh University for their support and guidance throughout this project.
