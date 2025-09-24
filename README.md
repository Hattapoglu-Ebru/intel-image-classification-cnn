# Intel Image Classification — CNN

**Veri seti:** https://www.kaggle.com/datasets/puneet6060/intel-image-classification  
**Kaggle Notebook (public):** https://www.kaggle.com/code/ebruhattapolu/ebru-hattapo-lu 
**Çerçeve:** TensorFlow/Keras (GPU)

## Adımlar
- EDA (sınıf dağılımı, örnek görseller)
- Dataset: image_dataset_from_directory (train/val/test)
- Model: CNN + Data Augmentation
- Eğitim: EarlyStopping, ReduceLROnPlateau, ModelCheckpoint
- Değerlendirme: Accuracy/Loss grafikleri, Classification Report, Confusion Matrix
- Grad-CAM

### Eğitim Grafiği
![Accuracy & Loss](plots/acc_loss.png)

### Accuracy Grafiği
![Accuracy](plots/acc.png)

### Loss Grafiği
![Loss](plots/loss.png)

### Confusion Matrix
![Confusion Matrix](plots/confusion_matrix.png)

### Grad-CAM (opsiyonel)
![Grad-CAM](plots/gradcam_grid.png)

### Classification Report (metin)
👉 `plots/classification_report.txt` dosyasına bakınız.
