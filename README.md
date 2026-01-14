# 👋 Hi, I'm Rafael Cabral

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-medeiros-cabral/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=Aw4Aw_MAAAAJ&hl=en)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rafael.medeiros.cabral@gmail.com)

### AI Research Engineer & Ph.D. Statistician

I specialize in **AI robustness**, **LLM optimization (SFT/RL)**, and **probabilistic modeling**. Currently, I am a Senior AI Research Engineer at Huawei International, at their Norbert Wiener Research Center in Singapore. I do AI research and develop and deploy AI pipelines for their on-device assistant serving over 900 million users.

> 
> **Note on Contributions:** Since moving out of academia, most of my work is in closed-source proprietary repositories. Below are my featured public research projects and open-source contributions.
> 
> 

---

## 🚀 Featured Projects

### [ProofFlow](https://github.com/Huawei-AI4Math/ProofFlow) | *AI4Math: Neuro-symbolic Math Reasoning*

* **Role:** Main contributor (80%+ of code).

* **Impact:** Developed a dependency graph approach to formalize natural language math proofs/calculations into the Lean formal language. State of the art performance in automatic verification of mathematical proofs. Used to generate high quality synthetic proofs (to train LLMs).


* **[GitHub](https://github.com/Huawei-AI4Math/ProofFlow)** | **[Paper](https://openreview.net/forum?id=s9t2FJVsBH)** (ICLR 8664; pending final decision) 

### [Google Tunix Hackathon](https://www.kaggle.com/competitions/google-tunix-hackathon) | *Teaching Gemma3-1B to Think*

* **Focus:** Kaggle hackaton to finetune Gemma3-1B on Google v5e-8 TPUs with their new JAX-native Tunix library.

* **Novelty:** Optimized a novel training pipeline where, following the initial reasoning, the model enters a self-verification phase to rate its own output. Trained on math, coding and writing tasks. Data generation, reward function, and TPU optimization details on writeup and notebook below. 

* [**Writeup**](https://www.kaggle.com/competitions/google-tunix-hackathon/writeups/new-writeup-1765977529751)  | [**Notebook**](https://www.kaggle.com/code/rafaelcabral96/gemma-1b-forge-evolve)  

* **Status:** Pending judges' results.

---

## 🎓 PhD Projects Archive 

For a full history of my past Gitbub project, visit my previous Github account: [rafaelcabral96](https://github.com/rafaelcabral96).

### [ngvb](https://github.com/rafaelcabral96/ngvb) | Tests and robustness for Deep Hierarchical Models with Variational Bayes 

* **What it is:** An R package with a C++ backend designed to (1) test hidden layer assumptions in deep hierarchical models ("are the assumptions of the model hidden layers reasonable? Does the data contradict them?") and (2) if there are unreasonable Gaussian assumptions, fit the model with robust non-Gaussian alternatives (for higher robustness/accuracy). 

* **Impact:**  Only Principled (Bayesian) framework to test hidden layer assumptions without needing to fit alternative models. Variational Bayes implementation of non-Gaussian models achieved **100x faster inference** than MCMC and improved extreme event prediction accuracy by 20% on spatial climate data.

* [Project Link](https://github.com/rafaelcabral96/ngvb/) | [JASA paper](https://www.tandfonline.com/doi/full/10.1080/01621459.2023.2296704) | [JRSSB paper](https://academic.oup.com/jrsssb/article/87/3/632/7914952)

### [nigstan](https://rafaelcabral96.github.io/nigstan/) | *Spatio-temporal Modeling*

* Advanced spatio-temporal modeling implemented in Stan for robust statistical inference.

* [BA paper](https://projecteuclid.org/journals/bayesian-analysis/advance-publication/Controlling-the-Flexibility-of-Non-Gaussian-Processes-Through-Shrinkage-Priors/10.1214/22-BA1342.full)

### [mlswarm](https://github.com/rafaelcabral96/mlswarm) | *Particle Swarm Optimization*

* A custom implementation of the PSO algorithm for global optimization challenges.

