# DataHeadQuarters
#Title: Could location and time predict the likelihood of a specific crime being committed?
#Overview: Our focus for this research is encompassed by the idea, does location and time predict the likelihood of a specific crime being committed? The reason we are focusing on specific crimes being committed at locations and times is due to the fact that we can understand better ways of setting up security systems,  better tracking of crimes of specific neighborhoods or ZIP Codes.

## Team
- Eli Licona Pineda - Researcher and coder
- Sami Nukala - Researcher and coder
- Jennifer Salazar Castro - Researcher and coder

## Repo Structure


/data/ (raw data NOT stored here)
/notebooks/
/src/
/reports/
/docs/
README.md
.gitignore


## How to Run
- Python: 3.10+ (recommended)
- Install deps: `pip install -r requirements.txt`  *(optional)*
- Open notebooks in `/notebooks/`

## Data Access
Raw data is stored in <shared drive/path>. To reproduce EDA:
1) Obtain dataset from <link or contact>.
2) Place files under your local `data/` (excluded from Git).
3) Run notebooks in `/notebooks/`.

## Milestones & Issues
We track Sprint tasks under the “Sprint 2 - Data Prep & EDA” milestone and Issues in GitHub.

# Branch
git clone https://github.com/<org>/<team-name>-dtsc-3601-project.git
cd <DataHeadQuarters>-dtsc-3601-project

# new branch
git checkout -b feature/eli-eda-setup

# add notebook
mkdir notebooks
jupyter notebook notebooks/eda_setup.ipynb   

# save a simple notebook that loads a CSV and prints head()

# stage + commit
git add .
git commit -m "Add initial EDA notebook and update README"

# push
git push -u origin feature/eli-eda-setup

#change 
git add . 

git commit -m "Added initial EDA notebook with dataset preview"

#git push origin feature/<your-initials>-eda-setup

