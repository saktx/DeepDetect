# DeepDetect: Learning All-in-One Dense Keypoints

This repository contains the implementation of the paper **DeepDetect: Learning All-in-One Dense Keypoints** — DeepDetect is an intelligent, adaptable, all-in-one, dense keypoint detector that uses deep learning
to learn the strengths of 7 strong keypoint detectors (SIFT, ORB, BRISK, FAST, AGAST, Harris Corner Detector, and Shi-Tomasi Corners) and 2 well-known edge detectors (Canny and Sobel). It provides highly dense and semantically meaningful keypoints, demonstrating robustness to poor visibility and brightness, low contrast, and complex scenes, without requiring manual tuning.

Following Jupyter notebooks are provided publicly:

| File Name                          | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `Train_DEEP_DETECT.ipynb`          | Performs training of DeepDetect.                                            |
| `Image_Matching_DEEP_DETECT.ipynb` | Step by step code for matching images using DeepDetect.                     |
| `Image_Matching_Traditional.ipynb` | Step by step code for matching images using traditional keypoint detectors. |

## Citation:
If you find our code helpful, please cite following paper:

```bibtex
@article{tareen2025deepdetect,
  title={DeepDetect: Learning All-in-One Dense Keypoints},
  author={Tareen, Shaharyar Ahmed Khan and Tareen, Filza Khan},
  journal={arXiv preprint arXiv:2510.XXXXX},
  year={2025}
}
