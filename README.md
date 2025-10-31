# Cross-domain-Anomalous-Sound-Detection
Cross-domain Anomalous Sound Detection for Antarctic Diesel Generator Sets Based on Pseudo-label Generation and Feature Disentanglement
![framework](https://github.com/user-attachments/assets/14f04a58-1df7-4727-a004-7f362f02ec62)
# Dependencies
pytorch_gpu_2.1.1

librosa==0.10.2.post1

omegaconf==2.2.3

scikit_learn==1.1.1

hydra-core==1.2.0

tqdm==4.66.5

lightning==2.4.0

relpath==3.0.5

torch==2.1.1

torchvision==0.16.1

torchaudio==2.1.1

tensorboardX==2.6.2.2

matplotlib==3.5.1

numpy==1.23.5

pandas==1.4.2

umap-learn==0.5.6
# How to Train
cd ./pseudoattr

bash pseudo_attr.sh

cd ./jobs/exp

bash exp3_PL.sh
# Reference
This paper was submitted to IEEE TRANSACTIONS ON INDUSTRIAL INFORMATICS and is currently in the second round of review. The following papers were used as references for this code.

1.Improvements of Discriminative Feature Space Training for Anomalous Sound Detection in Unlabeled Conditions

2.Disentangling Hierarchical Features for Anomalous Sound Detection Under Domain Shift
