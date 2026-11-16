<h1 align="center">Hadi Azizpour Lindi</h1>

<p align="center">
  <b>Machine Learning &amp; AI Engineer — LLM systems, interpretable deep learning, signals and time series</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hadiazizpourlindi/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://link.springer.com/10.1007/s11571-026-10458-8"><img src="https://img.shields.io/badge/Paper-Cognitive%20Neurodynamics%202026-1a7f37?style=flat-square" alt="Publication"></a>
  <a href="mailto:hadi.a.lindi@gmail.com"><img src="https://img.shields.io/badge/Email-C14438?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About

I build **interpretable deep-learning systems for high-dimensional signal data** — models that are
accurate *and* can say which physiological features drove the decision.

- 🧠 PhD candidate in Cognitive Science at ICSS, defense scheduled for **November 2026** — interpretable deep
  learning for early detection of Mild Cognitive Impairment and Alzheimer's disease from EEG.
- 🔬 5+ years across the full ML lifecycle: data pipelines → feature engineering → architecture →
  training → evaluation → explainability. Transformers, attention, graph neural networks, CNN/LSTM.
- 🌊 Before neuroscience, five years as a processing geophysicist on large-scale seismic data —
  the same signal-processing craft, different physics.
- 📄 Peer-reviewed researcher: 5 publications on EEG deep learning and SVD-based seismic denoising.

### Selected work

| Project | What it does |
| --- | --- |
| **Metis-Auto** (team project, private) | LLM model router for a production Persian chatbot platform: a fine-tuned classifier predicts topic and difficulty and sends each message to the cheapest model that still answers well. 18% to 44% lower answering-model cost on a replay of real traffic; 87% difficulty accuracy on an unseen month (baseline 75%). FastAPI + Docker. |
| **[eegkit](https://github.com/HadiAzizpourLindi/eeg-toolkit)** | Minimal, non-destructive EEG preprocessing: raw recording → deep-learning-ready `(epochs, channels, samples)` tensor plus a provenance manifest. Montage is never hard-coded, mains frequency is measured rather than assumed, ICA is off by default at every stage. 157 tests, CI green. |
| **[seiskit](https://github.com/HadiAzizpourLindi/seiskit)** | Exploration seismic processing toolkit — SEG-Y in, migrated section out. On PyPI: `pip install seiskit`. |
| **[NeuroBeats](https://neurobeatsclinical.netlify.app/)** | Binaural beat generator that runs in the browser with the Web Audio API. |

### Research

**Interpretable Feature-Transformer Framework for Cross-Subject MCI Detection Using Nonlinear
Dynamical and Graph-Theoretic EEG Features** — *Cognitive Neurodynamics*, Springer Nature (2026).
[10.1007/s11571-026-10458-8](https://link.springer.com/10.1007/s11571-026-10458-8)

Earlier work: four papers on attenuating random and ground-roll noise in seismic data with
Hankel/frequency-domain SVD in the F-X domain (Tehran 2012 & 2014, Istanbul 2012, Kiev 2012).

### Toolbox

**Learning** — PyTorch · TensorFlow/Keras · scikit-learn · Transformers & attention · GNN/GAT · CNN/BiLSTM · EEGNet · SHAP
**Signals** — MNE · EEGLAB · SciPy · spectral & F-X domain methods · SVD · connectivity & graph metrics
**LLM systems** — fine-tuning · model routing · RAG · LLM-as-judge evaluation · agents
**Engineering** — Python · FastAPI · Docker · MATLAB · NumPy/Pandas · pytest · GitHub Actions · reproducible pipelines

### Currently

- Finishing the dissertation — defense scheduled for **November 2026**
- Completed the Rahnema College Machine Learning & AI Engineering Bootcamp (Nov 2026)
- Building a feature-extraction library on top of `eegkit`: nonlinear dynamics, coherence, graph metrics
- Open to **machine learning and AI engineering** roles: LLM systems, signal and time-series analytics, biomedical AI

<p align="center"><sub>hadi.a.lindi@gmail.com · Tehran, Iran</sub></p>
