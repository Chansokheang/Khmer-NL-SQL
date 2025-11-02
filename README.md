# Khmer-NL-SQL

## Project Structure

```
khmer-nlsql/
├── checkpoints/          # Model checkpoints and saved states
├── configs/              # Configuration files
│   ├── model/           # Model architecture configurations
│   └── training/        # Training hyperparameters and settings
├── data/                # Data directories
│   ├── raw/            # Original, unprocessed data
│   ├── processed/      # Cleaned and preprocessed data
│   └── tokenized/      # Tokenized data ready for training
├── database/            # Database related files
│   ├── dataset/        # Database datasets
│   └── setup/          # Database setup scripts
├── evaluation/          # Evaluation scripts and metrics
├── experiments/         # Experiment tracking and results
├── logs/               # Training logs and tensorboard files
├── models/             # Model implementations
│   ├── encoders/       # Transformer encoder architectures
│   └── heads/          # Task-specific prediction heads
├── outputs/            # Model outputs and predictions
├── scripts/            # Utility and helper scripts
├── src/                # Source code
│   └── utils.py        # Utility functions
├── tests/              # Unit tests and test cases
├── nlsql.py            # Main NL-SQL conversion module
└── run.py              # Main execution script
```
