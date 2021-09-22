# RSNA-MICCAI-brain-tumor
Repo for the RSNA-MICCAI Brain Tumor Radiogenomic Classification Competition on Kaggle.


## Table of Contents:
- [File Placement](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/README.md#file-placement)
- [Datasets](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/README.md#datasets)


## File Placement

| File                                    | Colab              | Kaggle             | Google Drive       | Local              | GitHub             | Executed In  |
| --------------------------------------- |:------------------:|:------------------:|:------------------:|:------------------:|:------------------:|:------------:|         
| rsna-miccai-dcm-png-meta-dfs.ipynb      | :x:                | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | Kaggle       |
| make_train_kfold.ipynb                  | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Colab        |
| RSNA-MICCAI_baseline.ipynb              | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Colab        | 
| baseline_submission.ipynb               | :x:	               | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | Kaggle       |
| RSNA-MICCAI-efnb0-3d_512_archived.ipynb | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Colab        |
| RSNA-MICCAI-make_png_modified.ipynb     | :x:	               | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | Local/Gcloud |
| RSNA-MICCAI-move_data_GCS.ipynb         | :x:	               | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | Kaggle       |
| make_plane_modality_kfold.ipynb         | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Colab        |
| RSNA-MICCAI_efnb0_3d_256.ipynb          | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Colab        |


+ Note: Converting all images was too time consuming and I opted to not do it.

| Dataset                                | Kaggle             | Google Drive       | Local              | GitHub             |
| -------------------------------------- |:------------------:|:------------------:|:------------------:|:------------------:| 
| Competition Dataset                    | :heavy_check_mark: | :x:                | :heavy_check_mark: | :x:                |
| Train/Test Meta DataFrames             | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| RSNA-MICCAI-PNG                        | :heavy_check_mark: | :x:                | :heavy_check_mark: | :x:                |
| train_kfold                            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| baseline_models                        | :heavy_check_mark: | :x:                | :heavy_check_mark: | :x:                |
| images_meta_df                         | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: |
| rsnamiccaibraintumorapikey             | :heavy_check_mark: | :x:                | :heavy_check_mark: | :x:                |
| rsna_miccai_pngs                       | -                  | -                  | -                  | -                  |
| detailed_train_meta                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                |
| plane_modality_kfold                   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| rsna_miccai_pngs                       | -                  | -                  | -                  | -                  |
| RSNA Processed Voxels 64x256x256 CLAHE | :heavy_check_mark: | :x:                | :x:                | :x:                |


## Datasets

+ Note some of these datasets may be private.

- [Competition Dataset](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification/data).
- [Train/Test Meta DataFrames](https://www.kaggle.com/vincenttu/rsnamiccaibraintumor-meta-datasets) created from [rsna-miccai-dcm-png-meta-dfs.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/preprocessing/rsna-miccai-dcm-png-meta-dfs.ipynb).
- [RSNA-MICCAI-PNG](https://www.kaggle.com/jonathanbesomi/rsna-miccai-png).
- [train_kfold](https://www.kaggle.com/vincenttu/rsnamiccaibraintumor-train-kfold) created from [make_train_kfold.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/preprocessing/make_train_kfold.ipynb).
- [baseline_models](https://www.kaggle.com/vincenttu/baseline-models) created from [RSNA_MICCAI_baseline.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/RSNA-MICCAI_baseline/RSNA_MICCAI_baseline.ipynb).
- [images_meta_df](https://www.kaggle.com/vincenttu/images-meta-df) was created from running just the first half of [rsna-miccai-dcm-png-meta-dfs.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/preprocessing/rsna-miccai-dcm-png-meta-dfs.ipynb).
- rsnamiccaibraintumorapikey was how I accessed my GCS. 
- [detailed_train_meta](https://www.kaggle.com/vincenttu/detailed-train-meta) was created from exporting the train_meta_df from [here](https://www.kaggle.com/smoschou55/advanced-eda-brain-tumor-data).
- [plane_modality_kfold](https://www.kaggle.com/vincenttu/plane-modality-kfold) created from [make_plane_modality_kfold.ipynb](https://github.com/alckasoc/RSNA-MICCAI-brain-tumor/blob/main/src/preprocessing/make_plane_modality_kfold.ipynb).
- [RSNA Processed Voxels 64x256x256 CLAHE](https://www.kaggle.com/sreevishnudamodaran/rsna-processed-voxels-64x256x256-clahe).
