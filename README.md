# Brain Tumor MRI Segmentation

Deep-learning segmentation of brain tumours in MRI scans (BraTS 2018) using U-Net style models.

## Contents

| File | What it is |
|------|------------|
| `notebooks/BRATS2018.ipynb` | BRATS2018 |
| `notebooks/BrainSegmentationAI2.ipynb` | Model Construction |
| `notebooks/seg_unet2.ipynb` | **Import Librairies** |

## Getting started

```bash
git clone https://github.com/<your-username>/brain-tumor-mri-segmentation.git
cd brain-tumor-mri-segmentation
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pip install jupyterlab
jupyter lab   # then open a notebook in notebooks/
```

## Notes

- The BraTS dataset is not included; request it from the official BraTS challenge site and point the notebooks at your local copy.
