# DICM Dataset

The **DICM (Digital Image and Camera Model)** dataset is a collection of
real-world images captured using commercial digital cameras. It is commonly
used as a benchmark dataset for **low-light image enhancement**, contrast
enhancement, and related image-processing research.

## Dataset

- **Dataset:** DICM
- **Number of images:** 69
- **Image type:** Real-world photographs
- **Capture source:** Commercial digital cameras
- **Main application:** Low-light image enhancement
- **Dataset type:** Unpaired real-world images

The dataset is distributed as part of the research resources associated with
the Media Communications Laboratory (MCL), Korea University.

## Original Source

The original dataset is available from:

**Media Communications Laboratory (MCL), Korea University**

https://mcl.korea.ac.kr/projects/LDR/

Original download:

http://mcl.korea.ac.kr/projects/LDR/LDR_TEST_IMAGES_DICM.zip

## Citation

If you use this dataset in academic research, please cite the original work
associated with the dataset:

> C. Lee, C. Lee, and C.-S. Kim, "Contrast Enhancement Based on Layered
> Difference Representation," *IEEE Transactions on Image Processing*,
> vol. 22, no. 12, pp. 5372–5384, 2013.

The work was originally presented at ICIP 2012. The paper describes the
layered difference representation approach for image contrast enhancement.

## Intended Use

This repository is intended to facilitate reproducible research involving:

- Low-light image enhancement
- Image contrast enhancement
- Illumination correction
- Image restoration
- Computational photography
- Image quality assessment
- Benchmarking of enhancement algorithms

## Dataset Structure

```text
DICM-Dataset/
│
├── images/
│   ├── image_01.*
│   ├── image_02.*
│   ├── ...
│   └── image_69.*
│
├── README.md
└── LICENSE
