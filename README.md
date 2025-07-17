
# 3D MRI Brain Tumor Segmentation using U-Net 🧠

This project implements a deep learning pipeline for segmenting brain tumors from 3D MRI scans using a U-Net architecture in PyTorch. The model is trained on the BraTS dataset and achieves high segmentation performance.

---

## 🧪 Try It on Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/#fileId=https%3A//storage.googleapis.com/kaggle-colab-exported-notebooks/abdelrahmansaeed291/notebook9bcbb25486.ad1fe694-eab7-4c01-9915-2f5af55e6780.ipynb](https://colab.research.google.com/#fileId=https%3A//storage.googleapis.com/kaggle-colab-exported-notebooks/abdelrahmansaeed291/notebook9bcbb25486.ad1fe694-eab7-4c01-9915-2f5af55e6780.ipynb%3FX-Goog-Algorithm%3DGOOG4-RSA-SHA256%26X-Goog-Credential%3Dgcp-kaggle-com%2540kaggle-161607.iam.gserviceaccount.com/20250717/auto/storage/goog4_request%26X-Goog-Date%3D20250717T125031Z%26X-Goog-Expires%3D259200%26X-Goog-SignedHeaders%3Dhost%26X-Goog-Signature%3D019b40e6414c5844fd6b41bedae4a97d020433a10415f0ba8e85995fa00e53d26b3a42570f7543016104fce4c9555abe69acba081a88f7c9d09915b699c3af67ff208d7d6ecd04c77570ad5327182620bebdff1a6d6d2ed4b7b51970b89a4cf05e48d1d5c935f3acb28d0fef7848a83b4722661bfe112e7c65358157a93b3b7f05f4728d90b8b7c6e065ef869cb9298a9d0ab3e8d100fd5884e94eb0c6a0ffedae39021e4fcb9a82d8e496fcb660381f4ebc8a4d430e756a7f2e8d98bf6369103c16ba84a73ab377afaa566abeba12a2f9a91cc0894f534ef8592f9cb43d0ef9baac688ba78b34da5b65251f9ab97649d044a26fbe16fdd8d16638f1ba7140bc))

---

## 🗂️ Dataset

We use the **BraTS (Brain Tumor Segmentation)** dataset:

- 🔗 [Kaggle BraTS 2020 Dataset](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation)
- 🔗 [Official BraTS Dataset Site](https://www.med.upenn.edu/cbica/brats2020/data.html)

> 💡 After downloading, place the dataset inside a folder named `data/` in the project root.

---

## 📊 Results

| Metric                | Value     |
|------------------------|-----------|
| Dice Coefficient       | **0.994** |
| Test Accuracy          | **99.4%** |
| Loss (final epoch)     | ~0.02     |

---

## 🖼️ Example Output

Below is a sample output showing a slice from the 3D MRI scan and its corresponding predicted tumor mask:

| Original Slice | Tumor Mask Prediction |
|----------------|------------------------|
| ![Original](examples/original_slice.png) | ![Prediction](examples/predicted_mask.png) |

> Images are visualizations from model predictions using the BraTS validation set.

---

## 📦 Dependencies

- Python 3.8+
- PyTorch
- NumPy, Pandas
- nibabel
- matplotlib, seaborn
- scikit-learn

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Abdelrahman Abdelgawad**  
M.Eng. Data Science – TU Darmstadt  
📧 abdelrahmansaeed291@gmail.com  
