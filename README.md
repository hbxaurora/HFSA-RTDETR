# HFSA-DETR: A novel intelligent gingival inflammation grading model based on dual-domain analysis and adaptive attention

## Project Overview

This project implements HFSA-DETR (Hybrid-Frequency Self-Attention DETR), a deep learning model designed for automated gingival inflammation grading diagnosis. By integrating spatial-frequency dual-domain analysis with an adaptive sparse attention mechanism, this model effectively addresses the challenges of subjectivity and low efficiency in traditional gingival inflammation assessment, providing an objective and standardized intelligent diagnostic solution for oral health screening.

Gingivitis, as the early manifestation of periodontal disease, represents a significant public health concern affecting oral health worldwide. Traditional gingival inflammation assessment relies heavily on the subjective experience of clinical practitioners, which is not only time-consuming and labor-intensive but also results in significant inter-individual variability in assessment outcomes. The HFSA-DETR model proposed in this study can automatically identify and grade gingival inflammation directly from oral RGB images, achieving end-to-end processing from raw image input to precise grading output. Experimental results on both internal and external open-source datasets demonstrate that this model achieves 95.8% on the mAP50 metric, significantly outperforming existing YOLO series models and the RT-DETR baseline while maintaining lower parameter count and computational complexity, showcasing excellent clinical application potential.

## Gingival Inflammation Grading Criteria
![Figure1](https://github.com/user-attachments/assets/a24085e5-f823-4f27-9b27-c1f9de4d4ac4)
## Model Architecture
![Figure2](https://github.com/user-attachments/assets/389b8f4e-cda7-47e3-9baf-034d34d9e53a)


## Data Access

The dataset used in this project consists of two parts: an internally collected dataset and an externally sourced open-source dataset.

**Internal Dataset** contains 2,300 oral RGB photographs collected from 2,300 patients who visited the Affiliated Stomatological Hospital of Wenzhou Medical University between 2024 and 2025. All clinical images were collected by professionally trained stomatologists using a standardized process and saved in JPG format. They were captured with a Canon EOS 5D4 digital camera at 3360×2240 pixels, resulting in a single image file of approximately 3 MB. To protect patient privacy, all image data has undergone rigorous desensitization, removing any personal information that could identify the patient. Due to patient privacy and ethical requirements, the internal dataset cannot be directly shared publicly. To obtain relevant data for academic research, please contact the research team through the following channels.

**External Open-Source Dataset** comes from the Mendeley Data public dataset repository and contains 1,096 oral images of gingival inflammation, focusing on the pathological features of gingival tissue around the 12 anterior teeth. It can be accessed and obtained through the following link: https://data.mendeley.com/datasets/3253gj88rr/1

**Contact Information**

To obtain the internal dataset or for academic collaboration, please contact the research team via the following email:

- **Email**: [hou-yu-bo@wmu.edu.cn]

Please indicate your affiliated institution, research purpose, and data usage plan in your email, and we will contact you as soon as possible.

## Usage Instructions

### Environment Configuration

The experimental environment configuration for this project is shown in the following table, and the code has been tested and validated in this environment.

| Configuration Item | Version/Parameter |
|-------------------|-------------------|
| Operating System | Ubuntu 20.04 |
| Python | 3.8 |
| PyTorch | 1.13.1 |
| CUDA | 11.7 |
| GPU | NVIDIA RTX 4090 |

### Install Dependencies

```bash
pip install -r requirements.txt
```

## License

The code in this project is released under the [MIT License](LICENSE).
