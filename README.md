# Maksim Baryshnikov

**ML Engineer · Data Scientist · Data Analyst**
3rd-year Mathematics and Computer Science student, Voronezh State University (VSU)

I apply machine learning to problems from the natural sciences and work at the intersection of mathematics, ML and scientific computing: neural network interatomic potentials, hallucination detection in CT reconstruction, and dynamical chaos. I teach calculus to first-year students and write AI security tasks for national CTF competitions.

---

## Projects and research

### Hallucination detection in CT reconstruction
An algorithm that checks whether a neural CT reconstruction contains false details (sparse-view, low-dose settings): a detail is projected onto the kernel of the forward operator, then consistency with the measurement and the behavior of the decoder are verified.
- Comparison of decoders (FBP, TV regularization, neural networks) on Visible Human Project data
- Automatic detail selection and calibration of the false-alarm threshold
- Evaluation: RMSE, SSIM, ROC analysis, bootstrap confidence intervals, Wilcoxon test

### Neural network interatomic potentials (Behler–Parrinello method)
A neural network potential for quantum chemistry calculations and molecular dynamics of crystal lattices. Atom-centered symmetry functions describe the local environment of an atom in the lattice.

### Dynamical chaos theory
Studying dynamical chaos theory and writing a research paper on the problem of the gravitationally excited Fermi oscillator.

### Abinit and Atomic Simulation Environment (ASE) on a cluster
Established collaboration with the university supercomputing center and assembled a team to deploy Abinit + ASE on a computing cluster (OpenMP, MPI).

## Stack

| Area | Tools |
|---|---|
| ML and data | PyTorch, scikit-learn, pandas, SQL |
| Languages and tools | Python, C, Git, GitLab |
| Parallel computing | OpenMP, MPI |
| Mathematics | calculus, linear algebra, probability and statistics, complex analysis |

## Experience

- **Teaching Assistant, Calculus**, Faculty of Computer Science, VSU (since September 2026): practice sessions for first-year students, materials for assessments.
- **CTF Task Author (AI Security and Crypto)**, VrnCTF 2026 (February – May 2026):
  - a neural network weight analysis task: the flag is encoded as a rank-1 perturbation in the weight difference of two ONNX models;
  - an OCR model reverse-engineering task: recovering the model's alphabet and re-encoding a reference message;
  - maintained the task infrastructure throughout the competition.
- **Organizing Committee Secretary**, VrnCTF and CenterCTF 2026 (February – May 2026): competition rules and regulations, participant appeals, communication with the Competitive Programming Federation.
- **Deputy Head of the Student Research Society**, Faculty of Computer Science, VSU (since May 2026): recruitment for the Science and CTF tracks, leading the technical team that deploys competition platforms.

## Competitions and hackathons

- **CTF:** VrnCTF, CenterCTF, Kubok CTF, UralCUP
- **Hackathons:** MPIT, DANO

## Education

- Voronezh State University, Faculty of Computer Science: B.Sc., Mathematics and Computer Science (2024–2028)
- Yandex Education: Backend Developer in Python (associated program), ML and Big Data (specialization), Industrial Programming in Python

## Contact

- Telegram: [@pytaia](https://t.me/pytaia)
- Email: pytaia@yandex.ru
- Voronezh, open to relocating to Saint Petersburg · remote / hybrid · full-time
