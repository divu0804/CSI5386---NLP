*********************************   PART 1   *****************************************


- The folder "PART1" contains all the essential files for the PART 1 of the assignment.

- /PART1/Code contains the code all the code for part 1

- We used google collab because jupyter notebook crashed because of the huge dataset

- For viewing the output, any browser can be used

- Change parameters in run.sh and run to train the model
- Change parameters in evaluate.py and execute to get the AUPR score


Download the pre-trained models from here
** https://zenodo.org/record/4599830#.Y4f9BOHMLIU - link for the dataset **

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

                            ***********************************     PART 2   ***************************************


- The folder "PART2" contains all the essential files for the PART 2 of the assignment.

Download the dataset from https://alt.qcri.org/semeval2016/task1/index.php?id=data-and-tools
-DataSet for training : Use the 2012 training dataset
-Dataset for testing  : sts2016-english-with-gs-v1.0

This package contains test sets with gold standard labels for Semantic Textual Similarity (STS) shared task.

Trained model : model_all_mp_base_v2_e10_w1000_bs64

Cosine similarity list files :

    answer.txt

    headlines.txt

    plagiarism.txt

    postediting.txt

    question.txt


Gold Standard Files:

    STS2016.gs.answer-answer.txt

    STS2016.gs.headlines.txt

    STS2016.gs.plagiarism.txt

    STS2016.gs.postediting.txt

    STS2016.gs.question-question.txt




Evaluation Script:

    Correlation-noconfidence.pl



Code: sbert_trained.py



Open google collab upload the dataset files, ,model  and the .ipnyb notebook.
To train the model upload 2012 training data and run .

Output folder names: model_all_mp_base_v2_e10_w1000_bs64 would be created.

Change the readline input file , use our trained model then execute to see the output list of cosine similarities of the new model.


Persson Coefficient:

    To execute the perl script and get the persson coeff run the below command:

    /correlation-noconfidence.pl STS2016.gs.<dataset>.txt  <dataset>.txt



