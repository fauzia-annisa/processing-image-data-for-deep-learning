# processing-image-data-for-deep-learning

This repository contains Jupyter notebooks for basic image processing tasks used in Deep Learning.

## 📂 Repository Contents
Based on the uploaded files:
- `processing image data for deep learning.ipynb`
- `processing image data for deep learning .ipynb`
- `processing_image_data_for_Deep_Learning.ipynb` 
- `processing_image_data_for_deep_learning.ipynb`

## 📌 What the notebooks do
From the code in the screenshots, the notebooks cover:
1.  **Loading images** using `cv2.imread()` and `PIL.Image.open()`
2.  **Checking image properties** like `img.shape` and `type(img)`
3.  **Resizing images** to `200x200` using PIL: `img.resize((200, 200))`
4.  **Converting to Grayscale** using OpenCV: `cv2.cvtColor(img, cv2.COLOR_RGB2GRAY)`
5.  **Displaying images** using `matplotlib.pyplot.imshow()` and `cv2_imshow()`
6.  **Saving processed images** using `cv2.imwrite()` and `img.save()`

Example image used: `dog.jpg`

## 🚀 How to Use
1.  Open any of the `.ipynb` files in Google Colab or Jupyter Notebook
2.  Upload your own image file like `dog.jpg` to `/content/`
3.  Run the cells step by step

## 🛠️ Requirements
- Python 3.x
- Google Colab or Jupyter Notebook
- Libraries: `tensorflow`, `opencv-python`, `pillow`, `matplotlib`, `numpy`

Install with:
```bash
pip install tensorflow opencv-python pillow matplotlib numpy
