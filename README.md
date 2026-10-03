# RAG-Based Hallucination Detection in Large Language Models

A research-oriented project focused on exploring hallucination detection in Large Language Models (LLMs) through Retrieval-Augmented Generation (RAG), claim analysis, citation verification, and document-based evaluation.

The project includes experimental Jupyter notebooks, evaluation results, metric comparisons, and supporting research resources.

## Project Overview

Large Language Models may produce responses containing unsupported claims, incorrect information, or unreliable citations.

This project explores different aspects of hallucination detection, including:

* Claim-level analysis
* Citation verification
* Document-based evaluation
* Retrieval-Augmented Generation
* Evaluation metric comparison

## Key Components

| Component                   | Description                                          |
| --------------------------- | ---------------------------------------------------- |
| Citation Analysis           | Notebook for exploring citation-related verification |
| Claim Analysis              | Notebook for claim-level analysis                    |
| Document Analysis           | Notebook for document-based experimentation          |
| RAG Hallucination Detection | Main experimental notebook                           |
| Metrics Comparison          | Visualization of evaluation metrics                  |
| Results                     | CSV-based experimental outputs                       |

## Project Structure

```text
Rag_hallucination-model/
│
├── data/
├── info/
│
├── notebook/
│   ├── citation.ipynb
│   ├── claim.ipynb
│   ├── document.ipynb
│   ├── rag_hallucination_detection (1).ipynb
│   ├── fig1_metrics_comparison.png
│   ├── metrics_summary.csv
│   └── results.csv
│
├── main.py
├── requirement.txt
├── pyproject.toml
├── uv.lock
├── README.md
└── .gitignore
```

## Technology Stack

* Python
* Jupyter Notebook
* Retrieval-Augmented Generation
* Natural Language Processing
* Pandas
* Data Visualization

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SanikaDeokar09/Rag_hallucination-model.git
```

### Navigate to the Project

```bash
cd Rag_hallucination-model
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate Environment (Windows)

```powershell
.\venv\Scripts\Activate.ps1
```

### Install Dependencies

```bash
pip install -r requirement.txt
```

### Run the Experiments

Open the `notebook/` directory in VS Code or Jupyter Notebook and execute the notebooks.

## Experimental Outputs

The repository includes:

* Evaluation result files
* Metric summary
* Metric comparison visualization
* Research notebooks

## Future Scope

* Improve automated hallucination detection
* Integrate evidence-based claim verification
* Evaluate detection performance using additional metrics
* Develop an interactive hallucination analysis interface
* Explore explainable AI techniques

## Author

**Sanika Deokar**

[GitHub Profile](https://github.com/SanikaDeokar09)

## Disclaimer

This project is intended for academic research and educational purposes. Third-party research materials remain subject to their respective copyright and licensing terms.
