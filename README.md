# Named Entity Recognition (NER) Project

This project demonstrates a Named Entity Recognition (NER) system using a Support Vector Machine (SVM) classifier. The system identifies named entities in text, such as names of people and locations.

## Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ravindramohith/Named-Entity-Recognition.git
    cd Named-Entity-Recognition
     ```
2. **Install the required packages:**
     ```bash
     pip install -r requirements.txt
     ```

3. Install additional dependencies:
```bash
pip install gradio==3.48.0
pip install typing-extensions==4.5.0
```

## Usage
1. Run the Jupyter Notebook: Open the NER.ipynb notebook in Jupyter and run all cells to train the model and perform inference.

2. Inference Example: The notebook includes an example of how to use the trained model to annotate a sentence with named entities.

3. Gradio Interface: The notebook sets up a Gradio interface to interact with the NER model. You can enter a sentence, and the model will annotate each token as a named entity (1) or not (0).

4. Evaluation: The notebook also includes a section on evaluating the model's performance using precision, recall, and F1-score metrics.

5. Data Visualization: There are visualizations provided to understand the distribution of named entities in the dataset and the model's predictions.

6. Model Saving and Loading: Instructions on how to save the trained model and load it for future use are also included in the notebook.
