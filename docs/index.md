# Welcome 
## Exploring atomic scale physics using ab-initio calculation - Workshop 2025
This workshop is focused on the use of the ab-initio (first-principles) calculation to investigate atomic scale physics. We will start with some basics of electronic structure and the Density Functional Theory (DFT) and move on to some applications using a code called Quantum ESPRESSO (QE). We will then introduce beyond-DFT methods such as DFT+U and touch upon some Many-Body Perturbation Theory (MBPT) concept such as Green's function based approaches and how to use them. This workshop is intended for beginners in DFT-based simulations without any prior experience. If you already have some familiarity, it might also be helpful depending on your level of familiarity. Please refer to the topics to be covered and/or contact me directly if you are unsure whether this is gonna be helpful to you. This workshop includes both lecture sessions as well as hands-on sessions where we will do simple DFT calculations.

The choice of the software is QE since it is free, open-source and easy to use. Installation and troubleshooting of all the codes (QE, WEST, VESTA, c2x, etc.) will be covered in the workshop. Note that if you need to work with other codes such as VASP, CASTEP, SIESTA etc., you are still encouraged to attend since once you get the basics, switching code is not a big barrier. You just need to switch the syntax, the working principle remains more-or-less the same across all plane-wave based codes. 

The workshop will be conducted primarily in Bangla but written materials will be in English or bilingual for clarity (I personally don't find Bangla suitable in scientific communication). Below I provided a tentative schedule. This schedule is flexible, i.e., if there is some consensus among attendees on the timing, I can adjust the schedule up to certain extent. If you cannot attend SOLELY due to timing, let me know. Also, depending on how much interactive the sessions are, we might have to shuffle some of the topics due to time constraint.
## Intended participants
- If you are pursuing or wants to pursue a research path in material modeling, first-principle calculations.
- If you are in your 3rd year of study or at least finished your sophomore year. 
- If you are pursuing MS research work related to computational material science and this track is new to you.
## Ground rules
This workshop is intended to be personalized. So to make sure that only the interested ones register, there are some ground rules and you must commit to these rules:

- You must be familiar with quantum mechanics at the level of any modern physics textbook covers. Such familiarity should include Schrodinger's equation, the particle in a box system, and familiarity to the solution of Hydrogen atom and simple harmonic oscillator. I guess at minimum, this corresponds to the sophomore level (2 years of curriculum) physics, chemistry or material science. If you are unsure whether you have the prerequisite, contact me directly to make sure.
- You have a computer with good internet connection (all the sessions will be through Zoom).
- You will not miss any lecture/hands-on sessions and will submit assignments even if incomplete.
- Since this will be an online workshop, response from your side is expected to keep the sessions interactive. I will not enforce camera-on rules due to privacy and security purpose, but please be attentive and responsive.
- Recording is **NOT** allowed. I will **ALSO NOT** be recording from my side. If you miss any sessions, you have to rely on lecture notes/materials provided. If there is a valid reason you miss a lecture/hands-on session, contact me directly. We may arrange something. 
- You will download and prepare the files before the workshop starts. Detailed instruction will be sent once you are registered.
- This is an online workshop and a **NOT** a free one. Moreover, there will be no certificate and no formal recognition. So please do not register unless you genuinely want to learn this topic or need DFT in your research work.
- The incentives to attend this workshop is that 
	- By the end, you'll have a portfolio with a mini ab-initio research project
	- During the workshop, you'll get a 1-to-1 support
	- You will be learning from a fellow learner and not from an expert who might have forgotten what it's like to be a beginner.  
## Registration
Please, do not send any money without confirming your seat first. If you are interested, just fill out the google form, and I will reach out to you within 48 hours. If you satisfy the prerequisites, you can then pay through bKash/bank transfer and confirm your seat. The regular payment is 1500 BDT. Payment details will be shared later with accepted applicants. 
There is a strict need-based scholarship which you can apply for during the registration. If granted, there will be a discount applied. Note that you are advised to apply for this scholarship only if you are unable to pay the regular payment due to financial constraint. 

Google form: [https://forms.gle/cBNxKkyvKp8WQAgf6](https://forms.gle/cBNxKkyvKp8WQAgf6)
## Contact
[muhaymin.ph@gmail.com](mailto:muhaymin.ph@gmail.com), [+90 552 503 74 84](tel:+905525037484) (WhatsApp)

## Tentative schedule and topics to be covered
In *Day 0-5*, we will have dedicated lecture sessions and hands-on sessions. The practice-and-support-sessions are not interactive. Through some virtual platform (to be decided later), participants can talk about any problem they might face or have general discussions. 

| Session                       | Date                         |
| ----------------------------- | ---------------------------- |
| Day 0                         | June 28-29 (Saturday-Sunday) |
| Day 1                         | July 5 (Saturday)            |
| Day 2                         | July 6 (Sunday)              |
| Practice and support sessions | July 7-11 (Monday-Friday)    |
| Day 3                         | July 12 (Saturday)           |
| Day 4                         | July 13 (Sunday)             |
| Practice and support sessions | July 14-18 (Monday-Friday)   |
| Day 5                         | July 19 (Saturday)           |
| Practice and support sessions | July 20 (Sunday)             |

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