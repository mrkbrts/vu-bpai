# Analysis of Traditional NER and Generative LLMs for PICO Annotation in Medical Research 🔬
Bachelor Project Artificial Intelligence @ Vrije Universiteit Amsterdam 🎓 

![Poster](https://github.com/mrkbrts/vu-bpai/blob/main/M%20Bartos%20-%20BPAI%20Poster.png)

### About the Research Paper 📑
**Abstract:** This study compares the performance of Bidirectional Long Short-Term Memory (BiLSTM) networks and Generative Pre-trained Transformers (GPT) for extracting and annotating PICO (Population, Intervention, Comparison, Outcome) elements from medical research papers. Using the EBM-NLP dataset and a secondary dataset of full-length medical papers, the BiLSTM-CRF model was trained on tokenized text sequences, while the GPT-4o model utilized prompt engineering. 

**Results:** Results indicate that BiLSTM-CRF models excel at token-level annotation with a weighted F1-score of 0.76, whereas GPT-4o achieves a better recall of 0.89 and an F1-score of 0.82 at the abstract level.

**Conclusion:** The findings suggest that while BiLSTM-CRF offers superior explainability and token-level precision, GPT-4o provides greater flexibility and contextual understanding.

**Future Work:** Future research should explore hybrid models and validate findings on a larger dataset of full-length papers.

### About the Code 👨‍💻
The repository is organized as follows:

- **code/:** Includes the codebase for the experiments.
  - **main-experiment/:** Code and generated data for the primary experiment comparing NLP models.
  - **secondary-experiment/:** Code and generated data for the secondary experiment on full-length papers.
    - **full-length-papers/:** The manually annotated data consiting of 3 medical papers annotated in their full length.
- **Comparative Comparison of Traditional NER and Generative Large Language Models for PICO Extraction in Medical Research - M Bartos - Thesis.pdf:** Full text of the research paper.
- **M Bartos - BPAI Poster.png:** Scientific poster summarizing key findings.
   
### EBM-NLP Dataset 💽
The dataset used for the main experiment can be downloaded from [here](https://github.com/bepnye/EBM-NLP/tree/master).
