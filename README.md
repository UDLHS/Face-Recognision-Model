# Face Recognition with Siamese Neural Network

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

## 👤 Author

- **Udula**

