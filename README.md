

# 1908046_Image Caption Generator

**Project Duration:** 4th Year Undergraduate Project

An **Image Caption Generator** automatically creates descriptive captions for images using **CNNs** for feature extraction and **RNNs (LSTM)** for sequential text generation. Trained on the **Flickr8k dataset**, it produces human-like captions with impressive accuracy.

---

## 🔹 Features

- Generates natural language captions for images.
- Supports pre-trained CNNs: **VGG16, ResNet50, DenseNet201**.
- Uses **LSTM** networks for sequence modeling.
- Implements tokenization, padding, and one-hot encoding.
- Visual evaluation of image-caption pairs.

---

## 📂 Dataset

- **Images:** Flickr8k (8,000 images)
- **Captions:** Corresponding textual descriptions (`captions.txt`)
- Preprocessing: resizing, normalization, text cleaning

---

## 🛠️ Requirements

```bash
pip install numpy pandas matplotlib seaborn tensorflow tqdm
````

---

## 📝 Methodology

1. **Data Preprocessing**

   * Load images & captions, resize to 224x224
   * Normalize pixels, tokenize & pad captions

2. **Feature Extraction**

   * Extract image features with pre-trained CNNs

3. **Model Architecture**

   * Combine CNN features with LSTM sequence model
   * Layers: Dense, Embedding, Bidirectional LSTM, Dropout

4. **Training**

   * Optimizer: Adam
   * Callbacks: EarlyStopping, ModelCheckpoint, ReduceLROnPlateau

5. **Evaluation**

   * Generate captions for test images
   * Visualize results using matplotlib

---




## ⚙️ Usage

1. Clone the repo:

```bash
git clone https://github.com/yourusername/image-caption-generator.git
```

2. Place your dataset in the proper folder.
3. Run the Jupyter notebook or scripts.
4. Train the model or use pre-trained weights to generate captions.

---

## 🎯 Key Contributions

* Developed a **CNN + LSTM pipeline** for image captioning.
* Efficiently handled **data preprocessing, feature extraction, and sequence modeling**.
* Visualized captions for practical demonstration of AI-assisted image understanding.

---

## 🔗 GitHub Repository

[View Project Code](https://github.com/Nur0846/1908046_Image_Caption_Generator)

```



