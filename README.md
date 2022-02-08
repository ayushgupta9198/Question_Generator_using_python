# Question_Generator

**Idea: 
**

To create and generate random questions based on the input text.

**Brief:
**

Model approach is to work with input text where we processed text via generating questions and analyzing the quality of qestion based on parameters , after quality check we append the qauestions in new text file.


**Research involves around the model:
** 

We implemented this model for generating results on any custom text.
Model is available in both the versions like GPU & CPU.
We can change the text size dynamically to any length where it is working.
We can adjust parameter like -  NUmber of questions to generate

**Code Workflow:
**

Code utilize the necessary packages and libraries to import

import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
python -m spacy download en_core_web_sm

**To execute we follow the below command to run :
**

python /content/drive/MyDrive/Ayush_Gupta/comment_generator/Automatic-Question-Generator/AutomaticQuestionGenerator/main.py

Now just refresh the current directory and “find the result” , here you can also customise the output path accordingly
