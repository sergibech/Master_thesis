# Assessing VTE in cancer patients using deep learning synthetic data generation and domain adaptation techniques.
 
 This repository contains the code for my master's thesis. The repository is organized into three folders, each encompassing the necessary code and a requeriments.txt file to replicate specific experiments. Please note that due to the sensitive nature of the dataset, which contains clinical information of real patients, it cannot be uploaded to this repository as it is not publicly available.

- Experiment 1: Inside this folder, you'll find two notebooks. The first notebook presents our reproduction of a paper, including the permutation test and all the analyses outlined in my master's thesis. The second notebook replicates the findings of the Oncothromb paper; however, it excludes the preprocessing step and selects directly the same variables as the original paper.
- Experiment 2: This folder focuses on the performance study of various state-of-the-art GANs for tabular data. It includes a separate notebook for each architecture, as well as a folder named 'model' containing the code for CTABGAN with minor modifications to suit our dataset. The other methods are trained using the SDV library. Additionally, this folder contains the '.pkl' files for some trained GANs.
- Experiment 3: This folder contains our approach combining deep learning synthetic data generation and domain adaptation techniques in order to improve the Oncothromb score.
  
    
