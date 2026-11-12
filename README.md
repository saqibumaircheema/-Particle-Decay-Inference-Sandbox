# Particle-Decay Parameter Inference — AI Evaluation Sandbox

This repository is a **separate, sanitised copy of an existing scientific Python project**, prepared for use in an **AI coding-agent evaluation**. It contains pre-existing research code rather than evaluation prompts or answers. The original project is preserved separately.

## Project overview

The notebook uses Monte Carlo pseudoexperiments and unbinned maximum-likelihood fitting to examine parameter bias under background contamination in a simulated oscillating particle-decay model.

The model studies lifetime (`tau`), oscillation frequency (`delta_m`), and modulation (`V`). It compares signal-only fits against fits explicitly incorporating a background component.

## Contents

- `notebooks/decay_parameter_pseudoexperiments.ipynb` — original analysis code with outputs and machine-specific notebook metadata removed
- `requirements.txt` — Python dependencies
- `.gitignore` — excludes environments, caches, and generated files
- `LICENSE` — MIT licence

Generated results, figures, previous Git history and local machine configuration are deliberately omitted.

## Setup

Use Python 3 and install dependencies with:

```bash
python -m pip install -r requirements.txt
```

Open and run the notebook in Jupyter. Some Monte Carlo calculations may be computationally intensive. The original project did not fix a random seed, so repeated runs may differ.

## Licensing and evaluation context

The project is distributed under the MIT License. This copy is intended as a clean codebase for evaluating AI coding agents. **No evaluation prompt, rating, transcript or rationale is included in this repository.**
