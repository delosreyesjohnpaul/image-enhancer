## Overview
The **Image Enhancer** project aims to improve the quality of images using various enhancement techniques. This repository contains the code to enhance images through sharpening, denoising, and other image processing methods.

## Features
- **Image Sharpening:** Improve the clarity and definition of images.
- **Denoising:** Reduce noise and artifacts from images.
- **Contrast Adjustment:** Enhance the contrast of images for better visual appeal.
- **Brightness Control:** Modify the brightness levels of images.
- **Edge Detection:** Identify and highlight the edges within an image.

## Installation
To use this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/delosreyesjohnpaul/image-enhancer.git
cd image-enhancer
pip install -r requirements.txt
```

## Usage
To enhance an image, run the following command:

```bash
python enhance.py --input <input_image_path> --output <output_image_path> --method <enhancement_method>
```

### Parameters
- `--input`: Path to the input image.
- `--output`: Path to save the enhanced image.
- `--method`: The enhancement method to be used (`sharpen`, `denoise`, `contrast`, `brightness`, `edge_detection`).

## Examples
Enhance an image by sharpening:

```bash
python enhance.py --input sample.jpg --output sample_sharpened.jpg --method sharpen
```

Denoise an image:

```bash
python enhance.py --input sample.jpg --output sample_denoised.jpg --method denoise
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.


## Contact
For questions or suggestions, feel free to open an issue or contact the repository owner directly
