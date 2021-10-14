# WhatsMyQuestion

Project Description 

Our project is topic modeling based on a stackoverflow dataset. The model will be trained on stackoverflow questions, and be used to predict the topics on new questions written on a web app.

Data Source

    https://www.kaggle.com/stackoverflow/stacksample
    
    Dataset with the text of 10% of questions and answers from the Stack Overflow programming Q&A website.
This is organized as three tables:
Questions contains the title, body, creation date, closed date (if applicable), score, and owner ID for all non-deleted Stack Overflow questions whose Id is a multiple of 10.
Answers contains the body, creation date, score, and owner ID for each of the answers to these questions. The ParentId column links back to the Questions table.
Tags contains the tags on each of these questions.
All Stack Overflow user contributions are licensed under CC-BY-SA 3.0 with attribution required.
