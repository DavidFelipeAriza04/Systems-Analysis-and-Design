# Workshop 2: NCAA Tournament Prediction System Design

Building upon the analysis from Workshop 1—where system elements, relationships, and factors influencing result variability (sensitivity and chaos) for the NCAA tournament were identified—this Workshop 2 focuses on the **design of the prediction system**.

In this phase, essential **functional and non-functional requirements** for the system were defined. A **data architecture** was proposed, modeling the information flow and processing, as illustrated below (or in the design document):

[High Level Architecture](https://github.com/DavidFelipeAriza04/Systems-Analysis-and-Design/blob/main/Workshops/Workshop_2_Design/High%20Level%20Architecture.svg)

 <img src="https://raw.githubusercontent.com/DavidFelipeAriza04/Systems-Analysis-and-Design/aa73d4f571defa78e72dbdffdeb37266a97d371f/Workshops/Workshop_2_Design/High%20Level%20Architecture.svg" width="600" />


In addition to the requirements, strategies were outlined to **manage the elements affecting sensitivity and chaos** previously identified.

A **technological stack** was selected, drawing from tools commonly used in Kaggle projects and suitable for data analysis and machine learning. The **project structure** was organized into directories for the dataset (`/data`) and the source code (`/src`). The latter was modularized to cover data ingestion, preprocessing, model training, and the export of results to a `.csv` file.

For a detailed description of the system design, please refer to the [System Design Document](https://github.com/DavidFelipeAriza04/Systems-Analysis-and-Design/blob/main/Workshops/Workshop_2_Design/NCAA_Basketball_Tournament_System_Design.pdf).
