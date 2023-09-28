# The FOSS Capstone Project 

This GitHub page is a Capston Project created as a fulfillment of CyVerse FOSS workshop

## Objective

The goal of this page is to learn to build a personalized website using tools presented at the cohort sessions. 

Throughout FOSS, learners will be given the opportunity to reinforce their knowledge through self-paced assignments: a novel topic will be covered each week, and at the end of the lesson learners will be asked to add their newly gained knowledge to their own GitHub repository. This repository aims to be a reference learners can use when adding to their own work.

## Structure

The repository aims to represent a well structured page for a research tool following [FAIR](https://www.go-fair.org/fair-principles/) and [CARE](https://static1.squarespace.com/static/5d3799de845604000199cd24/t/5da9f4479ecab221ce848fb2/1571419335217/CARE+Principles_One+Pagers+FINAL_Oct_17_2019.pdf) principles. In addition, the resporitory tries to follow best practices for project management, data management, version control and documentation with the goal of being reproducible for collaborators and potential contributors.

- [Project Management](https://foss.cyverse.org/02_project_management/)
- [Managing Data](https://foss.cyverse.org/03_managing_data/)
- [Documentation and Communication](https://foss.cyverse.org/04_documentation_communication/)
- [Version Control](https://foss.cyverse.org/05_version_control/)
- [Reproducibility](https://foss.cyverse.org/06_reproducibility_i/)


## Repository Organization

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── mkdocs.yml                      <- Governing file for website building
├── requirements.txt                <- Requirements file for pip installation (required by website)
├── code
│   ├── src
│   │   ├── *.py                    <- Python files part of dplPy
│   │   └── execution_sample.ipynb  <- runnable example (executable Jupyter notebook)
│   ├── Dockerfile                  <- Docker script in charge of container creation
│   └── tests_data                  <- Data from third party sources used for testing (in rwl and csv formats.
│       ├── csv
│       └── rwl        
└── docs                           
    ├── assets                      <- Folder for images and additional graphic assets
    ├── stylesheets                 <- Folder containing style-related code for the website
    ├── index.md                    <- Main website home page
    ├── installation.md             <- Installation steps for dplPy
    ├── manual.md                   <- Manual for dplPy
    ├── Data_Management_Plan.md     <- Data Management Plan (example) applicable for this repository
    └── Governance_Operations.md    <- Governance & Operations (example) file applicable for this repsitory
```
---
