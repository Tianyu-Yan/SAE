# Boosting Correspondence Learning with Structure-Aware Estimator (ECCV2026)

## Requirements
Please use Python 3.12 and Pytorch 2.7.0. Other dependencies should be easily installed through "requirements.txt".

## Data

The training and testing require YFCC100M and SUN3D dataset. Use the following code to generate putative correspondences for YFCC100M and SUN3D with SIFT.
```bash
cd dump_match
python extract_feature.py
python yfcc.py
python extract_feature.py --input_path=../raw_data/sun3d_test
python sun3d.py
```

## Coming Soon
