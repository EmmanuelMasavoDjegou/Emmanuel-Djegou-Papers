# 🧠 Research by Emmanuel DJEGOU

I am a **Ph.D. candidate in Statistics** at **Missouri University of Science and Technology**, specializing in **deep learning methods for survival analysis**. This repository showcases my research projects, code, and findings.

##  🎯 Interests

- Recurrent Event Modeling  
- Accelerated Life Models  
- Neural Networks

## 📂 Projects

### Paper 1: Efficient Estimation in Semiparametric Accelerated Life Models for Recurrent Events

Accelerated life models, such as the Accelerated Failure Time (AFT) model, relate covariates to log event times under right-censoring and extend naturally to recurrent events via the Accelerated Gap Time (AGT) model. While they provide intuitive interpretations and serve as meaningful alternatives to the Cox model, they often overlook the effects of interventions occurring between events—common in fields like reliability engineering and biomedical research.

- Propose a broader class of **semiparametric accelerated life models** incorporating an **effective age process** to capture intervention effects.
- Develop a **sample-based weighted efficient score function** using parametric submodels to address infinite-dimensional baseline hazards and non-monotone score functions.
- Estimators are **consistent and asymptotically normal**.
- Validated via simulations and application to real biomedical data.

---

### Paper 2: Extending Virtual Age Models via Dynamic Covariate Acceleration for Biomedical Applications

Traditional virtual age models assume covariates influence only baseline hazard of initial failure times, ignoring their effect on the virtual age reflecting post-intervention condition.

- Introduce a **general class of virtual age models** where **time-varying covariates directly influence virtual age**.
- Offers flexible modeling of recurrent events (e.g., post-surgical readmissions), accounting for censoring and imperfect interventions.
- Inference based on **semiparametric efficiency theory** via reparameterization of baseline intensity and monotone estimating equations.
- Estimators are **consistent and asymptotically normal**.
- Propose a **novel failure time simulation algorithm**.
- Demonstrated improved accuracy on biomedical datasets.

---

### Paper 3: Modeling Recurrent Events Using Deep Neural Networks in Accelerated Failure Time Models

Recurrent event data commonly arise in biomedical and reliability studies, with multiple failures per subject.

- Extend **DeepR-AFT** framework to recurrent events via **DeepR-Recur**, a DNN model with **Gehan-type rank loss**.
- Capture nonlinear relationships between covariates and event times over multiple occurrences.
- Include a **subject-level frailty term** for within-subject dependence.
- Employ **stratified subsampling** for stable learning amid censored and irregularly spaced events.
- Simulations and real-world data show DeepR-Recur outperforms traditional AFT and Cox models in accuracy and interpretability.


___

## 📜 Research Framework

![Presentation3](https://github.com/user-attachments/assets/f781631a-a0ff-4e02-bf4b-570645f406ec)

---

## 📫 Contact

📧 emmanueldjegou5@gmail.com

🌐 [LinkedIn](https://www.linkedin.com/in/emmanuel-djegou-5652b2254/) 

🐙 [GitHub](https://github.com/EmmanuelMasavoDjegou)

---

## 📜 License

All papers are © by default unless stated otherwise. Contact me for collaboration or reuse.
