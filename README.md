# HWF (Hollywood Fly) & LVF (LasV Fly) Dataset for UAV Visual Place Recognition

This repository contains the **HWF** and **LVF** datasets, designed for deep learning-based UAV visual place recognition and localization. These datasets provide high-quality UAV imagery for research in **UAV-to-Satellite matching and localization**.

## Download the Dataset

The dataset introduced in the paper *ACCL: A Plug-and-Play Adaptive Confusion-Aware Contrastive Loss for UAV-to-Satellite* is available for download:

- **[Hollywood Fly Dataset](Google Drive URL)**
- **[LasV Fly Dataset](Google Drive URL)**

## Directory Structure

```
├── Data   
│   ├── Test/                    # Testing dataset (same structure as Val/)
│   ├── Train/                   # Training dataset (same structure as Val/)
│   ├── Val/                     # Validation dataset
│   │   ├── gt_matches.csv       # Ground truth matching file
│   │   ├── query.csv            # Query file containing image information
│   │   ├── query_images/        # Query images directory
│   │   ├── reference.csv        # Reference metadata file
│   ├── reference.csv            # Global reference file for all sets
│   ├── reference_images/        # Directory containing reference images
│   ├── reference_images.csv     # Reference image metadata
```

## Related Project

For more details on the ACCL: A Plug-and-Play Adaptive Confusion-Aware Contrastive Loss for UAV-to-Satellite used in this dataset, check out the ACCL project repository:

🔗 **[ACCL: A Plug-and-Play Adaptive Confusion-Aware Contrastive Loss for UAV-to-Satellite](https://github.com/NWPU-CPS/ACCL)**

## Citation

If you find this dataset useful in your research, please consider citing our paper:

```bibtex
@inproceedings{your_citation,
  author    = {Author Name and Co-authors},
  title     = {ACCL: A Plug-and-Play Adaptive Confusion-Aware Contrastive Loss for UAV-to-Satellite},
  booktitle = {Proceedings of ICME},
  year      = {2025}
}
```
