# Traffic Sign Image Classification

This repository contains a TensorFlow/Keras notebook and a saved model for classifying traffic-sign images. It also includes CSV metadata and image data referenced by the notebook.

## Project files

```text
.
├── Meta.csv
├── Test.csv
├── Train.csv
└── model/
    ├── Traffic_sign_recognition.ipynb
    └── traffic_classifier.h5
```

The notebook uses TensorFlow/Keras, OpenCV, Pillow, pandas, NumPy, Matplotlib, and scikit-learn. It imports `google.colab.drive` and reads images and labels from `/content/drive/MyDrive/archive`; the current notebook is Google Colab-oriented. The CSV files are present in the repository, but the referenced image-folder archive is not included in this repository snapshot.

## Running the notebook

1. Install the required Python packages in a compatible environment.
2. Open `model/Traffic_sign_recognition.ipynb` in Jupyter or Google Colab.
3. Review the dataset paths in the notebook and update them for the location of this repository.
4. Run the cells in order to inspect data, train/evaluate the CNN, and use the saved model where the notebook does so.

For a local Jupyter environment, install the notebook dependencies with:

```bash
pip install tensorflow opencv-python pillow pandas numpy matplotlib scikit-learn jupyter
```

## Notes

- The repository includes a `.h5` model artifact; loading it requires a TensorFlow/Keras version compatible with the model's serialization format.
- No accuracy figure is claimed here; run the notebook to reproduce its evaluation.
- This is an image-classification demonstration, not a complete traffic-sign detection or autonomous-driving system.
