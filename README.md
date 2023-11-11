# rutaBAGA: A Visualization Approach for Bias Awareness in University Admissions
This repository hosts the supplemental materials for our submission of paper "rutaBAGA: A Visualization Approach for Bias Awareness in University Admissions" to CHI 2024.

## Abstract
University admissions is a complex decision making process where cognitive and implicit biases, may impact the way reviewers individually and collectively make decisions. Education-based methods like training courses often have limited impact due to the subconscious nature of these biases. This paper introduces a visualization system, rutaBAGA, that promotes heightened awareness of implicit biases through real-time system interactions. The system enables reviewers to scrutinize their own processes to ensure fair and consistent review procedures. We present the results of a controlled study that shows (i) implicit racial bias correlates to observable differences in university application review behaviors and decisions and (ii) our system can affect individuals’ review processes. Additionally, we present a case study where rutaBAGA was used in the 2022-2023 Ph.D. admissions cycle in the Computer Science department at a private university demonstrating rutaBAGA’s potential to iteratively transform university application review processes to ensure adherence to fair procedural goals.

## Controlled Study
The `controlled_study` directory contains the dataset, survey responses, and data analysis scripts for the controlled study.

- `dataset` directory:
    - prompts_summary.pdf: summarizes the sequence of prompts that were used to generate the full application packages.

    - application_generation_process.pdf: summarizes the full generation generation process including prompts used, results generated, and generation dates. 

    - applications: the directory contains formatted PDF files of the generated application documents that were displayed in the study interface. 
- `data_analysis` directory:
    - IAT.Rmd: R markdown for the IAT score calculation.
    - data_analysis.Rmd: R markdown for the data analysis of hypotheses 1 and 2.
    - data_analysis.html: HTML view of the full_data_analysis R markdown file.
    - survey_analysis.ipynb: Jupyter notebook for the analysis of post study survey response
    - survey_analysis.html: HTML view of the survey_analysis notebook.
    - interaction_analysis.ipynb: Jupyter notebook for the process and analysis of user interactions.
    - interaction_analysis.html: HTML view of the interaction_analysis notebook.
    - `data` directory: the directory contains csv files for the data used in the analysis.
        - applications.csv: application profiles.
        - focus_time_with_change.csv: participants' time spent data including the time spent before and after seeing the summary page.
        - IAT_score.csv: participants' gender and race IAT scores calculated from the survey response. 
        - interactions.csv: participants' interactions on the rating page.
        - rating_history.csv: participants' rating histories on the applicants.
        - ratings_with_change.csv: participants' ratings on the applicants before and after seeing the summary page.
        - ratings.csv: participants' final ratings on the applicants.
        - survey_responses.csv: the post study survey responses.
        - vis_interactions.csv: participants' interactions on the summary page.
        


- post_study_survey.pdf: the post study survey.





## Case Study
The `case_study` directory contains the survey responses, and data analysis scripts for the case study.
- data_analysis.Rmd: R markdown for the data analysis of time spent and decision data.
- decisions.csv: decision data including the admissions decision, gender and race for the applicants.
- focustime.csv: time spent data including user id, applicant id, time spent, gender and race of the applicant.
- survey_responses.xlsx: a spreadsheet including the responses from the post study survey, the SUS score, and usefulness scores.


## Prototype
- prototype.png: The preliminary prototype.