# Python Color Detection 🎨

A simple color detection project built using **Python** and **OpenCV**.
This program detects the color name and RGB values when the user double-clicks on any pixel in an image.

## 📌 Features

* Detect color name from an image
* Display RGB values of the selected pixel
* Interactive mouse click detection
* Simple and beginner-friendly computer vision project

## 🛠 Technologies Used

* Python
* OpenCV
* NumPy
* CSV color dataset

## 📂 Project Structure

```
Python-color-detection/
│
├── color_detection.py
├── colors.csv
├── image.jpg
└── README.md
```

## ⚙️ Installation

1. Clone the repository

```
git clone https://github.com/sathvik995/Python-color-detection.git
```

2. Navigate to the project folder

```
cd Python-color-detection
```

3. Install required libraries

```
pip install opencv-python
pip install numpy
```

## ▶️ Running the Project

Run the script with an image as input:

```
python color_detection.py -i image.jpg
```

## 🖱 How It Works

1. The program loads an image.
2. The user double-clicks on any part of the image.
3. The program reads the pixel's RGB values.
4. It compares them with the dataset in `colors.csv`.
5. The closest color name is displayed on the screen.

## 📷 Example Output

When you double-click on a pixel, the program will show:

```
Color Name: Red
RGB: (255, 0, 0)
```

## 🎯 Applications

* Basic computer vision learning
* Image processing practice
* Color recognition systems
* Beginner Python projects

## 👨‍💻 Author

Original Repository:
https://github.com/sathvik995/Python-color-detection

---

⭐ If you like this project, consider giving it a star on GitHub!
