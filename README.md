# Hallmarks of Cancer Project

## Overview
This project is part of the **HINF 5016 Natural Language Processing & Health** coursework at Weill Cornell Medicine. The primary objective is to explore the **Hallmarks of Cancer** using Natural Language Processing (NLP) techniques.

The project is inspired by [Hallmarks-of-Cancer](https://github.com/sb895/Hallmarks-of-Cancer) and leverages data from the [BLUE Benchmark dataset](https://github.com/ncbi-nlp/BLUE_Benchmark/releases/tag/0.1), provided by course instructor **Yifan Peng**.

## Data Source
The dataset used in this project comes from the **BLUE Benchmark**, a biomedical NLP evaluation suite. The data is publicly available at:
- **Dataset repository**: [BLUE Benchmark](https://github.com/ncbi-nlp/BLUE_Benchmark/releases/tag/0.1)
- **Dataset description**: [BLUE Benchmark Overview](https://github.com/ncbi-nlp/BLUE_Benchmark?tab=readme-ov-file)

## Objectives
- Utilize **Natural Language Processing (NLP)** techniques to analyze text data related to the hallmarks of cancer.
- Implement various **machine learning and deep learning models** to extract insights from biomedical literature.
- Evaluate model performance on **biomedical NLP tasks** such as Named Entity Recognition (NER), Relation Extraction (RE), and Document Classification.

## Methodology
1. **Data Preprocessing**: Tokenization, cleaning, and transformation of biomedical texts.
2. **Feature Engineering**: Word embeddings, contextualized representations (e.g., BioBERT, SciBERT).
3. **Model Selection**: Use classical ML models (SVM, Random Forest) and deep learning models (Transformer-based architectures).
4. **Evaluation Metrics**: F1-score, precision, recall, and other relevant benchmarks.
5. **Analysis & Interpretation**: Understanding the extracted patterns and their significance in cancer research.

## Implementation
- **Programming Language**: Python
- **Libraries & Tools**:
  - `transformers` (Hugging Face)
  - `scikit-learn`
  - `tensorflow` / `pytorch`
  - `spaCy`
  - `NLTK`
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`

## Expected Outcomes
- A comprehensive analysis of the **Hallmarks of Cancer** through **biomedical NLP**.
- Comparative performance results of different NLP models on cancer-related texts.
- Insights that can support further research in cancer genomics and treatment.

## Repository Structure
```
├── data/                 # Contains preprocessed datasets
├── notebooks/            # Jupyter notebooks for experiments
├── src/                  # Source code for model training & evaluation
├── results/              # Model evaluation outputs & visualizations
├── README.md             # Project documentation
└── requirements.txt      # Required dependencies
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Hallmarks-of-Cancer-Project.git
   cd Hallmarks-of-Cancer-Project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run experiments:
   ```bash
   python src/train_model.py --config configs/default.yaml
   ```

## References
- **Hallmarks of Cancer GitHub**: [sb895/Hallmarks-of-Cancer](https://github.com/sb895/Hallmarks-of-Cancer)
- **BLUE Benchmark**: [ncbi-nlp/BLUE_Benchmark](https://github.com/ncbi-nlp/BLUE_Benchmark)

## Contributors
- [Your Name] - [Your Email]
- Course Instructor: **Yifan Peng**, Weill Cornell Medicine

## License
This project is for educational and research purposes only.
