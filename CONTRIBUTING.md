# Code and documentation standards

**Author:** Priyanka Singh · University of Iowa

- Begin every substantive Python/R script with a concise project, author, purpose, inputs and outputs header.
- Add function docstrings for arguments, return values and key assumptions. Use comments to explain biological/statistical reasoning and non-obvious decisions.
- Use descriptive snake_case filenames and functions (R and Python); consistent formatting; explicit random seeds where applicable.
- Validate inputs and include at least one unit test or sanity check per project.
- Separate `data/`, `src/`, `notebooks/`, `tests/`, and `results/` where useful. Never commit restricted data or credentials.
- Every project README must state biological question, public dataset/accession, methods, exact run instructions, results, limitations, references, and attribution.
- Credit original authors, tools, datasets, and any externally adapted code. Do not claim others' code as your own.
- Use clear commit messages such as `Day 03: add tested GC-content calculation`.
- Prefer short, explanatory comments over line-by-line narration.
