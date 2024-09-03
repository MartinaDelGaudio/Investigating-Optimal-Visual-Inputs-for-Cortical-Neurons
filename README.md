# Investigating Optimal Visual Inputs for Cortical Neurons

This group research project is committed to employing deep learning techniques to identify and generate the Most Excitatory Input (MEI) for targeted neurons in the visual system of a mouse, specifically through the use of end-to-end trained Convolutional neural networks (CNNs). 
**My part involved the design of the CNN architecture**. 

A visual representation of the whole process can be found below.

![Screenshot 2024-09-03 181215](https://github.com/user-attachments/assets/a12f8450-bb11-4a5b-a469-f316b144e712)

The dataset used is provided by the Allen Institute for Brain Science, collecting whole-brain datasets for public use.

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

Finally, there's a Jupyter Notebook included (dataset_download.ipynb) that automates the process of downloading the dataset directly into your created environment. Simply open the notebook and follow the provided instructions to get started quickly.

## 🚀 Outline of the project
This project is divided into four key parts:

- **Identification of Most Expressive Neurons**: We begin by identifying the neurons in the mice visual cortex that are most responsive to visual stimuli. This step sets the foundation for targeted analysis.
  
- **CNN Architecture**: A custom Convolutional Neural Network (CNN) is designed to predict neuronal responses. The architecture and detailed methodology are explained in the accompanying report and notebook. A visualization of the architecture can be found below.
  
![WhatsApp Image 2024-09-03 at 17 54 52](https://github.com/user-attachments/assets/92d6c8a7-9eb6-48d6-b3b3-fe2fc3d12c39)

- **Generation of the Most Excitatory Inputs (MEI)**: Using various techniques, including gradient ascent on the CNN, we generate the MEI that maximizes neuronal responses. This process is visually illustrated below.
  
![Screenshot 2024-09-03 181620](https://github.com/user-attachments/assets/42fb5212-628e-49d1-a551-d545076f0081)

- **Final Comparison**: The project concludes with a comparative analysis of the generated MEIs and Gabor filters, which are recognized as the most excitatory visual stimuli for mice.


# Bibliography

This work has been inspired by [1] and it was applied on AllenSDK dataset[2].

[1] W. et al, “Inception loops discover what excites neurons most using deep predictive models”, Nature Neuroscience, 2019.

[2] https://allensdk.readthedocs.io/en/latest/index.html
