Goals:
Becoming familiar with all the components of a realistic working environment for a software engineer.
Gaining experience on working on the terminal
Gaining experience on making progress when exposed to many unfamiliar technologies
Summary:
Set up a code repository with continuous integration and deployment.
Specification:
Set up a git repository in your github account. Follow the set up command instructions carefully:
https://docs.google.com/document/d/1bH7zX7AA93THTylXPwb78P2H2xfyrhwhWiTaXxvJ0aU 

The repository must satisfy the following criteria:
It must contain an App.java file which has a simple static method implementation:
The method should accept at least 4 parameters.
At least two of these parameters must be
Integer [ ] or
ArrayList<Integer>.
The method should perform a meaningful computation on the set of strings and return a result.
It must contain a AppTest.java file that implements unit tests for your algorithm implementation.
The file must contain at least 5 meaningful unit tests covering your method
It must contain a pom.xml file.
It must have a continuous integration setup with https://travis-ci.org site.
It must have an auto deployment setup with https://www.heroku.com/ site.
The web application should have a UI similar to the shown during the class. For each parameter requested from the user, the UI should have a separate form.
When the submit button is pressed, the inputs should be given to the algorithm and the result should be shown to the user on the web page.
The web page should have a description of the algorithm, the input format and the output.
It must have a README.md file describing what your project is about.  In addition,
the file must contain a green marker from travis-ci showing the current build is passing;
the file must contain a demo site address to the corresponding heroku application.(

IMPORTANT NOTICE:
Make sure that your github repository shows a meaningful commit history distributed over time. In other words, we should NOT see that you committed all the files all at once because otherwise this clearly showed that you actually did not follow the instructions properly.

Submission (due February 8, 21:59)
Send an email to the address: bil481spring2020@gmail.com
Include a link to your public github repository.
Include a screenshot to your travis page showing the latest build (see an example below)
Include a screenshot to the overview page of your heroku app (see an example below)

Make sure the heroku app is running until the grading is done (unless you manually delete the app from heroku, it will stay running). If the demo site does not work, we will assume you have not completed the heroku setup.

Example screenshots:
Example look of github repository
Example Travis screenshot (It must have the repository address visible)
Example heroku screenshot (It must have the github repository address visible)
Example webapp screenshot



 