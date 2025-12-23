# resume
# ZIYU SHE

**Location:** 4056, Basel Switzerland  
**Phone:** +41772241767  
**Email:** ziyu.she@unibas.ch

---

## LANGUAGES

- **English:** Advanced (C1)
- **Chinese:** Native 

---

## WEBSITES, PORTFOLIOS, PROFILES

- https://github.com/SheZiyu?tab=repositories
- https://scholar.google.com/citations?user=V0KN5esAAAAJ&hl=en
- https://www.linkedin.com/in/ziyu-she-868ab0234/

---

## PERSONAL SUMMARY

Ph.D. Candidate at the University of Basel specializing in artificial intelligence and machine learning, with a focus on advancing **drug discovery through physics-based deep learning techniques**. Demonstrated expertise in optimizing complex systems and fostering collaboration to drive significant research outcomes in **medical imaging and robotics**.

---

## SKILLS

- Artificial Intelligence
- Machine Learning
- Robotics
- Python
- PyTorch
- Slurm/HPC
- Latex

---

## EXPERIENCE

### PH.D. CANDIDATE, 12/2023 - 11/2027
**University of Basel**

- Leveraged physics-based deep learning for drug discovery by integrating normalizing flows, SMC, and pocket-conditioned generative models with molecular simulation and energy functions to enhance sampling, free-energy estimation, and ligand design.

---

### RESEARCH ASSISTANT, 11/2021 - 04/2023
**Polytechnic University of Milan**

- Leveraged machine learning to advance medical imaging pattern recognition and optimize robotic controller design.

---

### TEACHING ASSISTANT, 09/2018 - 06/2021
**Sun Yat-sen University**

- Engaged in conferences emphasizing Statistics and Mathematics, Ordinary Differential Equations, and Dynamic Systems.

---

## PERSONAL INFORMATION

- **Date of birth:** 11/16/1995
- **Gender:** Female
- **Nationality:** Chinese
- **Hobby:** tennis, traveling, reading

---

## EDUCATION

### University of Basel, 12/2023 - 11/2027
**Ph.D.: Computer Science**
- Physics-based Deep Learning for Drug Design

---

### Polytechnic University of Milan, 11/2021 - 04/2023
**MSc: Computer Vision**
- Non-rigid 3D Reconstruction, Neural Rendering, Self-supervised Learning

---

### Sun Yat-sen University, 09/2018 - 06/2021
**MSc: Applied Mathematics**
- Differential Geometry, Differential Manifold, Soliton Equation and Integrable System, Partial Differential Equation
- **Outstanding Master Thesis:** https://github.com/SheZiyu?tab=repositories
- **GPA:** 3.31/4

---

### Guangdong University of Technology, 09/2014 - 06/2018
**BSc: Applied Statistics**
- Advanced Algebra, Analytic Geometry, Probability Theory
- **GPA:** 3.13/4

---

## PUBLICATIONS

- **She, Z.**, Marzullo, A., Destito, M., Spadea, M. F., Leone, R., Anzalone, N., et al. (2023). Deep learning-based overall survival prediction model in patients with rare cancer: a case study for primary central nervous system lymphoma. **International Journal of Computer Assisted Radiology and Surgery**. (Cited by 11)

- Su, H., Zhang, J., **She, Z.**, Zhang, X., Fan, K., Zhang, X., Liu, Q., Ferrigno, G., et al. (2022). Incorporating model predictive control and fuzzy approximation for robot manipulation under remote center of motion constraint. **Complex & Intelligent Systems**. (Cited by 11)

- Fu, J., Zhang, J., **She, Z.**, Ovur, S. E., Li, W., Qi, W., Su, H., Ferrigno, G., De Momi, E. (2021). Whole-body spatial teleoperation control of a hexapod robot in unstructured environment. In **2021 6th IEEE International Conference on Advanced Robotics and Mechatronics**. (Cited by 9)

- **Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces**. **Under review at ICLR 2026** (conference submission). 2025.

- STGen3D: Spatial-temporal-based Generator for Dense 3D Reconstructions of Non-rigid Objects. **First Author at ICCV 2023** (conference submission). 2022.

---

## HONORS AND AWARDS

- 09/2014 - 06/2021 Five Times of Outstanding Student Scholarship (top 5%)
- 12/2019 **Second Class of National College Mathematics Contest (Top 5%)**
- 12/2019 Second Class of the National College English Contest (Top 5%)
- 01/2016 **First class of Guangdong Automation Experimental Skill Contest (top 1%)**
- 04/2015 S Class of the American Mathematical Modeling Contest

---

## RESEARCH

### Ph.D. Project 1 – Amortized sampling with transferable normalizing flows for protein–ligand systems

- Developed a **transferable normalizing-flow / Boltzmann generator** that learns a proposal distribution over ligand conformations in protein binding pockets, using MD trajectories as training data.

- Combined the flow with **sequential Monte Carlo (SMC) + Langevin refinement** to efficiently generate near-equilibrium samples and estimate **free energies / ΔF between binding modes**, while retaining a principled treatment of densities and partition functions.

- Implemented a full **physics-aware data pipeline** (heavy-atom projections, pocket masks, bond-graph encodings, multi-mode DCD handling) to make the model robust across different ligands and poses.

---

### Ph.D. Project 2 – Pocket-conditioned molecular generation for structure-based drug design

- Built a **3D generative model conditioned on the protein pocket** that proposes **de novo ligand candidates** directly inside the binding site, without requiring a fixed starting molecule.

- Incorporated **geometric and simple physics/energy features** of the pocket to bias generation towards chemically valid, sterically compatible, and physically plausible ligands.

- Positioned as **a structure-based drug discovery tool**, complementary to docking: the model generates initial ideas in the right pocket, which can then be refined by docking, MD or free-energy methods.

---

### Agentic AI – Terminal-bench

- Created the **ode-solver-rk4** benchmark task to evaluate agent coding ability on implementing a numerical IVP ODE solver (e.g., RK4) under strict step-size/call-order constraints and accuracy requirements.
