# Skin-Lesion-Segmentation-using-K-Means-Clustering
This project focuses on skin lesion segmentation using K-Means Clustering in Python. The experiment is performed using a Jupyter Notebook compatible with Google Colab.

---

## 📘 Access the Notebook

You can open the notebook directly via the link below:  
🔗 (https://colab.research.google.com/drive/1OUsJ42IcSNe0lkjMDUL4wBf95xfinit_?usp=sharing)

Alternatively, download the attached `.ipynb` file and open it in Google Colab or Jupyter Notebook.

---

## 📂 Mounting Google Drive

To properly access the dataset, follow these steps:

1. Download the dataset folder from the link below:  
   🔗 (https://drive.google.com/drive/folders/1EPJhltdUbPrFqOQQtQhDuqLkG14HicLE?usp=sharing)

2. Upload the folder to **your Google Drive**.

3. Make sure the paths in the notebook match your Drive structure.

---

## 🖼️ Update Image Paths

To test different images, modify the following code snippet:

```python
# --- Load image ---
img = cv2.imread('/content/drive/My Drive/MLA1/IMD019/IMD019_Dermoscopic_Image/IMD019.bmp')

# --- Load Ground Truth Mask ---
ground_truth = cv2.imread('/content/drive/My Drive/MLA1/IMD019/IMD019_lesion/IMD019_lesion.bmp', cv2.IMREAD_GRAYSCALE)
