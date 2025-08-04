# 🧠 Face Verification with Siamese Neural Network (Experimental)

This project is a personal implementation of a **Face Recognition Model** using a **Siamese Neural Network**, based on the foundational paper:

> **"Signature Verification using a Siamese Time Delay Neural Network"**  
> *Jane Bromley et al., 1993*

---

## 🧠 What is a Siamese Neural Network?

A Siamese Neural Network is designed to learn **similarity between two inputs**. In the context of face recognition, it learns to determine whether two face images belong to the **same person** or **different people** by comparing their feature embeddings.

---

## 📌 Project Summary

- ✅ Built using the Siamese Network architecture.
- 📷 Takes two face images and predicts whether they are of the same person.
- 🧪 Uses **contrastive loss** to train the model on image pairs.
- 🧍‍♂️ Currently trained only on **my face**, and works accurately for that case.
- ⚠️ Not suitable for general face recognition tasks yet — more training data and tuning needed.

---

## 🛠️ Tools Used

- Python
- TensorFlow
- NumPy
- OpenCV (for image preprocessing)

---

## 📄 Paper Reference

- [**Signature Verification using a Siamese Time Delay Neural Network** (1993)](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)  
  *Jane Bromley, Isabelle Guyon, Yann LeCun, Eduard Säckinger, Roopak Shah*

---

## ⚙️ Next Steps (Future Improvements)

- [ ] Train with more diverse faces
- [ ] Improve accuracy with better preprocessing and augmentation
- [ ] Add GUI or simple web interface for testing
- [ ] Evaluate with standard datasets (e.g., LFW, VGGFace2)

---

This is an experimental project where I implemented a **face verification system** using a **Siamese Neural Network**, inspired by the original Siamese paper on one-shot learning. The model takes a image and varified the user.

---

## 🚀 What I Built

- A custom Siamese neural network using **TensorFlow/Keras** *(or PyTorch – update as needed)*.
- Implemented **contrastive loss** to train the model to distinguish between similar and dissimilar face pairs.
- Created a custom data loader that generates image pairs on the fly for training.
- Built an inference script to test image pairs manually *(or with webcam if implemented)*.

---

## ⚠️ Limitations

> This was built as a **fun and exploratory project**, so accuracy is currently limited due to:
- A **small dataset**
- No hyperparameter tuning
- Minimal augmentation and preprocessing

Despite that, it helped me understand:
- Deep metric learning
- How face recognition models (like FaceNet) work
- How to build pair-based training pipelines

---

## 🎯 Why I Did This

I wanted to try something beyond traditional classification models and challenge myself to implement a paper-style model from scratch.

This project was built:
- For **fun and experimentation**
- To understand **contrastive learning** and **one-shot learning**
- As a foundation to improve and iterate on in the future

---

## 👤 Author

- **Udula**

