# 🧠 LLM-Enabled Visual Stimuli Reconstruction using Brain Activity Signals (fMRI)

# Abstract
Reconstructing  visual stimuli from human brain activity  bridges  Neuroscience and 
Machine Learning  (ML)  pursuits.  Given  the  complexity of  the  image  generation 
pipeline from  signals data, this  area of research has seen limited  attention over 
the past years, in contrast  with other machine learning and Artificial  Intelligence
(AI) realms. The traditional approaches to the task have seen sub-optimal performance
due to the complexity of the task. The current research in the AI domain  has evolved 
with the revolution of  Large  Language  Models (LLMs), outperforming the traditional 
approaches in many downstream  procedures. However, these models  have not been fully 
explored for the task of image reconstruction from brain activity signals. Our exper-
iments on the Algonauts 2023 dataset demonstrate that proposed LLM-enabled methodology
significantly improves reconstruction quality, outperforming traditional baselines in 
both semantic and visual alignment.

---

## 📊 Dataset

We use the **Algonauts 2023** dataset, consisting of aligned fMRI recordings and corresponding image stimuli. Each image-fMRI pair is used to train and evaluate multiple reconstruction pipelines.

---

## 🧠 Models Implemented

- **GAN**: Baseline System: A generative adversarial network trained to produce realistic images conditioned on fMRI signals.
- **CNN + Autoencoder**: A traditional approach using convolutional encoders/decoders to address the research gap.
- **Transformer-Based Decoder**: Enhanced architecture using SOTA techniques, a sequence model (with and without attention mechanism) capturing complex spatial dependencies from brain activity.
- **LLM-Enabled Pipeline**: A Vision-LLM-based proposed pipeline, Combining CLIP, BLIP, and Stable Diffusion to generate images via caption intermediates from fMRI inputs.

---
## 👩‍💻 Developers Information

Developed by **[Sheema Firdous](https://www.linkedin.com/in/sheema-firdous-67b9b8181/)**;  
as a part of **Deep Neural Networks and Learning Systems** module assessment  at **[Sheffield Hallam University](https://www.shu.ac.uk/)**

Supervised by [Dr. Alejandro Jiménez Rodríguez](https://www.linkedin.com/in/aljiro/)
