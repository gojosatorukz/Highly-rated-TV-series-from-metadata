Highly rated TV series from metadata
Machine Learning Algorithms - Midterm - SE-2418
Bekzat Rashiduly and Gapar Galym

START HERE
1. Extract the entire ZIP, preserving all folders.
2. Open Midterm_TVSeries.html to read the executed notebook without installing anything.
3. Open Midterm_TVSeries.ipynb in Jupyter to inspect and rerun the code.
4. Use slides/Midterm_TVSeries.pptx for a 7-10 minute defense.
5. Read docs/DEFENSE_GUIDE_RU.txt to prepare both partners for questions.

REPRODUCIBLE RUN
Use Python 3.12 or a compatible current Python environment.
python -m venv .venv
Activate .venv using the command for your operating system.
python -m pip install -r requirements.txt
python -m jupyter notebook
Open Midterm_TVSeries.ipynb and run all cells in order from the extracted project directory.
The notebook runs offline from the supplied raw snapshot. Collection is a separate step:
python code/collect_data.py --snapshot midterm_2026-10-06 --pages 60
The collector reuses verified existing pages. Use a NEW snapshot name for any new collection.

CONTINUATION
Retain data/raw/midterm_2026-10-06, data/processed/series_clean.csv and data/splits unchanged.
Endterm and Final reuse the same IDs, labels, 8/10 target and held-out split.
Use a new results folder for each later stage. Plot summaries are retained but excluded at Midterm.
Do not use the held-out test results to choose hyperparameters.

DATA ATTRIBUTION
Source: TVmaze, https://www.tvmaze.com
API: https://www.tvmaze.com/api
Data and derived cleaned data: CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/
The cleaned CSV changes the original JSON structure, strips summary HTML and adds a binary target.

AI ASSISTANCE
OpenAI Codex assisted with collection/preprocessing code, notebook, experiments, slides and checks.
The notebook documents the confirmed team responsibilities and the AI assistance explicitly.

SUBMISSION
Moodle requests Midterm_Surname_Name_Group.zip. Both partners upload the same project content.
The submission box displays Friday 9 October 2026 at 12:00 AM, meaning the start of that day.
The course guide also requires upload by 23:59 on the day before the group's defense.
