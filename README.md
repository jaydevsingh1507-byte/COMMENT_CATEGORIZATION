**Comment Categorization & Reply Assistant Tool**

This project is an NLP-based mini-application that analyzes user comments (from social media posts, product announcements, etc.) and classifies them into meaningful emotion/intent categories such as praise, support, constructive criticism, hate/abuse, threat, emotional, spam/irrelevant, and questions/suggestions. The tool helps brands and content creators efficiently sort feedback and generate appropriate responses.

**The repository contains:**

A labeled dataset (combined_dataset.csv)
A notebook (comment_catergorization_assignment.ipynb) that trains and evaluates an ML/NLP classification model
Preprocessing pipeline: cleaning, tokenizing, lemmatizing
Machine Learning classifier (e.g., Logistic Regression / SVM / Transformer)
Output examples and category predictions
Google Colab-friendly execution
Reply assistance template logic (optional)

**Project Overview**
Users post many types of comments online—positive, negative, abusive, supportive, emotional, or spam.
This tool automatically:
✔ Cleans and preprocesses user comments
✔ Predicts the underlying intent/emotion
✔ Categorizes them into meaningful groups
✔ (Optional) Suggests reply templates

**Target Categories**
Your classifier detects the following:
Praise – e.g., “Amazing work! Loved this.”
Support – “Keep going, you’re doing great!”
Constructive Criticism – “Good idea, but the sound quality could improve.”
Hate/Abuse – “This is trash, stop making videos.”
Threat – “I’ll report you if you do this again.”
Emotional – “This reminded me of my childhood.”
Irrelevant/Spam – “Follow me for free followers!”
Question/Suggestion (Optional) – “Can you make a video on X?”

**How to Run the Notebook on Google Colab
Follow these steps to run the .ipynb file without errors:**
1. Open Google Colab
Go to: https://colab.research.google.com/
2. Upload the Notebook
Select comment_catergorization_assignment.ipynb
3. Upload Dataset to Colab
You can either upload the dataset on your google drive and access it from there using the 4th cell in the notebook or run 5th cell and upload it there firectly from your computer. But first run the cells before running any cell. 
**NOTE:**
RUN ALL CELLS SEQUENTIALLY TO AVOID ANY ERROR.

After you have run all the cells. You will get a Gradio UI where you to put your comment.
**EXAMPLES:**
1. I love the animation but the audio needs work. *-constructive criticism*
2. Good idea, but the sound quality could improve. *-constructive criticism*
3. Can you make a video on X? *-question*
4. Follow me for free followers! *-spam*
5. Amazing work! Loved this. *-praise*
6. This is trash, stop making videos. *-hate*
