# DSPO: Direct Semantic Preference Optimization for Real-World Image Super-Resolution

<div>
    Miaomiao Cai<sup>1,†</sup>&emsp;
    Simiao Li<sup>2†</sup>&emsp;
    Wei Li<sup>2*</sup>&emsp;
    Xudong Huang<sup>2</sup>&emsp;
    Hanting Chen<sup>2</sup>&emsp;
    Jie Hu<sup>2</sup>&emsp;
    Yunhe Wang<sup>2*</sup>&emsp;
</div>

<div>
    <sup>1</sup>University of Science and Technology of China, <sup>2</sup>Huawei Noah’s Ark Lab <br/>
</div>

[![DSPO Paper on arXiv](https://img.shields.io/badge/DSPO-paper-red?logo=arxiv&logoColor=red)](https://arxiv.org/pdf/2504.15176)

---

## Abstract

Recent advances in diffusion models have improved Real-World Image Super-Resolution (Real-ISR). However, existing methods often lack human feedback integration. This can lead to misalignment with human preferences, resulting in artifacts, hallucinations, and the generation of harmful content. In response, we introduce a technique for human preference alignment in Real-ISR. This is a significant step toward enhancing image quality and relevance.

## Table of Contents

1. [Introduction](#introduction)
2. [Methodology](#methodology)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)
8. [Releases](#releases)

## Introduction

The field of image super-resolution has made strides in recent years. Yet, there remains a gap in how these systems align with human preferences. Traditional models focus on technical performance metrics but often overlook user satisfaction. DSPO aims to bridge this gap by incorporating direct semantic preferences into the super-resolution process. This alignment ensures that the output images resonate more with human expectations.

## Methodology

DSPO employs a novel framework that integrates human feedback directly into the training process. The model learns to prioritize features that humans find appealing. This approach not only enhances image quality but also reduces the occurrence of artifacts that can detract from user experience. Key components of the methodology include:

- **Feedback Loop**: A mechanism to gather user input during training.
- **Preference Mapping**: Techniques to translate user feedback into model adjustments.
- **Evaluation Metrics**: Custom metrics to assess human alignment in image outputs.

## Installation

To get started with DSPO, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/luis40589/DSPO.git
   cd DSPO
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the necessary dependencies installed. You may need libraries such as TensorFlow or PyTorch, depending on your environment.

## Usage

To use DSPO for image super-resolution, follow these steps:

1. Prepare your input images. Ensure they are in a supported format (e.g., JPEG, PNG).
2. Run the model with your images:

   ```bash
   python run_dspo.py --input_path path/to/your/images --output_path path/to/save/results
   ```

3. Review the output images in the specified output directory.

For more advanced usage, refer to the documentation within the `docs` folder.

## Results

DSPO has demonstrated significant improvements in image quality when compared to traditional methods. Some key findings include:

- **Higher User Satisfaction**: User studies show a marked increase in satisfaction ratings for images processed with DSPO.
- **Reduced Artifacts**: The integration of human feedback leads to fewer artifacts and hallucinations in generated images.
- **Broader Applicability**: DSPO performs well across various types of images, from landscapes to portraits.

![Sample Output](https://example.com/sample-output.png)

## Contributing

We welcome contributions to DSPO. If you have ideas for improvements or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes and push them to your fork.
4. Open a pull request with a clear description of your changes.

Your contributions help enhance the model and benefit the community.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

To download the latest version of DSPO, visit the [Releases](https://github.com/luis40589/DSPO/releases) section. You can find pre-built binaries and other important files there. If you encounter issues, please check the documentation or raise an issue on GitHub.

For the latest updates and discussions, feel free to check our [Releases](https://github.com/luis40589/DSPO/releases) section regularly.