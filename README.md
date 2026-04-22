# Advanced Customizations in Deep Learning and Neural Networks

This repository contains Google Colab notebooks covering regularization, data augmentation, and advanced deep learning constructs in both **TensorFlow/Keras** and **PyTorch**. Each notebook includes a corresponding walkthrough video.

---

## Notebooks

### 1) `01_Regularization_Techniques_TF_PyTorch.ipynb`
- **Colab Notebook**: [Colab Link](https://colab.research.google.com/drive/1LLGjlGfGKPLpPXU4s8OnqDUG5shoLq6E?usp=sharing)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: L1/L2 Regularization, Dropout, Early Stopping, Monte Carlo Dropout (Part 1a–d)

### 2) `02_Initialization_BatchNorm_TF_PyTorch.ipynb`
- **Colab Notebook**: [Colab Link](https://colab.research.google.com/drive/1ZRDs7_169Zd7W4Bolr2vm0IJaeX3YdOl#scrollTo=LWW6YtRRwRS4)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: Weight Initialization (Xavier, He, LeCun, Orthogonal), Batch Normalization, Layer Normalization, Group Normalization (Part 1e–f)

### 3) `03_Custom_Dropout_Regularization_TF_PyTorch.ipynb`
- **Colab Notebook**: [Colab Link](https://colab.research.google.com/drive/1m_qZPJufZ5u0OeJzApEeFAStNY1yGoo9)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: Custom Dropout Variants (Alpha, Gaussian, Concrete, DropBlock), Custom Regularizers (Orthogonal, Spectral, Activity) (Part 1g)

### 4) `04_Callbacks_Tensorboard_KerasTuner.ipynb`
- **Colab Notebook**: [Colab Link](COLAB_LINK_HERE)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: Callbacks (ModelCheckpoint, EarlyStopping, ReduceLROnPlateau, Custom), TensorBoard, Keras Tuner Hyperparameter Tuning (Part 1h–i)

### 5) `05_KerasCV_Data_Augmentation.ipynb`
- **Colab Notebook**: [Colab Link](COLAB_LINK_HERE)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: KerasCV Data Augmentation — RandAugment, CutMix, MixUp, RandomCutout, Solarization, GridMask (Part 1j)

### 6) `06_AugLy_MultiModal_Augmentation.ipynb`
- **Colab Notebook**: [Colab Link](COLAB_LINK_HERE)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: Multi-Domain Data Augmentation — Image, Text (nlpaug), Audio, Time Series, Tabular (SMOTE), Video (Part 1k)

### 7) `07_Advanced_Keras_Custom_Components.ipynb`
- **Colab Notebook**: [Colab Link](COLAB_LINK_HERE)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: TensorFlow/Keras — Custom LR Scheduler, Custom Dropout (MCAlphaDropout), Custom Normalization (MaxNormDense), TensorBoard, Custom Loss (HuberLoss), Custom Activation/Initializer/Regularizer/Constraint, Custom Metric (HuberMetric), Custom Layers (MyDense, GaussianNoise, Attention), Custom Model (ResidualRegressor) (Part 2 i–ix)

### 8) `08_Custom_Optimizer_Training_Loop.ipynb`
- **Colab Notebook**: [Colab Link](COLAB_LINK_HERE)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: Custom Optimizer (MyMomentumOptimizer, Adam from Scratch), Custom Training Loop (GradientTape, Gradient Accumulation, Mixed Precision) (Part 2 x–xi)

### 9) `09_Weights_and_Biases_Integration.ipynb`
- **Colab Notebook**: [Colab Link](COLAB_LINK_HERE)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: Weights & Biases Experiment Tracking — wandb.init, wandb.log, wandb.watch, Sweeps, Artifacts, Alerts (Part 2 xii)

### 10) `10_Advanced_PyTorch_Custom_Components.ipynb`
- **Colab Notebook**: [Colab Link](COLAB_LINK_HERE)
- **Video Explanation**: [YouTube Link](YOUTUBE_LINK_HERE)
- **Coverage**: PyTorch — Custom LR Scheduler, Custom Dropout, Custom Normalization, Custom Loss, Custom Activation/Initializer/Regularizer/Constraint, Custom Metric, Custom Layers, Custom Model, Custom Optimizer, Custom Training Loop (Part 2 i–xi)

---

## Assignment Topics

| Part | Topics Covered |
|------|----------------|
| **Part 1** | Regularization (L1/L2, Dropout, Early Stopping, MC Dropout), Initialization, Batch Normalization, Custom Dropout, Callbacks, TensorBoard, Keras Tuner, Data Augmentation (KerasCV, AugLy) |
| **Part 2** | Custom LR Schedulers, Custom Loss Functions, Custom Activations, Custom Layers, Custom Metrics, Custom Models, Custom Optimizers, Custom Training Loops, Weights & Biases |

---

## References

- Géron, A. — [Hands-On ML3 (TensorFlow)](https://github.com/ageron/handson-ml3)
- Géron, A. — [Hands-On ML2 (TensorFlow)](https://github.com/ageron/handson-ml2)
- Géron, A. — [Hands-On MLP (PyTorch)](https://github.com/ageron/handson-mlp)
- [TensorFlow Data Augmentation Tutorial](https://www.tensorflow.org/tutorials/images/data_augmentation)
- [KerasCV Documentation](https://keras.io/keras_cv)
- [Awesome Data Augmentation](https://brunokrinski.github.io/awesome-data-augmentation/)
- [AugLy — Facebook Research](https://github.com/facebookresearch/AugLy)
- [Data Augmentation Review](https://github.com/AgaMiko/data-augmentation-review)

