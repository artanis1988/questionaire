The main idea is to create a

1. RUNNING APPLICATION
The application folder has both jar and bat files and user can either
run it using bat on windows or throw console on jar at any platform.

2. LAYOUT
The UI is made up using Swing and presents a small app with one page UI only
that is going to contain the question at the top half side of it and
the answer to it is hidden by default but shown in the bottom half side \
once a user clicks a button.
"Load Questions" button is in the top-right corner of the page.
 "Show Answer" is in the left bottom and "Next question" is in the right bottom.

3. OPERATION
3.1 Loading questions from file
When clicking on "Load Questions" button, a file-open-dialog appears
and it's require to point to XML file that contains questions and answers.

3.2 Show answer to the current question
When clicking on "Show answer" the answer to a question above becomes visible
in the bottom part of the page, after this click the button "Show answer"
changes status that prevents a user from clicking on it again until a user changes
the answer.

3.3 Move to the next question.
When clicking on "Next Question", the program will randomly chose next question
based on the size of previously loaded into app.

4. PROBLEMS AND TROUBLESHOOTING
4.1 Prerequisites
Make sure you have JRE 1.7 on your machine to run this application
4.2 Importing questions
A problem may appear when loading corrupted or empty file with questions.
As the file shouldn't be null or empty, in case of invalid - a special message is shown,
no questions are loaded in error case and buttons "Show Answer" and "Next Question"
become unable to click.
4.3 XML validation
The xsd inside the app validates the xml for integrity as well as for
validness. Make sure you're loading the correct XML that corresponds
to the one shown in Paragraph 5.

5. DATA FORMATS

5.1 Questions file
The XML file with questions and answers is going to be as given below:
<?xml>
<questions>
    <item>
        <question>When was Java released?</question>
        <answer>1995</answer>
    <item>
    ..........more items - as many as you want.
</questions>

6. FEEDBACK
Hope you'll enjoy the quiz experience
Any feedback as well as improvements can be sent to my email:artanishierarch@gmail.com


