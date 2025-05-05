{{ cookiecutter.project_slug }}/
├── data/
│   ├── raw/                # Original, immutable data dumps
│   ├── interim/            # Intermediate processed data
│   └── processed/          # Final data sets for modeling
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   └── 02_model_training.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data/               # Data loading, cleaning, preprocessing
│   ├── features/           # Feature engineering steps
│   ├── models/             # Model training and evaluation
│   └── visualization/      # Custom plots and charts
│
├── reports/
│   └── figures/            # Generated visualizations
│
├── configs/
│   └── config.yaml         # Parameters for pipeline stages
│
├── tests/
│   └── test_basic.py       # Basic tests for modules
│
├── .gitignore
├── README.md
├── environment.yml        # Conda environment
├── requirements.txt       # Pip environment
├── setup.py               # Installable src/
└── pyproject.toml         # Optional: Poetry or modern build systems