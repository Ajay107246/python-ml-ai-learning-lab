# Python ML & AI Learning Lab

🚀 My hands-on learning journey through Python, Machine Learning, AI &amp; GenAI.
Welcome to my personal learning lab where I explore Python, Data Science, Machine Learning, and GenAI using Jupyter Notebooks inside VS Code.

## 📘 Contents

### 01 — Jupyter Practice

Basic notebook setup, interactive backends, VS Code integration.
Link: https://code.visualstudio.com/docs/datascience/jupyter-notebooks

### 02 — NumPy

NOTE: WIP
Array operations, broadcasting, numerical computing.

### 03 — Matplotlib

NOTE: WIP

- Basic plots
- Sine & cosine
- Shaded plots
- Colormaps
- Subplots
- Animations
- 3D surface plots

### 04 — Interactive Visualizations

NOTE: WIP

- Slider‑controlled sine wave
- Interactive 3D plots

### 05 — Pandas

NOTE: WIP
DataFrames, cleaning, filtering, grouping.

### 06 — Machine Learning

NOTE: WIP
Linear regression, classification, model evaluation.

#### Classification

This notebook demonstrates how changing the classification threshold affects model predictions and evaluation metrics. It uses synthetic probability data to show how a classifier’s behavior shifts as the threshold moves between 0 and 1.

🔍 What this notebook covers?

- How probability outputs convert into positive/negative predictions
- How the confusion matrix changes with threshold
- How evaluation metrics respond:
- Accuracy – overall correctness
- Precision – correctness of positive predictions
- Recall (TPR) – ability to detect actual positives
- F1‑Score – balance between precision and recall

🎛 Interactive Visualization

- An interactive slider (powered by `ipywidgets`) updates: Predicted labels, Confusion matrix, All evaluation metrics
- This makes it easy to see the trade‑offs between false positives, false negatives, and overall model performance.

🎯 Recommended Threshold

- There is no universal “best” threshold
- The ideal value depends on the problem:
- High precision → use a higher threshold
- High recall → use a lower threshold
- Balanced performance → optimize using ROC or PR curves

### 07 — GenAI

NOTE: WIP
Text generation, embeddings, RAG experiments

### Initial steps

- python -m venv .venv
- source .venv/bin/activate
- On Windows Git Bash: source .venv/Scripts/activate
- pip install -r requirements.txt

### Folder structure

python-ml-ai-learning-lab/
│
├── 01_jupyter_practice/
│   ├── src/
│   │   └── basic_notebook_setup.ipynb
│
├── 02_numpy/
│   ├── src/
│   │   └── numpy_basics
│
├── 03_matplotlib/
│   ├── 01_basic_plots/
│   │   └── sine_wave_plot.ipynb
│   ├── 02_multi_plots/
│   │   └── sine_cosine_plot.ipynb
│   ├── 03_shaded_animation/
│   │   └── shaded_animation_wave.ipynb
│   ├── 04_colormap_plots/
│   │   └── gradient_colormap_plot.ipynb
│   ├── 05_subplots/
│   │   └── multiple_graphs.ipynb
│   ├── 06_3d_plots/
│       └── 3d_surface_plot.ipynb
│
├── 04_interactive_visualizations/
│   ├── interactive_slider_sine_wave.ipynb
│   ├── interactive_3d_surface.ipynb
│
├── 05_pandas/
│   └── pandas_basics.ipynb
│
├── 06_machine_learning/
│   ├── linear_regression.ipynb
│   └── 02_classification_threshold_confuse_matrix
|        ├── class_threshold_matrix.ipynb
│
├── 07_genai/
│   ├── text_generation.ipynb
│   ├── embeddings.ipynb
│
├── .gitignore
└── README.md
