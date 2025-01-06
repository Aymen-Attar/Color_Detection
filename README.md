# Color Detection Project

This project detects colors in an image by matching pixel values to a predefined dataset of color names and their RGB values.

## Features

- Detects colors in an image using Python.
- Provides the closest color name for any pixel clicked on the image.
- Interactive and easy to use.

## How It Works

1. The `colors.csv` file contains a dataset of color names along with their RGB values.
2. The script uses OpenCV to display an image (`colorpic.jpg`) and listens for mouse clicks.
3. When you click on a pixel, the script retrieves its RGB values and matches them with the closest color in the dataset.

## Prerequisites

Ensure you have Python installed on your system. You also need the following Python libraries:

- OpenCV (`cv2`)
- Pandas
- NumPy

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Aymen-Attar/Color_Detection.git
   cd Color_Detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:

   ```bash
   python color_detection.py
   ```

2. The image (`colorpic.jpg`) will open in a window. Click anywhere on the image to detect the color.

3. The detected color name and its RGB values will be displayed on the image.

## Files

- **`color_detection.py`**: The main script for color detection.
- **`colorpic.jpg`**: Sample image for color detection.
- **`colors.csv`**: Dataset containing color names and their RGB values.

## Example

![Sample Output](https://via.placeholder.com/500x300.png?text=Sample+Output)

The detected color will be displayed as:

```
Detected Color: Red (R: 255, G: 0, B: 0)
```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to fork the repository and create a pull request.



## Contact

For any questions or feedback, feel free to reach out:

- **GitHub**: [Aymen-Attar](https://github.com/Aymen-Attar)
