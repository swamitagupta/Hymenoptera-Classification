# Hymenoptera-Classification

Transfer learning can be performed in two ways:
1. Fine Tuning
2. Feature Extractor

This notebook implements and compares both techniques on the Hymenoptera dataset in Pytorch.

**TLDR**: Feature Extractor provides the highest validation accuracy of 0.9542: while Fine-tuning the model provides an accuracy of 0.9411. This can be attributed to the lesser amount of data in Hymenoptera dataset as compared to the ImageNet dataset, whose pretrained layers extracted features more accurately.
