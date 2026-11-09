## Project Overview

This repository contains the **AI Ethics, Governance and Legal Compliance Assessment** of **SecureFinance Africa**, a fictional AI-powered financial system.

The project evaluates the ethical, technical, governance, fairness and regulatory implications of deploying AI in financial services. It examines potential risks associated with automated financial decision-making and proposes mitigation measures aligned with recognised AI governance and data protection frameworks.

## Repository Contents

| File | Description |
|---|---|
| `SecureFinance_Governance_Assessment.ipynb` | Google Colab notebook containing the Python code, synthetic data generation, model development, fairness evaluation and supporting analysis. |
| `SecureFinance_Governance_Report.pdf` | Complete assessment report covering ethical risks, governance frameworks, legal compliance, fairness findings, risk assessment and recommendations. |

```text
.
├── SecureFinance_Governance_Assessment.ipynb
├── SecureFinance_Governance_Report.pdf
└── README.md
```

## Assessment Scope

The assessment covers:

- **AI Ethics:** Transparency, accountability, privacy, explainability and human oversight.
- **AI Governance:** Risk management and alignment with the NIST AI Risk Management Framework.
- **Legal Compliance:** Relevant requirements under Nigeria's Data Protection Act 2023, the NDPC General Application and Implementation Directive 2025, and the EU AI Act where applicable.
- **Algorithmic Fairness:** Evaluation of potential disparities across demographic and geographical groups.
- **Risk Management:** Identification, assessment and mitigation of AI-related risks.
- **Deployment Readiness:** Recommendations for responsible and controlled AI deployment.

## Technical Implementation

The accompanying Google Colab notebook provides the reproducible computational analysis supporting the assessment.

The analysis includes:

- Synthetic dataset generation
- Machine learning model development and evaluation
- Classification performance metrics
- Group-based fairness evaluation
- False positive rate and prediction-rate comparisons
- Feature importance and proxy analysis
- Fairness mitigation experiments
- Supporting statistical analysis and visualisations

The report documents the methodology, results, limitations and interpretation of the experiments.

## How to Run the Notebook

1. Open the `.ipynb` notebook using [Google Colab](https://colab.research.google.com/).
2. Select **Runtime → Run all**.
3. Allow the notebook to install or import the required dependencies.
4. Execute the cells sequentially.
5. Review the generated results, evaluation metrics and visualisations.

> For reproducibility, use the random seed and experimental settings specified in the notebook.

## Important Note on the Dataset

The assessment uses **synthetic data** for its experimental fairness analysis. The results are intended to demonstrate potential algorithmic risks and evaluate mitigation approaches. They should **not** be interpreted as findings from real SecureFinance customers or actual financial transactions.

## Key Assessment Considerations

The assessment emphasises that achieving acceptable overall model performance does not necessarily guarantee fairness across different population groups.

It therefore examines group-level disparities, the possible influence of proxy variables, and the limitations of individual mitigation approaches. Proposed combined mitigation strategies should be experimentally validated before being treated as demonstrated improvements.

## Author

**Asim Shayan Khan**

AI-Driven Cybersecurity and Digital Forensics Fellowship
