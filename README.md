# gpt-oss-20b Red Teaming Workflow

## Overview
This repository documents a red teaming engagement against the gpt-oss-20b model, including all findings, code, and submission materials for the OpenAI GPT-OSS-20B Red Teaming challenge.

## Folder Structure
- `notebooks/` — Jupyter notebooks for experiments, prompt engineering, and analysis
- `findings/` — All finding JSON files 
- `images/` — Figures for submission
- `submission/` — Final writeup 

## Workflow
1. **Experimentation:**
   - Use notebooks in `notebooks/` to develop and test prompts, analyze outputs, and document vulnerabilities.
2. **Findings:**
   - Each confirmed vulnerability is documented as a separate JSON file in `findings/`, following the provided schema.
3. **Submission:**
   - The final report (`writeup.md`) and all required links are in `submission/`.
   - Each finding JSON is also uploaded as a private Kaggle dataset.
4. **Images:**
   - All supporting images are stored in `images/` for use in the submission.

## Submission Links
- **Kaggle Notebook:** https://www.kaggle.com/code/huseyincavus/gpt-oss-20b-safety
- **Kaggle Datasets:**
  - https://www.kaggle.com/datasets/huseyincavus/gpt-oss-finding-1
  - https://www.kaggle.com/datasets/huseyincavus/gpt-oss-finding-2
  - https://www.kaggle.com/datasets/huseyincavus/gpt-oss-finding-3
  - https://www.kaggle.com/datasets/huseyincavus/gpt-oss-finding-4
  - https://www.kaggle.com/datasets/huseyincavus/gpt-oss-finding-5

## Getting Started
1. Clone this repo.
2. (Optional) Set up a Python environment with `uv` and install dependencies as needed.
3. Explore notebooks and findings for full details.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

