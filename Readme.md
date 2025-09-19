Aqui está uma versão **minimalista em inglês** do README:

---

# 🧠 Multiple Sclerosis Datasets

This repository contains **datasets related to Multiple Sclerosis (MS)**, including MRI scans, lesion masks, and metadata for research and AI development.

---


---

## 🚀 Usage

Clone the repository:

```bash
git clone https://github.com/your-username/multiple-sclerosis-datasets.git
cd multiple-sclerosis-datasets
```

Example in Python:

```python
import nibabel as nib
import matplotlib.pyplot as plt

img = nib.load("datasets/raw/sample_T2.nii.gz")
data = img.get_fdata()

plt.imshow(data[:, :, 60], cmap="gray")
plt.axis("off")
plt.show()
```

---

## 📜 License

Data is **anonymized** and for **research purposes only**. Check `LICENSE` for details.

---

## 🙌 Contributing

Contributions are welcome! Open a **pull request** or create an **issue**.

---

If you want, I can also make an **even shorter “one-page” version** that fits neatly for GitHub without any code snippets. Do you want me to do that?
