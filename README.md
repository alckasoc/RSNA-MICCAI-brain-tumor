# RSNA-MICCAI-brain-tumor
Repo for the RSNA-MICCAI Brain Tumor Radiogenomic Classification Competition on Kaggle.


## Table of Contents:
- [File Placement](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/README.md#file-placement)
- [Datasets](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/README.md#datasets)


## File Placement

| File                                   | Colab              | Kaggle             | Google Drive       | Local              | GitHub             |
| -------------------------------------- |:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|
| rsna-miccai-dcm-png-meta-dfs.ipynb     | :x:                | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: |
| make_train_kfold.ipynb                 | :heavy_check_mark:	| :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| RSNA-MICCAI_baseline.ipynb             | :heavy_check_mark:	| :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| baseline_submission.ipynb              | :x:	              | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: |
| RSNA-MICCAI-efnb0-3d_512.ipynb         | :heavy_check_mark:	| :x:                | :heavy_check_mark: | :x:                | :x:                |
| RSNA-MICCAI-make_png_modified.ipynb    | :x:	              | :heavy_check_mark: | :x:                | :x:                | :x:                |


| Dataset                                | Kaggle             | Google Drive       | Local              | GitHub             |
| -------------------------------------- |:------------------:|:------------------:|:------------------:|:------------------:| 
| Competition Dataset                    | :heavy_check_mark: | :x:                | :x:                | :x:                |
| Train/Test Meta DataFrames             | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| RSNA-MICCAI-PNG                        | :heavy_check_mark: | :x:                | :heavy_check_mark: | :x:                |
| train_kfold                            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| baseline_models                        | :heavy_check_mark: | :x:                | :heavy_check_mark: | :x:                |
| rsna_miccai_pngs                       | -                  | -                  | -                  | -                  |


## Datasets

+ Note some of these datasets may be private.

- [Competition Dataset](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification/data).
- [Train/Test Meta DataFrames](https://www.kaggle.com/vincenttu/rsnamiccaibraintumor-meta-datasets) created from [rsna-miccai-dcm-png-meta-dfs.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/preprocessing/rsna-miccai-dcm-png-meta-dfs.ipynb).
- [RSNA MICCAI PNG](https://www.kaggle.com/jonathanbesomi/rsna-miccai-png).
- [train_kfold](https://www.kaggle.com/vincenttu/rsnamiccaibraintumor-train-kfold) created from [make_train_kfold.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/preprocessing/make_train_kfold.ipynb).
- [baseline_models](https://www.kaggle.com/vincenttu/baseline-models) created from [RSNA_MICCAI_baseline.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/RSNA-MICCAI_baseline/RSNA_MICCAI_baseline.ipynb).
