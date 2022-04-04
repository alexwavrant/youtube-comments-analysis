# Aspect-Based Sentiment Analysis of YouTube Comments

This project is an Aspect-Based Sentiment Analysis of YouTube Comments. There are four main notebooks:
- **comments-absa-gsdmm:** Contains the main code for the Aspect-Based Sentiment Analysis of YouTube Comments with a GSDMM Model for the topics modelling section.
- **comments-absa-lda:** Contains the code for the topics modelling section with an LDA Model for the topics modelling section.
- **comments-extraction:** Used to extract comments from a YouTube video and store them in an Excel file (note that some comments are already provided in comments_spreadsheets directory).
- **sentiment-analysis-evaluation:** Used to evaluate the VADER Sentiment Analysis Model.

## How to Install and Run the Project
This project requires to create an virtual environment. It is recommended to create a conda environment using the following steps:
1. From the terminal, go to the directory of the project.
2. From the terminal, type the following command: ```conda env create -f youtube-comments-analysis-env.yml```
3. After the packages are installed and the environment is set, you can set your IDE's interpreter using the newly created environment.

**You are now ready to run the notebooks!**
