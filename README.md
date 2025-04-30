# Custom-Image-Classification-Pipeline-with-PyTorch
Custom image classification pipeline using PyTorch. It includes data preprocessing with transformations, model inference, and output prediction generation. The pipeline processes test data and saves predictions in a CSV format, ideal for Kaggle submissions or custom image classification tasks.

# Custom Image Classification Pipeline

Welcome to my custom image classification pipeline built with **PyTorch**. This notebook contains all the steps to preprocess test data, make predictions using a trained model, and generate a Kaggle-style submission CSV file.

---

## 🚀 Key Features:

1. **Data Preprocessing**:
   - Transformations: random affine, resizing, and tensor conversion.
   - Custom dataset class to handle various data formats (e.g., NumPy arrays, PIL images).

2. **Model Training**:
   - Custom `TinyVGG` model with flexible hidden units.
   - Early stopping and learning rate scheduling for better training results.

3. **Prediction Pipeline**:
   - Batch inference to handle large datasets efficiently.
   - Collect predictions into tensors, then convert to a CSV file for easy submission.

---

## 🛠 Workflow:

### 1. **Preprocessing**:
   Test images are transformed using affine transformations (random rotations, translations, scaling) and converted into tensor format.

### 2. **Model Training**:
   - Custom `TinyVGG` model is trained with early stopping to avoid overfitting.
   - Data is preprocessed before feeding it into the model for training.

### 3. **Inference**:
   After training, the model makes predictions on the test data, and the results are saved in a CSV file.

### 4. **Submission**:
   The predictions are saved in a format compatible with Kaggle submissions, ready to be submitted directly.

---

## 📦 Requirements:

Before running the notebook, make sure you have the following libraries installed:

```bash
!pip install torch torchvision pandas numpy pillow

# 🤝 Contributing

If you have suggestions or improvements:
- Fork the repository
- Open a pull request

If you find any issue:
- Open an issue, and I’ll do my best to help!


# 📝 License

This project is licensed under the MIT License.  
See the LICENSE file for full details.


