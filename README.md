# EZgut
Machine learning-based larval zebrafish gut segmentation for gut fluorescence (food intake) quantification

We have trained Detectron2's [Pointrend](https://github.com/facebookresearch/detectron2/tree/main/projects/PointRend) on our custom dataset of brightfield images of larval zebrafish. The trained model is available via [Google Drive](https://drive.google.com/file/d/1-4Mr0_6xhiZh5QW7IjN8P-Jx1UKQBxbG/view?usp=sharing).

The Google Colab notebook [MaskPrediction_GutFluorescence](./MaskPrediction_GutFluorescence_v1.ipynb) includes prediction of segmentation masks for the larval zebrafish guts as well as fluroscence analysis to quantify food intake. 
