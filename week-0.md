\# RISC-V Reference SoC Tapeout Program

\## Week 0 Assignment

\*\*Name:\*\* MOHAMED AAFTAAB M R \*\*University:\*\* Chennai Institute
of Technology \*\*Program:\*\* RISC-V Reference SoC Tapeout Program
\*\*Week:\*\* 0

---

\### 1. Getting Started with Digital VLSI SoC Design and Planning

This week, I started exploring the fundamentals of digital VLSI (Very
Large Scale Integration) SoC (System on Chip) design and planning. I
learned how an SoC integrates various digital components such as
processors, memory, and peripherals on a single chip, and understood the
benefits of this integration in terms of performance and efficiency. I
also reviewed the essential steps involved in planning an SoC project,
including specification, architecture design, verification, and tapeout.

---

\### 2. Tools Installation \& Verification

For my development environment, I completed the following tool
installations and verifications:

\- \*\*Git:\*\* Installed and configured for version control and GitHub
submissions.  - \*\*Docker:\*\* Set up to enable isolated and
reproducible tool environments.  - \*\*Yosys:\*\* Installed as the
synthesis tool for RTL design.  - \*\*OpenROAD/OpenLane:\*\* Set up for
automated physical design and chip layout tasks.  - \*\*iverilog:\*\*
Installed for simulation and verification of Verilog code.  - \*\*RISC-V
GNU Toolchain:\*\* Installed for compiling and running RISC-V programs.

### GTKWave Installation & Verification  
```bash
gtkwave -v


\#### Icarus Verilog (iverilog) Verification ```bash iverilog -v
``` !\[Icarus Verilog](images/22222222.png)

\#### Yosys Verification ```bash yosys ```
!\[Yosys](images/3333333.png)

All tools were successfully installed and tested on my system.

---

\### 3. RISC-V ISA Summary

RISC-V is an open-source instruction set architecture (ISA) that is
known for its simplicity, modularity, and extensibility. Unlike
proprietary ISAs, RISC-V enables designers to implement custom
extensions suited to specific applications. Its minimal and clean base
set allows for efficient hardware implementations, and its open nature
fosters innovation and collaboration in processor and SoC design.

---

\### 4. "Hello, World!" RTL Simulation

I executed a simple "Hello, World!" simulation using iverilog with the
provided testbench. The simulation ran successfully and produced the
expected output.

\*\*Sample Output Log:\*\* ``` Hello, World! Simulation finished.
```

---

\### 5. Week 0 Reflections

\*\*Setup Experience and Challenges:\*\* The tool installation process
was largely straightforward, thanks to the comprehensive guides
provided. I encountered a few challenges with configuring some
environment variables, but these were resolved after consulting
documentation and online resources. I am now comfortable with the setup
and look forward to further learning.

---

\### 6. Submission

All required files, logs, images, and this summary have been added to
the `week0` folder in my GitHub repository for review.

---

\*Excited to continue my learning journey in the RISC-V Reference SoC
Tapeout Program!\*

