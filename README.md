
# ResCoWNet: A Novel Deep Learning Approach for Despeckling OCT Images

#### Do check out the publication for this project:

![Static Badge](https://img.shields.io/badge/Paper-red?logo=Elsevier&labelColor=black&link=https%3A%2F%2Fwww.sciencedirect.com%2Fscience%2Farticle%2Fabs%2Fpii%2FS0030402623004205)

## Overview

Optical Coherence Tomography (OCT) is a non-invasive imaging technology widely used for diagnosing and treating retinal illnesses. However, OCT images are often affected by speckle noise, which significantly degrades image quality and hampers accurate disease diagnosis.

This project introduces ResCoWNet, a novel deep convolutional neural network designed to enhance the quality of OCT images by efficiently despeckling them. The proposed method leverages Dual-Tree Complex Wavelet Transform (DT-CWT) and residual learning to outperform traditional and existing deep learning techniques in reducing noise, thereby improving the overall clarity and diagnostic usability of OCT images.

## Key Features

- **Speckle Noise Reduction**: Uses advanced despeckling techniques to improve the quality of noisy OCT images.
- **Dual-Tree Complex Wavelet Transform (DT-CWT)**: Employed for superior performance in noise reduction compared to traditional Discrete Wavelet Transform (DWT) methods.
- **Residual Learning**: Facilitates efficient deep learning by incorporating residual blocks at multiple levels.
- **Hierarchical Network Structure**: Utilizes a deep convolutional neural network (CNN) to capture spatial correlations and extract information at various resolutions.
- **Quantitative & Subjective Improvements**: Produces OCT images that outperform existing despeckling methods both quantitatively and subjectively.

## Results

Our model outperforms conventional despeckling techniques (such as PNLM, WGLRR, MWCNN and MWRN) and other deep learning-based denoising models. Quantitative evaluations and subjective analysis both indicate significant improvements in image quality.
## Deployment

To deploy this project run

```bash
  git clone https://github.com/ShreCodes2809/ResCoWNet_MWRDCNN.git
```

I worked on this project during my summer research internship at National Institute of Technology, Tiruchirappalli.