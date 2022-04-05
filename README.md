# Aspect-Based Sentiment Analysis of YouTube Comments

This project is an Aspect-Based Sentiment Analysis of YouTube Comments. There are four main notebooks:
- **comments-absa-lda:** **This is the main notebook.** It contains the code for the topics modelling section with an LDA Model for the topics modelling section.
- **comments-extraction:** Used to extract comments from a YouTube video and store them in an Excel file (note that some comments are already provided in comments_spreadsheets directory).
- **sentiment-analysis-evaluation:** Used to evaluate the VADER Sentiment Analysis Model.
- **comments-absa-gsdmm:** This is an additional notebook. It Contains the main code for the Aspect-Based Sentiment Analysis of YouTube Comments with a GSDMM Model for the topics modelling section.

## How to Install and Run the Project
This project requires to create an virtual environment. It is necessary to create a conda environment using the following steps:
1. From the terminal, go to the directory of the project.
2. From the terminal, type the following command: ```conda env create -f youtube-comments-analysis-env.yml```
3. After the packages are installed and the environment is set, you can set your IDE's interpreter using the newly created environment.

**You are now ready to run the notebooks!**

# Run ABSA Using LDA Model
1. Open the comments-absa-lda notebook.
2. Pick a content creator from the list of available content creators available in the second cell of the notebook.
3. Paste the selected content creator in the variable `creator` in the second cell of the notebook, below the list of creators.
4. Run all the cells in the notebook.
5. Results of the ABSA will appear at the bottom of the notebook.

# Run ABSA Using GSDMM Model
1. Open the comments-absa-gsdmm notebook.
2. Pick a content creator from the list of available content creators available in the second cell of the notebook.
3. Paste the selected content creator in the variable `creator` in the second cell of the notebook, below the list of creators.
4. Run all the cells in the notebook.
5. Results of the ABSA will appear at the bottom of the notebook.
