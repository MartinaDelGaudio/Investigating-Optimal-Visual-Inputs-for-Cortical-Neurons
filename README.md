# Investigating Optimal Visual Inputs for Cortical Neurons

This research is committed to employing deep learning techniques to identify and generate the Most Excitatory Input (MEI) for targeted neurons in the visual system of a mouse, specifically through the use of end-to-end trained Convolutional neural networks (CNNs). The dataset used is provided by the Allen Institute for Brain Science, collecting whole-brain datasets for public use.

## 📦 Dataset Installation Guide

To work with datasets provided by the Allen Institute for Brain Science, you'll need to install the AllenSDK. Follow these steps to set up the environment and access the data.

### Prerequisites
Ensure you have [Anaconda](https://www.anaconda.com/products/distribution) installed to manage your Python environments efficiently.

### Step-by-Step Installation

1. **Create a New Conda Environment:**
   
   ```bash
   conda create -n allensdk
   ```
2. **Activate the Environment:**
   
   ```bash
   conda activate allensdk
   ```
3. **Install the Allen SDK:**
   
   Use `pip` to install the Allen SDK package:
   ```bash
   pip install allensdk
   ```
For additional resources and other distribution formats, you can visit the official [Allen SDK Documentation](https://allensdk.readthedocs.io/en/latest/).

### 🚀 Let's Start

There's a Jupyter Notebook included (...ipynb) that automates the process of downloading the dataset directly into your created environment. Simply open the notebook and follow the provided instructions to get started quickly.






# Bibliography
This work has been inspired by [1] and it was applied on AllenSDK dataset[2].
[1] W. et al, “Inception loops discover what excites neurons most using deep predictive models”, Nature Neuroscience, 2019.
[2] https://allensdk.readthedocs.io/en/latest/index.html
