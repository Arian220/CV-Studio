# CV Studio

CV Studio is a graphical user interface (GUI) tool designed for image annotation and labeling. It allows users to easily annotate images by drawing bounding boxes or polygons and associate labels with them. The software supports different output formats, such as YOLO and COCO, and provides zooming features for better interaction with the images. It is especially useful for training machine learning models with labeled datasets.

## Features

- **Image Loading**: Load multiple images from a directory for annotation.
- **Bounding Box and Polygon Annotation**: Draw bounding boxes and polygons to annotate objects in images.
- **Class Management**: Add, remove, and load classes for annotation.
- **Zooming**: Zoom in and out of images to make detailed annotations.
- **Multiple Output Formats**: Export annotations in YOLO or COCO format.
- **File Management**: Open and save images, load and save annotation classes.
- **User-Friendly Interface**: Designed using PyQt5 for a modern and responsive interface.

## Requirements

To run this project, you need to install the following dependencies:

- Python 3.x
- PyQt5

You can install the required libraries using pip:

```bash
pip install PyQt5
```

## Installation

Clone the repository and run the main script:
```bash
git clone https://github.com/Arian220/CV-Studio.git
cd cv-studio
python main.py
```

>[!NOTE]
>Ensure the utils.py file exists in the same directory. This file may include important utility functions used by the application.

## Usage
- Open Images: Click on "Archivo" in the menu and select "Abrir Imágenes" to load a folder containing images.
- Select and Annotate Images: Click on an image from the list to load it in the central panel. Use the tools on the right to annotate the image with bounding boxes or polygons.
- Manage Classes: Add and remove classes from the "Clases" dropdown. You can also load classes from a .txt file.
- Save Annotations: Click the "Guardar Anotaciones" button to save your annotations in the selected format (YOLO or COCO).
- Zoom In/Out: Use the zoom buttons to adjust the view of the image for easier annotation.

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit pull requests. Please make sure to write clear commit messages and include tests if you add new features.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


