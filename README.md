# Watermarkify

Watermarkify is a Python tool designed to simplify the process of adding watermarks to images. Whether you're looking to brand your images with a logo or protect them with a custom text watermark, Watermarkify provides an easy-to-use solution.

## Features

- **Logo Watermark**: Seamlessly embed your logo onto images with customizable transparency levels.
- **Text Watermark**: Add personalized text watermarks to your images with ease.
- **Flexibility**: Adjust watermark positioning, size, and transparency to suit your needs.
- **External URL Support**: Works effortlessly with images hosted online.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/biswadeep-roy/Watermarkify.git
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

### Adding Logo Watermark

```python
from watermarkify import add_logo_watermark

# Replace 'image_url' and 'logo_url' with actual image and logo URLs
image_url = 'YOUR_IMAGE_URL'
logo_url = 'YOUR_LOGO_URL'

add_logo_watermark(image_url, logo_url)
```

Adding Text Watermark

```python
from watermarkify import add_text_watermark

# Replace 'image_url' with actual image URL
image_url = 'YOUR_IMAGE_URL'

add_text_watermark(image_url, 'YOUR_CUSTOM_TEXT')
```

## Contributing
Contributions are welcome! If you have ideas, suggestions, or bug fixes, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Watermarkify utilizes the Pillow library for image processing.
