# Computer Vision Labs

Labs from my computer vision course at MIVA Open University.

## Labs

| Lab | Topic | Notebook |
|-----|-------|----------|
| 1 | Image Processing Fundamentals | MIT8311_Lab1_Image_Processing_Fundamentals.ipynb |

## Lab 1 summary
- Loaded the MNIST dataset.
- Applied binary thresholding with OpenCV.
- Wrote a rule-based detector for the digit "1" using columns 13 to 15.
- Result: it accepted a clean "1" and rejected "5" and "0".
- Finding: my first "1" was slanted and scored 51.6, lower than "5" (88.0) and "0" (60.7), so the rule failed. Hand-written rules are brittle. This is why machine learning is used.

## Tools
Python, OpenCV, NumPy, Matplotlib, TensorFlow/Keras (data only), Google Colab.
