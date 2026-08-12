TransAddAttUnet-Brain-Tumor-Segmentation/
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── configs/
│   └── config.yaml
│
├── data/
│   └── README.md
│
├── src/
│   ├── dataset.py
│   ├── preprocessing.py
│   ├── augmentation.py
│   ├── model.py
│   ├── attention.py
│   ├── tsa.py
│   ├── gsa.py
│   ├── aam.py
│   ├── additive_attention.py
│   ├── losses.py
│   └── utils.py
│
├── train/
│   ├── train.py
│   └── train_kfold.py
│
├── evaluation/
│   ├── evaluate.py
│   ├── metrics.py
│   └── statistical_analysis.py
│
├── visualization/
│   ├── plot_loss.py
│   ├── plot_accuracy.py
│   ├── plot_confusion_matrix.py
│   ├── plot_roc.py
│   ├── plot_segmentation.py
│   ├── plot_attention.py
│   └── plot_comparison.py
│
├── baselines/
│   ├── unet.py
│   ├── linknet.py
│   ├── transunet.py
│   └── transattunet.py
│
├── notebooks/
│   ├── 01_dataset_analysis.ipynb
│   ├── 02_training.ipynb
│   ├── 03_evaluation.ipynb
│   └── 04_visualization.ipynb
│
├── checkpoints/
│
└── results/
    ├── figures/
    ├── tables/
    └── metrics/
