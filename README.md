# Quizller-App
A True or False game with a beautiful GUI and interesting questions created with the help of concepts of Oops(Object-oriented-programming).

# Table of Contents
* Description 
* Libraries and Modules
* How to Run
* Screenshots

# Description
An interesting True or False game created with the help of various libraries, API and GUI libraries. 

The questions are requested from [Trivia Database](https://opentdb.com/), so that we have plethora of questions. The images for True and False are stored in images directory as `true.png` and `false.png` respectively.


All the data for questions are returned in the file `data.py`, while the question objects is created in `question_model.py`. In `quiz_brain.py` the QuizBrain object contains the methods for next_question, check answer and if it still has questions. GUI is provided from `ui.py` the colors used, is referred from [here](https://colorhunt.co/)

# Libraries and Modules
* Tkinter - for GUI
* Requests
* html

# How to Run 

As soon as the user runs the code a windom with a question, score (on the top)  and check marked button ✅ and cross marked button ❌ representing True and False respectively. 

If the user thinks the answer is true the user will click on the check mark, if user's choice is correct the question background color will change to green for 2 secs and the score will be increase by 1. If the user's choice is incorrect the screen color will change to red and score will remain unchanged. 

Total 10 questions are asked in one game, after the game is over final score will be revealed in score/10 format.

# Screenshots

* Opening Window

<img width="262" alt="image" src="https://user-images.githubusercontent.com/103064401/192941707-0bd85144-1553-4bb5-a581-8f04b80a12c1.png">

* For Correct answer

<img width="258" alt="image" src="https://user-images.githubusercontent.com/103064401/192942174-987e6baa-7d17-4834-a0f7-f4e014619e09.png">

* For Incorrect answer

<img width="258" alt="image" src="https://user-images.githubusercontent.com/103064401/192941990-69e30aaa-fbd0-4efd-95ea-0446c7bf8d42.png">

* Final Score

<img width="262" alt="image" src="https://user-images.githubusercontent.com/103064401/192942241-9894adaa-c5e9-4d7b-ba5e-079cf1a56246.png">



