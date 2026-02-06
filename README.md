# DeepDetect: Learning All-in-One Dense Keypoints

This repository contains the code used in the paper: **DeepDetect: Learning All-in-One Dense Keypoints** — DeepDetect is an intelligent, adaptable, all-in-one, dense keypoint detector that uses deep learning
to learn the strengths of 7 strong keypoint detectors (SIFT, ORB, BRISK, FAST, AGAST, Harris Corner Detector, and Shi-Tomasi Corners) and 2 well-known edge detectors (Canny and Sobel). It provides highly dense and semantically meaningful keypoints, demonstrating robustness to poor visibility and brightness, low contrast, and complex scenes, without requiring manual tuning. It also outperforms classical detectors in dense 3D reconstruction (providing up to 842,045 voxels), even when their extremely low thresholds are used.

For clarity and reproducibility, the **Image Matching** and **3D Reconstruction** pipelines are presented step-by-step through Jupyter notebooks.

Following files are available in the repository:

| File Name                                     | Description                                                                           |
|-----------------------------------------------|---------------------------------------------------------------------------------------|
| `Train_DEEP_DETECT.ipynb`                     | Performs training of DeepDetect.                                                      |
| `Image_Matching_DEEP_DETECT.ipynb`            | Step by step code for matching images using DeepDetect.                               |
| `Image_Matching_Traditional.ipynb`            | Step by step code for matching images using traditional keypoint detectors.           |
| `DEEP_DETECT_Best_Model.pth`                  | Trained DeepDetect model for image matching.                                          |
| `DEEP_DETECT_Training_Data.npz`               | File containing the data of training and validation losses, recorded during training. |
| `Stereo_3DReconstruction_SIFT.ipynb`          | 3D Reconstruction code using SIFT.                                                    |
| `Stereo_3DReconstruction_DEEP_DETECT.ipynb`   | 3D Reconstruction code using DeepDetect.                                              |
| `DEEP_DETECT_Best_Model_3DReconstruction.pth` | Trained DeepDetect model for 3D Reconstruction.                                       |
| `espnet_model.py`                             | File containing ESPNet architecture, used in 3D Reconstruction.                       |

## Note:
We provide only a few images from the Training and Validation sets used in our work due to storage limitations. However, the provided samples are sufficient to give users a clear understanding about the data.

## Citation:
If you find our repository helpful, please cite the following paper:

```bibtex
@article{tareen2025deepdetect,
  title={DeepDetect: Learning All-in-One Dense Keypoints},
  author={Tareen, Shaharyar Ahmed Khan and Tareen, Filza Khan and Yuan, Xiaojing},
  journal={arXiv preprint arXiv:2510.17422},
  year={2025}
}
