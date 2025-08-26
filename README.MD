# 🛡️ Exploit, Defend, and Detect Adversarial Attacks on Image-Based AI Systems  
**An Ethical Perspective**

👨‍💻 **Authors**  
- Mattia Gualandi — [mattia.gualandi2@studio.unibo.it](mailto:mattia.gualandi2@studio.unibo.it)  
- Alex Presepi — [alex.presepi@studio.unibo.it](mailto:alex.presepi@studio.unibo.it)  
- Alessandro Sciarrillo — [alessandr.sciarrill2@studio.unibo.it](mailto:alessandr.sciarrill2@studio.unibo.it)  

---

## 📄 Abstract  
The growing integration of deep learning models in critical domains has raised urgent concerns about their **vulnerabilities**. One of the most alarming threats is **adversarial attacks** on image-based AI systems — subtle perturbations to images that can mislead even the most accurate models, often without detection.  

These attacks challenge not only the **technical robustness** of AI but also raise **ethical concerns**, especially regarding human safety, fairness, and accountability.  

In this project, we:  
- 🔎 **Review and categorize** popular adversarial attack techniques.  
- 🧪 **Evaluate their impact** on standard vision models.  
- 🛡️ **Design and test defenses** to counteract these attacks.  
- 🚨 **Develop detection modules** to recognize corrupted inputs.  
- 🚗 **Apply case studies** in face recognition and vehicle detection, highlighting real-world risks.  

By combining **technical** and **ethical perspectives**, we emphasize the importance of AI systems that are not only performant but also **resilient and trustworthy** under adversarial conditions.  

---

## ⚙️ Installation  

Clone the repository and install the required dependencies:  

```bash
pip install -r requirements.txt
```

## 📦 Datasets  

Download the following datasets and place them inside the `datasets/` folder:  

1. 🧾 [PADetBench](https://huggingface.co/datasets/Jiawei-Lian/PADetBench/tree/main) — benchmark for evaluating adversarial detection.  
2. 🖼️ [ImageNet-100 (validation set)](https://www.kaggle.com/datasets/ambityga/imagenet100?select=val.X) — subset of ImageNet for large-scale image classification.  
3. 🙂 [Face Recognition Dataset](https://www.kaggle.com/api/v1/datasets/download/vasukipatel/face-recognition-dataset) — dataset for face identification tasks.  

---

## 🚀 Features  

- 🧨 Implementation of **adversarial attacks**: PGD, DeepFool, Carlini-Wagner, and more.  
- 🛡️ Evaluation of **defenses**: preprocessing, feature squeezing and adversarial training.  
- 🔍 Development of a **detector module** to identify adversarially perturbed inputs.  
- 🚗 Case studies on **face recognition** and **vehicle detection** to highlight real-world implications.  
- ⚖️ Integration of an **ethical perspective**, addressing fairness, safety, and accountability.  

---

## 📌 Ethical Perspective  

Adversarial robustness is not only a **technical challenge** but also a matter of **ethics**.  
We emphasize:  
- 🔐 **Security** — protecting systems from malicious exploitation.  
- ⚖️ **Accountability** — designing systems that remain trustworthy in safety-critical contexts.  

---

