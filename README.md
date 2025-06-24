
# Developer Upskilling Curriculum

Welcome! This repository aggregates a **self‑guided learning path** that takes an absolute beginner all the way to writing, testing, and shipping maintainable Python software.  
Everything is organised as Jupyter notebooks so you can **read an explanation, run the code, and tinker immediately**—no separate slides or PDFs required.

---

## Module Overview

| # | Module | What you’ll learn | Notebook parts |
|---|--------|------------------|----------------|
| 0 | **Absolute‑Beginner Primer** | Install Python, run scripts vs. REPL, variables, loops, functions, basic debugging, and editor setup. | `primer_part0` – `primer_part6` |
| 1 | **Python Language Features & OOP** | Data structures, scopes, functions in depth, classes, inheritance vs. composition, idiomatic Python style. | `language_features_part0` + numbered parts |
| 2 | **Problem‑Solving & Software Design** | Decomposing problems, design patterns, complexity metrics, trade‑offs, and communication artifacts. | `problem_solving_design_part0` + numbered parts |
| 3 | **Files & the File System** | Paths, encodings, file modes, atomic writes, permissions, compression, and cross‑platform quirks. | `files_fs_part0` + numbered parts |
| 4 | **Concurrency (Threads + Async)** | GIL realities, threads, processes, asyncio event loops, race conditions & defensive patterns. | `concurrency_part0` + numbered parts |
| 5 | **Networking Fundamentals** | Sockets, TCP/UDP, HTTP anatomy, TLS, REST best practices, tooling (`curl`, `mitmproxy`). | `networking_part0` + numbered parts |
| 6 | **Testing & Debugging** | Pytest essentials, fixtures, mocking, coverage, property testing, CI, breakpoints & profiling. | `testing_debugging_part0` + numbered parts |

> Each module starts with a **Part 0** notebook—an engaging preface that sets context and motivation—followed by several hands‑on parts packed with explanations, runnable code, and quick‑check questions.

---

## How to run the notebooks

1. ### Install Python (≥ 3.11 recommended)
   * **Windows/Mac** – download from [python.org](https://www.python.org/downloads/) and *tick* “Add Python to PATH”.  
   * **Linux** – use your package manager (`sudo apt install python3 python3-venv`).

2. ### Create a project folder and a virtual environment *(optional but encouraged)*
   ```bash
   mkdir dev‑upskill && cd dev‑upskill
   python -m venv .venv
   source .venv/bin/activate      # Windows: .venv\Scripts\activate
   ```

3. ### Install Jupyter
   ```bash
   pip install --upgrade pip
   pip install notebook           # or: pip install jupyterlab
   ```

4. ### Launch and open notebooks
   ```bash
   jupyter notebook               # or: jupyter lab
   ```
   A browser tab will open—navigate to the notebook file you want (e.g., `primer_part1.ipynb`) and hit **Run ▶︎** to execute each cell.

5. ### Tips
   * If you see a `Kernel not found` prompt, choose the Python interpreter from your virtual environment.
   * Use **Shift + Enter** to run the current cell and jump to the next.
   * Feel free to edit code cells and re‑run—experimentation is the fastest way to learn!

Happy coding—and enjoy the journey from “Hello, world!” to production‑ready software.
