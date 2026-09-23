# 👋 Hi, I'm Abdellatif Salah Eldin  

🎓 **B.Sc. Computer Science (AI Track)** — Arab Academy for Science, Technology and Maritime Transport (AASTMT), 2022–2026, GPA 3.56/4.0 (Excellent with Honors)  
🧠 Research-focused graduate interested in **Biomedical NLP, Retrieval-Augmented Generation (RAG), Medical Computer Vision, and Trustworthy AI Systems**  
🏥 Built **MediLink**, a full-stack medical AI application powered by HTAN (my medical image segmentation model) and my own biomedical RAG system, connected through multiple LLM components 
🩻 Co-developed **HTAN**, a medical image segmentation architecture, with a paper in preparation for submission  
📌 Goal: Research-based Master's (MSc) in Computer Science, with a direction in AI, Computer Vision, NLP, and Explainable AI (XAI)
📄 [Download my CV](#) <!-- replace with your GitHub CV link -->

---

## 🌐 Socials:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdellatif-salama-40a77921a)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:abdosalamaman@gmail.com)

---

# 🔬 Research Interests

- Computer Vision and Medical Image Segmentation for Healthcare  
- Biomedical NLP, Large Language Models (LLMs), and Retrieval-Augmented Generation (RAG)  
- Medical Information Retrieval and Clinical Question Answering  
- Multimodal Medical AI Combining Imaging and Clinical Text  
- Explainable AI (XAI) for Trustworthy, Citation-Grounded Medical Systems
---

# 🧪 Research

## 🩻 HTAN: Hyper TransAttUNet for Medical Image Segmentation

Co-developed **HTAN**, a segmentation architecture that adds manifold-constrained hyper-connections to the TransAttUNet bottleneck.

- Improved Dice by **1.05, 3.57, and 1.07 points** over the reproduced baseline on ISIC-2018 (skin lesions), GlaS (glands), and Data Science Bowl 2018 (nuclei)
- Responsible for data preprocessing, model architecture design, training optimization, and evaluation, including ablations on residual stream count and mHC block depth
- Fixed NaN training failures from fp16 overflow in the Sinkhorn-Knopp projection by moving it to FP32, with gradient clipping for stability
- Manuscript in preparation for submission to a peer-reviewed AI or medical imaging venue

## 🏥 MediLink: Biomedical Retrieval-Augmented Generation System

A biomedical RAG assistant for melanoma, skin cancer, and multiple myeloma.

### Key Components

- Biomedical ingestion pipelines over **PubMed, PMC, Cancer.gov, NHS, MedlinePlus, and clinical guideline PDFs**
- Biomedical embeddings using `pritamdeka/S-PubMedBert-MS-MARCO`
- **Weaviate hybrid retrieval** using dense search + BM25
- Biomedical reranking using `ncbi/MedCPT-Cross-Encoder`
- Query rewriting, HyDE expansion, multi-query retrieval, and MMR diversification
- Intent classification, out-of-scope detection, triage routing, and citation-grounded answer generation
- Local evaluation for retrieval relevance, coverage, faithfulness, grounding quality, and chunk diversity

### Benchmark Highlights

*30-question benchmark across melanoma, skin cancer, and multiple myeloma — small sample, indicative only:*

- Approx. **0.91 relevance**
- Approx. **0.95 coverage**
- Approx. **0.95 answer faithfulness**

---

# 📂 Featured Projects

## 🏥 MediLink: Biomedical RAG and Clinical QA System

A research-oriented biomedical retrieval system for evidence-grounded medical question answering.

**Main technologies:**  
`Python` `Weaviate` `PyTorch` `sentence-transformers` `HuggingFace` `MedCPT` `RAG` `LangGraph` `Docker` `AWS`

**Key features:**

- PubMed / PMC / medical guideline ingestion  
- Biomedical hybrid search with cross-encoder reranking  
- Query rewriting and retrieval diversification  
- Citation-grounded medical answer generation  
- Computer vision module for X-ray and MRI interpretation  
- Local RAG evaluation pipeline  

## 🩻 HTAN: Hyper TransAttUNet

A medical image segmentation architecture that expands the TransAttUNet bottleneck into multiple manifold-constrained residual streams.

**Main technologies:**  
`Python` `PyTorch` `Vision Transformers` `CNNs` `Medical Image Segmentation`

**Key features:**

- Manifold-constrained hyper-connections at the Self-Aware Attention bottleneck  
- Sinkhorn-Knopp doubly stochastic residual mixing  
- Evaluated on ISIC-2018, GlaS, and Data Science Bowl 2018  

---

# 💻 Tech Stack:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=sqlite&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

---

# 🧰 Technical Skills

## Programming  
`Python` `SQL` `Java` `C++`

## Machine Learning / Deep Learning  
`PyTorch` `TensorFlow` `scikit-learn` `HuggingFace Transformers` `sentence-transformers`

## Retrieval / NLP  
`Retrieval-Augmented Generation` `Biomedical NLP` `Hybrid Search` `Cross-Encoder Reranking` `MMR Retrieval` `Query Rewriting`

## Computer Vision / Healthcare AI  
`Medical Image Segmentation` `CNNs` `Vision Transformers` `Clinical QA` `Medical Information Retrieval` `Clinical Decision Support`

## Tools  
`Weaviate` `Docker` `Git` `Linux` `AWS` `CUDA` `Jupyter` `pandas` `NumPy`

---

# 🎓 Certifications

- **Retrieval Augmented Generation (RAG)** — DeepLearning.AI  
- **Natural Language Processing with Attention Models** — DeepLearning.AI  
- **Oracle Cloud Infrastructure 2025 Certified Data Science Professional**  
- **Supervised Machine Learning: Regression and Classification** — Stanford University / Coursera  
- **Advanced Learning Algorithms** — Stanford University / Coursera  

---

# 📊 GitHub Stats:

![](https://github-readme-stats.vercel.app/api?username=boodie04&theme=dark&hide_border=false&include_all_commits=false&count_private=false)

![](https://nirzak-streak-stats.vercel.app/?user=boodie04&theme=dark&hide_border=false)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=boodie04&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---

[![](https://visitcount.itsvg.in/api?id=boodie04&icon=0&color=0)](https://visitcount.itsvg.in)

---

# 🌍 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdellatif%20Salama-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/abdellatif-salama-40a77921a)
[![GitHub](https://img.shields.io/badge/GitHub-boodie04-black?style=for-the-badge&logo=github)](https://github.com/boodie04)
[![Email](https://img.shields.io/badge/Email-abdosalamaman%40gmail.com-red?style=for-the-badge&logo=gmail)](mailto:abdosalamaman@gmail.com)

---

⭐️ From [Abdellatif Salah Eldin](https://github.com/boodie04)
