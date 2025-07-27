# 🧠 AI Fashion Tagger – Meesho Visual Taxonomy

**⏱ Duration**: Jan 25 – Apr 25  
**🛠 Tech Stack**: Python, PyTorch, React.js, Django, Tailwind CSS  
**🔗 GitHub**: [GitHub Repo](https://github.com/Prince22378/Meesho_VE_3) \
**🔗 Website link**: [Website Link](https://meesho-ve-3-frontend.onrender.com/) 


---

## 🧩 The Fashion Attribution Challenge

Manual fashion tagging is a **billion-dollar bottleneck** for fashion e-commerce platforms. With ever-expanding product catalogs, tagging new items accurately and consistently has become unscalable.

---

## 📊 The Scale of the Problem
- With manual input taking around one minute per product, scaling to millions of products in a seamless flow poses a significant operational challenge.

  Manual tagging struggles with:

- 🐌 **Speed Bottleneck**: Products can take days to become searchable due to 10× slower throughput.
- 📈 **Scalability Nightmare**: Tagging needs grow linearly with SKUs, causing unsustainable costs.
  
---

## 🚀 Our AI-Powered Solution

A robust, full-stack system to **auto-tag fashion product images** using a deep learning pipeline, with real-time predictions and downloadable reports.

### 🔑 Key Model Features

- ✅ Multi-label classification (5 - 10 fashion attributes on 5 categories of clothing)
- 🔁 Transfer learning with domain-specific tuning

---

## 📈 Performance Highlights

| Metric                 | Value             |
|------------------------|------------------|
| ⚡ Inference Time      | **< 1s**         |
| 🏷 Attributes Handled  | **5 - 10** attributes for 5 clothing categories|
| 🎯 Evaluation Metric   | **73% harmonic F1** |

---

## 🌐 System Architecture
```
Frontend (React.js + Tailwind) -> Backend (Django REST API) -> Model Server (PyTorch) -> Attribute Output (JSON, CSV, Reports)
```
