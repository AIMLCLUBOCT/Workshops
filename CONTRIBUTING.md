# Contributing Workshop Materials

We welcome workshop materials, notebook improvements, and teaching exercises prepared by student mentors, technical leads, and guest speakers!

---

## Guidelines for Workshop Submissions

1. **Self-Contained & Reproducible:**
   - Every workshop must include a `requirements.txt` with locked major/minor versions.
   - Any custom dataset used must either be included in `data/` (if $< 5\text{MB}$) or downloaded dynamically in the notebook via a public URL.
2. **Pedagogical Clarity:**
   - Provide a dual-notebook structure where possible:
     - `01_starter.ipynb`: Guided exercise containing explanations, hints, and `# TODO: Implement here` prompts.
     - `02_solution.ipynb`: Verified solution running end-to-end without errors.
3. **Clean Jupyter Outputs:**
   - Before committing notebooks, clear unnecessary large outputs, stack traces, and local system paths (`Kernel > Restart & Clear Outputs`).
4. **Licensing:**
   - Code contributed to this repository is licensed under the MIT License. Please ensure any third-party code or datasets are compatible with open-source reuse.
