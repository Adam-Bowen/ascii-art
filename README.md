# ASCII Art Converter

This Python script converts images to ASCII art and saves the result as both a text file and a PNG image with a transparent background. ject converts images into ASCII art and saves the results both as a PNG file and as plain text. The tool can be used to generate ASCII representations of images, which can then be displayed in terminals, text editors, or dashboards e.g. nvim.

## Example
![GZpMxgHWkAceOuM](https://github.com/user-attachments/assets/05e59e76-f03c-4c28-b550-d8cb8cdbc553)
![CleanShot 2024-10-12 at 23 42 18@2x](https://github.com/user-attachments/assets/b79caa5e-6645-412d-8aa2-93c6032ae618)


## Usage

1. Place your image file in the same directory as the script.
2. Update the `IMAGE_PATH` variable in the script with your image filename.
3. Run the script:

   ```bash
   python main.py
   ```

## Requirements

- Python 3.x
- Pillow (Python Imaging Library)

Make sure you are in a virtual environment and then install the required dependencies (only Pillow) by running:

```bash
pip install -r requirements.txt
```


## How The Converter Works

1. The script loads an image file.
2. It resizes the image to a specified width while maintaining the aspect ratio.
3. The image is converted to grayscale.
4. Each pixel's grayscale value is mapped to an ASCII character.
5. The resulting ASCII art is saved as a text file.
6. The ASCII art is also rendered as a PNG image with a transparent background.

## Screenshot

A few pieces of art generated by this tool:
