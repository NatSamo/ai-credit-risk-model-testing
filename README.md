# AI Model Testing & Validation – Credit Risk Case Study
AI QA portfolio project focused on model validation, metrics evaluation, bias analysis, robustness and monitoring in credit risk.

## Dataset

We use UCI Credit Card Default dataset.

Target variable: default.payment.next.month (1 = default, 0 = no default)

Initial validation goals:
- Check class imbalance
- Validate data types
- Identify missing values

Repository structure:
ai-credit-risk-model-testing/
│
├── data/ # Dataset download instructions (raw data not stored)
│ └── README.md
│
├── notebooks/ # Jupyter notebooks for model testing workflow
│ └── README.md
│
├── results/ # Exported metrics, plots and evaluation outputs
│
├── test_strategy.md # AI QA validation approach and testing scope
├── metrics_evaluation.md # Metrics analysis and threshold considerations
├── bias_fairness.md # Subgroup analysis and fairness assessment
├── robustness_metamorphic.md # Robustness testing and metamorphic relations
├── monitoring_plan.md # Production monitoring and drift strategy
│
├── requirements.txt # Project dependencies
├── .gitignore
└── README.md
