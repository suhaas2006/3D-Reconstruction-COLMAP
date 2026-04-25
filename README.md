# 3D Reconstruction using COLMAP

## 📸 Input Images
![Input](input.png)

Multi-view images captured from different angles.

---

## 🔗 Feature Matching & Camera Poses
![Feature Matching](colmap.png)

SIFT features detected and matched across images. Camera positions estimated.

---

## 📍 Sparse Reconstruction
![Sparse](sparse.png)

Initial 3D structure generated using Structure from Motion (SfM).

---

## 🧱 Dense Reconstruction
![Dense](dense.png)

Dense point cloud created using Multi-View Stereo (MVS).

---

## 🧊 Final Output (Mesh)
![Final](output.png)

Final 3D mesh generated using Poisson Surface Reconstruction.

---

## 🔁 Pipeline Overview
![Pipeline](pipeline.png)

Complete pipeline from input images to final 3D model.

---

## 📊 Results
- ~100 input images
- ~5K–10K sparse points
- 100K+ dense points
- ~5–10 minutes runtime

---

## ⚠️ Challenges
- Noise in dense reconstruction
- Sensitive to image quality and overlap
- High computation time
