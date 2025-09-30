# Prediksi Diabetes dengan Neural Network (Pima Indians Dataset)

## 🇮🇩 Deskripsi Proyek
Proyek ini menggunakan **dataset Pima Indians Diabetes** untuk membangun model prediksi apakah seorang pasien memiliki diabetes atau tidak.  
Dalam pengembangan model, beberapa modifikasi telah dilakukan dibandingkan baseline sederhana:

1. **Arsitektur Dense Layer**  
   - Ukuran hidden layer diperbesar menjadi **64 → 32 → 16** untuk memberikan kapasitas representasi yang lebih kuat.

2. **Optimizer dengan Learning Rate**  
   - Pada optimizer ditambahkan pengaturan **learning rate** agar proses training lebih stabil dan cepat konvergen.

3. **Callback dengan Early Stopping**  
   - Proses training ditambahkan **EarlyStopping** untuk menghentikan pelatihan ketika akurasi/validasi tidak lagi meningkat, sehingga menghindari **overfitting** dan menghemat waktu.

Dengan kombinasi ini, model menjadi lebih **stabil**, **akurat**, serta lebih mampu melakukan **generalization** pada data baru.

---

## en Project Description (English)
This project leverages the **Pima Indians Diabetes dataset** to build a predictive model for diabetes classification.  
Compared to a basic neural network, several improvements were implemented:

1. **Dense Layer Architecture**  
   - Hidden layer sizes were increased to **64 → 32 → 16**, giving the network stronger representation power.

2. **Optimizer with Learning Rate**  
   - The optimizer includes a custom **learning rate** setting to stabilize training and speed up convergence.

3. **Callback with Early Stopping**  
   - Training incorporates **EarlyStopping** to halt the process when validation accuracy stops improving, preventing **overfitting** and saving computation time.

With these adjustments, the model achieves better **stability**, **accuracy**, and **generalization** to unseen data.

---

## 🔧 Teknologi / Technologies
- Python  
- TensorFlow / Keras  
- NumPy & Pandas  
- Matplotlib  

---

## 📊 Dataset
- **Sumber**: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- **Fitur**: 8 kolom medis (glucose, insulin, BMI, umur, dll.)  

