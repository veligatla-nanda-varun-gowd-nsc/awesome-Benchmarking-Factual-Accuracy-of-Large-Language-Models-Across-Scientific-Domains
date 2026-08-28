# Domain Datasets & Factual Benchmarks

This directory houses the foundational datasets utilized to systematically verify the accuracy boundaries of Large Language Models across specialized scientific domains.

## 📌 Verified Datasets

*   **PubMedQA (Biomedical Question Answering)**
    *   **Source:** National Institutes of Health (NIH) / EMNLP
    *   **Description:** A specialized biomedical dataset collected from authentic PubMed abstracts requiring models to solve research queries with yes/no/maybe choices using context paragraphs.
    *   **Application:** Structural medical accuracy and factual reasoning validation.
    *   **Official Link:** [PubMedQA Portal](https://pubmedqa.github.io/)
    *   **Code Hub:** [pubmedqa/pubmedqa on GitHub](https://github.com/pubmedqa/pubmedqa)

*   **SciQ Dataset (Science Exam Benchmarks)**
    *   **Source:** Allen Institute for Artificial Intelligence (AI2)
    *   **Description:** Consists of 13,679 crowdsourced science exam questions across Physics, Chemistry, and Biology in multiple-choice layouts including baseline evidence documentation.
    *   **Application:** Benchmarks core scientific information retrieval limits.
    *   **Official Link:** [AllenAI SciQ Download](https://allenai.org/data/sciq)
    *   **Code Hub:** [huggingface/lighteval on GitHub](https://github.com)

*   **MMLU (Massive Multitask Language Understanding) - Science Subsets**
    *   **Source:** UC Berkeley
    *   **Description:** Advanced professional multi-task assessment blocks covering specific technical modules like College Chemistry, College Physics, and Clinical Medicine.
    *   **Application:** Measures abstract knowledge depth and technical parameter retention metrics.
    *   **Code Hub:** [hendrycks/test on GitHub](https://github.com)
