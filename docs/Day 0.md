# Day 0: Setup & Preparation

Before we begin hands-on sessions, participants must prepare their systems by installing or compiling a few essential tools.

We will primarily use the **Quantum ESPRESSO (QE)** suite and **WEST** code. Additionally, tools like `c2x`, `XCrySDen`, and `VESTA` will assist with tasks like input generation, post-processing, and visualization.

---

## 🖥️ Operating System Requirements

To ensure smooth performance and compatibility, a Unix-like environment is required. Recommended options:

- **Ubuntu** or **Debian** (preferred for beginners)
- **Windows Subsystem for Linux (WSL)** with Ubuntu, if you're using Windows

> ⚠️ Regardless of OS, you must have access to a terminal (`bash`, `sh`, or `zsh`) to execute commands.

---

## 🧰 Recommended Software

- **Code Editors**: If you are an advanced user, you're free to use `nano` or `vim`. However, I recommend editors like **VS Code**, **Sublime Text**, or **Atom**. I'll be using **VS Code** during the sessions.
- **Zoom**: All lectures and hands-on sessions will be conducted via Zoom. Please ensure it's installed and functional. In case it doesn't work, we'll be using Google Meet. 
- **Python (optional but highly recommended)**: While not required, basic familiarity with Python is a plus. It can be helpful for automating tasks and analyzing results.

---

## ⚙️ Installing Quantum ESPRESSO (QE)

=== "✅ Recommended (Source Build)"

    1. **Install prerequisites**:
    ```bash
    $ sudo apt install git wget build-essential
    $ sudo apt install g++ gfortran liblapack-dev
    $ sudo apt install libfftw3-dev libopenmpi-dev
    ```

    2. **Download the source**:
        ```bash
        $ cd ~
        $ mkdir opt
        $ cd opt
        $ git clone https://github.com/QEF/q-e.git
        ```

    3. **Configure the build**:
        ```bash
        $ cd q-e
        $ ./configure
        ```

    4. **Compile QE (parallelized)**:
        ```bash
        $ make -j$(nproc) all
        ```

        > 💡 Use just `make all` if you're on an old PC or single-core system.

    5. **Verify installation**:
        Check the `~/opt/q-e/bin/` directory. You should see executables like `pw.x`, `dos.x`, etc.

    6. **(Optional) Add QE to your PATH**:
        ```bash
        $ echo 'export PATH=$PATH:$HOME/opt/q-e/bin' >> ~/.bashrc
        $ source ~/.bashrc
        ```
=== "🧪 Alternate (Quick Install)"

    If you're unable to compile QE, try the Ubuntu package version (not recommended for advanced features):

    ```bash
    $ sudo apt install quantum-espresso
    ```

    If this fails or you encounter errors, post in the Facebook group or create a GitHub issue: [https://github.com/AbdulMuhaymin/Workshop-2025/issues/new](https://github.com/AbdulMuhaymin/Workshop-2025/issues/new)

---

## 🔧 Other Tools

We'll provide installation details for the following during the workshop:

* **`c2x`**: Can do a lot of things but we'll use it to prepare input files.
* **`VESTA`**: A powerful 3D visualization tool for structures and isosurfaces.
* **`XCrySDen`**: A visualization tool. Not required but helps if you have.
* **`WEST`**: A many-body perturbation theory code to be used in later sessions.

Stay tuned — detailed instructions for each of these will be shared separately.
