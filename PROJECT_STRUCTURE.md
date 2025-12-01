# SpaceGuard - Project Structure

```
SpaceGuard/
│
├── src/                    # Source code
│   ├── __init__.py
│   └── data_utils.py      # Data processing utilities
│
├── scripts/               # Training & evaluation scripts
│   ├── train.py
│   ├── train_improved.py
│   ├── train_optimized.py
│   ├── train_high_precision.py
│   ├── train_high_performance.py
│   ├── predict.py
│   ├── evaluate_improvements.py
│   ├── evaluate_precision.py
│   ├── visualize.py
│   ├── augment_data.py
│   ├── monitor_training.py
│   ├── performance_analysis.py
│   ├── fix_detection_issues.py
│   ├── check_map.py
│   └── create_proper_confusion_matrix.py
│
├── configs/               # Configuration files
│   ├── config.yaml
│   ├── config_improved.yaml
│   ├── config_high_precision.yaml
│   ├── environment.yml
│   ├── yolo_params.yaml
│   ├── yolo_params_augmented.yaml
│   └── classes.txt
│
├── docs/                  # Documentation
│   ├── README.md
│   ├── DOWNLOAD_FEATURES.md
│   ├── WEBCAM_SETUP.md
│   ├── WEBCAM_STATUS.md
│   ├── WEBCAM_IMPLEMENTATION_SUMMARY.md
│   ├── PERFORMANCE_SUMMARY.md
│   ├── PRECISION_OPTIMIZATION_README.md
│   ├── improvement_report.md
│   ├── performance_report.md
│   ├── precision_report.md
│   └── test_report.md
│
├── models/                # Trained models (gitignored)
│
├── data/                  # Dataset (gitignored)
│
├── notebooks/            # Jupyter notebooks for experiments
│
├── app.py                # Streamlit web application
├── setup.py              # Setup script
├── setup_environment.py  # Environment setup
├── quick_start.py        # Quick start script
├── quick_optimize.py     # Quick optimization
├── quick_precision_boost.py
├── simple_precision_boost.py
├── test_webcam.py        # Webcam testing
├── requirements.txt      # Python dependencies
└── .gitignore           # Git ignore file

```

## Folder Descriptions

- **src/**: Core source code and utility modules
- **scripts/**: All training, evaluation, and analysis scripts
- **configs/**: YAML configuration files and class definitions
- **docs/**: Project documentation and reports
- **models/**: Saved model weights (excluded from git)
- **data/**: Dataset directory (excluded from git)
- **notebooks/**: Jupyter notebooks for experimentation
