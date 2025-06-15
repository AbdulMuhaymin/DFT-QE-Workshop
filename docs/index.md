# Welcome

![Workshop Cover](https://raw.githubusercontent.com/AbdulMuhaymin/Workshop_2025/main/docs/assests/cover.png)

## Workshop 2025: Exploring Atomic Scale Physics with Ab-initio Calculations

This workshop introduces participants to ab-initio (first-principles) methods for studying atomic-scale physics. We'll begin with foundational concepts in electronic structure and Density Functional Theory (DFT), and then apply them using **Quantum ESPRESSO (QE)**. The course continues with advanced beyond-DFT topics like **DFT+U** and an introduction to **Many-Body Perturbation Theory (MBPT)** through Green's function-based methods.

Designed for **beginners**, the workshop also accommodates those with partial familiarity looking to deepen their understanding. Both **lecture** session and **hands-on** sessions are included.

We use **Quantum ESPRESSO** due to its open-source nature, flexibility, and user-friendliness. Installation and setup support for QE and related tools like `WEST`, `VESTA`, `XCrySDen`, and `c2x` will be provided.

> ⚠️ This workshop will be conducted primarily in **Bangla**, but all materials (slides, notes) will be in **English or bilingual** for clarity. The schedule is flexible to accommodate participant availability.

---

## 👤 Who Should Join

- Undergraduate (3rd year or beyond) students interested in materials modeling or first-principles calculations
- MS/graduate students working in computational materials science with limited background in DFT
- Anyone looking to start research in ab-initio electronic structure methods

---

## 📌 Ground Rules

To maintain a personalized and high-engagement environment, participants must agree to the following:

- Be familiar with basic quantum mechanics: Schrödinger equation, particle in a box, hydrogen atom, harmonic oscillator.
- Have a computer with stable internet (Zoom will be used for sessions).
- Attend **all lectures and hands-on sessions**, and submit assignments (even if incomplete).
- Be interactive: No camera requirement, but active participation is expected.
- **No recording** is allowed and no sessions will not be recorded. Lecture notes/materials will be shared.
- Prepare all required files before the workshop (instructions will follow upon registration).
- This is a **paid, non-certificate** workshop — only join if you're genuinely interested.

### 🎁 What You’ll Gain

- A small **research portfolio** with ab-initio simulations
- **1-to-1 support** during sessions
- Learn from a fellow learner with beginner-friendly explanations

---

## 📝 Registration

Do **not send any payment** until your seat is confirmed.

- Fill the Google Form: [https://forms.gle/cBNxKkyvKp8WQAgf6](https://forms.gle/cBNxKkyvKp8WQAgf6)
- You will be contacted within 48 hours
- If you are accepted, you can confirm your seat by paying **1500 BDT** via bKash or bank transfer (details after confirmation)

### 💸 Scholarship

A strict **need-based** scholarship is available. Apply only if you have genuine financial constraints.

---

## 📬 Contact

- **Email**: [muhaymin.ph@gmail.com](mailto:muhaymin.ph@gmail.com)
- **WhatsApp**: [+90 552 503 74 84](tel:+905525037484)

---

## 🗓️ Tentative Schedule 

| Session                       | Date                         |
| ---------------------------- | ---------------------------- |
| Day 0                        | June 28–29 (Sat–Sun)         |
| Day 1                        | July 5 (Saturday)            |
| Day 2                        | July 6 (Sunday)              |
| Practice/Support             | July 7–11 (Mon–Fri)          |
| Day 3                        | July 12 (Saturday)           |
| Day 4                        | July 13 (Sunday)             |
| Practice/Support             | July 14–18 (Mon–Fri)         |
| Day 5                        | July 19 (Saturday)           |
| Practice/Support             | July 20 (Sunday)             |

---

## 📚 Topics Overview


### Day 0: 
*(will be done through Discord/Messenger before the workshop starts)*
- Setting up computational environments
- Downloading all the files to be used in the hands-on sessions
### Day 1: Introduction to DFT
- 07:30 PM - 08:20 PM **(Lecture session)**
	- An absolute beginner's guide to DFT - 20 minutes
		- DFT as a black-box
	- Approaches of doing DFT - 30 minutes
		- Approximations used in DFT
		- Born-Oppenheimer approximation (frozen core)
		- Pseudopotential
		- an introduction to QE and comparison with other codes
- 08:30 PM - 09:20 PM **(Lecture session)**
    - Structural and electronic properties of solids - 50 minutes
	    - Brillouin zone integration
	    - smearing methods
	    - basis set
	    - supercell
	    - electronic structure (band, DOS)
	    - metallicity of solids
- 09:30 PM - 10:20 PM **(Hands-on session)**
    - Introduction to Linux environments and basic commands - 10 minutes
	- DFT calculation of Si semiconductors using QE - 40 minutes
	    - self-consistent field calculation
	    - non self-consistent field calculation
	    - band structure calculation
	    - density of states calculation
	    - plotting tools
- 10:20 PM - **(Open session)**
	- Kahoot
    - Discussion
### Day 2: Practical aspects of DFT
- 07:30 PM - 08:20 PM **(Lecture session)**
	- A review of Day 1 - 10 minutes
	    - Structure optimization, and others - 40 minutes
		- XC functional
	    - Hellman-Feynman theorem
	    - Ionic vs cell relaxation
	    - PWTK, shell scripting
- 08:30 PM - 09:20 PM **(Hands-on session)**
	- Structural properties - 30 minutes
		- lattice parameters
	    - relaxation
	    - variable-cell relaxation
	    - Handling hexagonal cells
	- Convergence testing - 20 minutes
	    - kinetic energy cutoff
	    - k-points
	    - broadening
	    - supercell sizes, charge density,
- 09:30 PM - 10:20 PM **(Hands-on session)****
	- DFT in molecules - 20 minutes
	    - bond length, angle, and dihedrals
	    - quantum dots
    - Improvement of some property - 30 minutes
	    - LDA to GGA
	    - band gap
- 10:20 PM - **(Open session)**
	- Kahoot
    - Discussion
### Day 3: Magnetization & Hubbard parameters
- 07:30 PM - 08:20 PM **(Lecture sessions)**
	- Magnetism - 40 minutes
	    - origin of magnetism in materials
	    - spin-polarized DFT
    - Hubbard parameter: DFT+U - 10 minutes
- 08:30 PM - 09:20 PM **(Hands-on session)**
	- spin-polarized calculation
    - density of states
    - exchange splitting
- 09:30 PM - 10:20 PM **(Hands-on session)**
	- DFT+U calculation
	- Calculating the U parameters
	- U, V, and J parameters
- 10:30 PM - **(Open sessions)**
	- Kahoot
    - Discussion
### Day 4: Doping, defects, & lower dimensional materials
- 07:30 PM - 08:20 PM **(Lecture sessions)**
	- Doping & defects - 30 minutes
	    - manipulating doping concentration
	    - isolated defect properties
    - 1D and 2D materials - 20 minutes
- 08:30 PM - 09:20 PM **(Hands-on session)**
	- Doped material properties
    - Lower dimensional materials
- 09:30 PM - 10:20 PM **(Hands-on session)**
    - Defect formation energy
    - Thermodynamic stability
- 10:30 PM - **(Open sessions)**
	- Kahoot
    - Discussion
### Day 5: Excited states & many-body physics
- 07:30 PM - 08:20 PM **(Lecture sessions)**
	- Optical properties - 20 minutes
    - Many-body physics - 30 minutes
	    - Green's function formalism
	    - Hedin's equation
	    - GW approximation
- 08:30 PM - 09:20 PM **(Hands-on session)**
	- Independent particle approximation
	- Local field effect 
	- Random Phase Approximation
- 09:30 PM - 10:20 PM **(Hands-on session)**
    - GW self-energy calculation
    - Quasiparticle correction
- 10:30 PM - **(Open sessions)**
	- Kahoot
    - Discussion