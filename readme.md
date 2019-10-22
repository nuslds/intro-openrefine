# An Introduction to Data Cleaning With OpenRefine

## Getting Ready for the Workshop

- Go to this GitHub repo. https://github.com/nuslds/openrefine-intro
- [Download the demo data](http://libguides.nus.edu.sg/ld.php?content_id=47625117).
- You should have OpenRefine installed on your PC.

  - Not sure how to download and run OpenRefine? Check out the instructions [here](https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions)
- Launch OpenRefine

  - Windows: Double click on OpenRefine.exe in the folder

  - macOS: Click on the icon after you have it installed. If you get a message saying "Open Refine can't be opened because it is from an unidentified developer", you can refer to the instructions [here](https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions#macos).
  - OpenRefine should open in your **default browser**. If you prefer to use another browser, simply copy the URL and paste it to the address bar of your preferred browser. **Chrome** is recommended.

![img](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/browser.PNG)



## Introduction

**OpenRefine** is a powerful tool for working with messy data. This workshop delves into the nifty functions OpenRefine provides to ease your data cleaning works.



**OpenRefine** allows you to:

- Work with relatively messy and unstructured data efficiently
- Explore and transform data in an easy way
- Batch edit of rows and columns without coding
- Interact with your data as it is always visible at each step of editing



## Overview

- [Part 1. Getting Started](https://github.com/nuslds/openrefine-intro/blob/master/markdowns/Part_1_Getting_Started.md)
- [Part 2. Removing Duplicates](https://github.com/nuslds/openrefine-intro/blob/master/markdowns/Part_2_Removing_Duplicates.md)
- [Part 3. Dealing with Incomplete Information](https://github.com/nuslds/openrefine-intro/blob/master/markdowns/Part_3._Dealing_with_Incomplete_Information.md)
- [Part 4. Identifying Inaccurate Entries](https://github.com/nuslds/openrefine-intro/blob/master/markdowns/Part_4_Tackling_Inaccurate_Inconsistent_Entries.md)
- [Part 5.  Dealing with Multi-Valued Cells](https://github.com/nuslds/openrefine-intro/blob/master/markdowns/Part_5_Dealing_with_multi_valued_cells.md)



## Data for Demonstration

We will use the data of OSMI Mental Health in Tech Survey 2016 for demonstration. Download the demo data from here.

- **Description**: This survey is conducted by Open Sourcing Mental Illness (OSMI) to understand the attitudes towards mental health in the tech workplace and the mental health disorders among tech-related workers. The [original data](https://www.kaggle.com/osmi/mental-health-in-tech-2016/) was made **dirty** to demo some basic features of OpenRefine, and only a small portion of data is used.

- **License Information**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

- **Rows**: 1515 (including blank rows and duplicates)

- **Columns**: 20

- **List of Variables**

  | **Code**                    | **Question**                                                 |
  | --------------------------- | ------------------------------------------------------------ |
  |record_id                   |Record ID (not included in the   original dataset)           |
  |gender                      |What   is your gender?                                       |
  |age                         |What is your age?                                            |
  |country_work                |What   country do you work in?                               |
  |us_state_work               |What US state or territory do   you work in?                 |
  |position                    |Which  of the following best describes your work position?   |
  |self_employed               |Are you self-employed?                                       |
  |num_employee                |How   many employees does your company or organization have? |
  |tech_company                |Is your employer primarily a   tech company/organization?    |
  |tech_role                   |Is   your primary role within your company related to tech/IT? |
  |employer_mh_benefits        |Does your employer provide   mental health benefits as part of healthcare coverage? |
  |employer_mh_discussions     |Has   your employer ever formally discussed mental health (for example, as part of   a wellness campaign or other official communication)? |
  |mh_med_coverage             |Do you have medical coverage   (private insurance or state-provided) which includes treatment of    mental health issues? |
  |mh_resources_awareness      |Do you know local or online resources to seek help for a mental health disorder? |
  |mh_productivity             |Do you believe your productivity   is ever affected by a mental health issue? |
  |mh_career                   |Do   you feel that being identified as a person with a mental health issue would   hurt your career? |
  |mh_disorders                |Do you currently have a mental   health disorder?            |
  |mh_disorders_type           |If yes, what condition(s) have you been diagnosed with?    |
  |mh_disorders_disanosed      |Have you been diagnosed with a mental   health condition by a medical professional? |
  |mh_disorders_disanosed_type |If so, what condition(s) were you diagnosed with?          |

  
