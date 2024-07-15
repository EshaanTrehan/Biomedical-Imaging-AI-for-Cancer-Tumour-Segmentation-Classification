
# Biomedical Imaging Project

## Tumor Segmentation & Classification

This project aims to perform breast cancer tumor segmentation and classification using ultrasound scans. The dataset contains ultrasound images categorized into benign, malignant, and normal classes, along with corresponding segmentation maps.

## 🚀 Features

- **Tumor Segmentation**: Identify and segment tumors in ultrasound scans.
- **Tumor Classification**: Classify the segmented tumors into benign, malignant, or normal.
- **Data Visualization**: Display examples of ultrasound scans and their corresponding segmentation maps.

## 📁 File Structure

- `Lab 6.ipynb` - Main Jupyter notebook containing the project code and analysis.
- `dataset/`
  - `benign/`
    - `input.npy` - Input ultrasound scans for benign tumors.
    - `target.npy` - Target segmentation maps for benign tumors.
  - `malignant/`
    - `input.npy` - Input ultrasound scans for malignant tumors.
    - `target.npy` - Target segmentation maps for malignant tumors.
  - `normal/`
    - `input.npy` - Input ultrasound scans for normal cases.
    - `target.npy` - Target segmentation maps for normal cases.
- `requirements.txt` - Specifies the Python libraries needed.
- `models/` - Directory to save/load trained models.

## 🔧 Setup & Execution

1. Ensure you have Python installed on your system.
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Lab\ 6.ipynb
   ```

## 🧪 Testing

- Launch the Jupyter notebook to ensure all cells run without errors.
- Verify data loading and visualization of ultrasound scans and segmentation maps.
- Train the segmentation and classification models and evaluate their performance.

## 🧠 Technical Details

- **Client-Side Technology**: Jupyter Notebook.
- **Server-Side Technology**: Python.
- **Key Python Libraries**:
  - **NumPy**: For numerical operations and handling .npy files.
  - **Pandas**: For data manipulation and analysis.
  - **Matplotlib**: For plotting graphs and visualizing images.
  - **Keras**: For building and training neural networks.
  - **scikit-learn**: For data preprocessing and evaluation metrics.
  - **Google Colab**: For cloud-based execution and mounting Google Drive.

## 🌟 Support

For any technical issues or contributions, please open an issue on the project's GitHub repository page or contact the project maintainer.
