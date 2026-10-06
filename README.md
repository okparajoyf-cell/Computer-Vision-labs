# Computer Vision Labs

Labs from my computer vision course at MIVA Open University.

## Labs

| Lab | Topic | Notebook |
|-----|-------|----------|
| 1 | Image Processing Fundamentals | MIT8311_Lab1_Image_Processing_Fundamentals.ipynb |
| 2 | Image Classification with CNNs | MIT8311_Lab2_Image_Classification_with_CNNs.ipynb |


## Lab 1 summary
- Loaded the MNIST dataset.
- Applied binary thresholding with OpenCV.
- Wrote a rule-based detector for the digit "1" using columns 13 to 15.
- Result: it accepted a clean "1" and rejected "5" and "0".
- Finding: my first "1" was slanted and scored 51.6, lower than "5" (88.0) and "0" (60.7), so the rule failed. Hand-written rules are brittle. This is why machine learning is used.

 ## Lab 2 summary
- Built a CNN with Conv2D and MaxPooling layers in Keras.
- Trained on MNIST for 5 epochs.
- Test accuracy: 98.83% (117 wrong out of 10,000).
- Correctly classified the slanted and blurry 5s, 6s, 1s, and 7s I checked.
- Finding: a CNN learns shapes by itself and handles handwriting variation better than my Lab 1 rule.

## Tools
Python, OpenCV, NumPy, Matplotlib, TensorFlow/Keras, Google Colab.
