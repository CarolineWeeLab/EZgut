# EZgut
Machine learning-based larval zebrafish gut segmentation for gut fluorescence (food intake) quantification.

We have improved upon [this](https://elifesciences.org/articles/43775) previous thresholding protocol for gut fluorescence quantification. Critically, EZgut does not face the problem of data loss in low feeding conditions.

![Graphical abstract](./graphical_abstract.png)

See our publication [Osmotic Stress Uncovers Correlations and Dissociations Between Larval Zebrafish Anxiety Endophenotypes](https://www.frontiersin.org/articles/10.3389/fnmol.2022.900223/full) for more details.

We have trained Detectron2's [Pointrend](https://github.com/facebookresearch/detectron2/tree/main/projects/PointRend) on our custom dataset of brightfield images of larval zebrafish. The trained model is available via [Google Drive](https://drive.google.com/file/d/1-4Mr0_6xhiZh5QW7IjN8P-Jx1UKQBxbG/view?usp=sharing).

The Google Colab notebook [MaskPrediction_GutFluorescence](./MaskPrediction_FluorescenceAnalysis_v1.ipynb) includes prediction of segmentation masks for the larval zebrafish guts as well as fluroscence analysis to quantify food intake. The [examples folder](./examples/) contains sets of brightfield (BF) and fluorescence (Cy5) images as well as a folder of BF masks that have been curated for any prediction errors. Please note that mask predictions are not always perfect and critical errors require correction by manual ROI drawing in external software such as ImageJ.

Training data is available on request.

### Citing EZgut
If you use EZgut, please cite: [Osmotic Stress Uncovers Correlations and Dissociations Between Larval Zebrafish Anxiety Endophenotypes](https://www.frontiersin.org/articles/10.3389/fnmol.2022.900223/full)

### License
See full license details [here](./LICENSE)

### Acknowledgements
* For help in annotating ground truth data: Chua Kai Xin, Gaynah Doblado, Wen Lie
* For help in code testing: Guan Zhen

### Questions
Please contact:
* Caroline Lei WEE, weel@imcb.a-star.edu.sg
* Jazlynn TAN, jazlynntan99@gmail.com
