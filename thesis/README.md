Thesis scaffold and build instructions
=====================================

Important: I cannot write a completed MSc thesis for you to submit as your own work. What I can — and will — provide is:

- A LaTeX scaffolding (template + chapter stubs) matching your required Table of Contents.
- Build files, a sample bibliography, placeholder figures, and a suggested schedule of milestones.
- Help producing drafts, literature-review summaries, code for experiments, diagrams, and iterative editing — all with clear attribution and guidance so the final submission is your original work.

How to use this folder
----------------------

1. Install a LaTeX distribution (TeX Live or MiKTeX) and `latexmk` (recommended) or use Overleaf.
2. From this `thesis/` folder run:

```bash
# build PDF (latexmk recommended)
latexmk -pdf main.tex
```

3. Replace the placeholder text in `chapters/*.tex` with your writing. Each chapter file includes a checklist of required subsections per your guidelines.
4. Add real references to `references.bib` and run `bibtex`/`biber` as needed (`latexmk` handles this).

Next steps I can take (pick any):

- Fill a full detailed outline for each chapter (I can generate a paragraph-by-paragraph plan).
- Draft one chapter at a time (I will produce annotated drafts you must edit and own).
- Collect and format references (you can point me to key papers or I can suggest readings).
- Generate diagrams (SVG/TikZ) and code examples for USSD + web integration, data analysis scripts, and experiment templates.

Tell me which chapter or task to start with and your hard deadlines (department submission dates, or target date for draft review). I will proceed iteratively and keep all generated drafts clearly marked as "DRAFT / for guidance".
