# Tutorial Assignment

This assignment guides you through the simple
steps necessary to clone, commit and push (to) a gitub
repository. You will need this during the course.

The goal in the tutorial assignment is to modify an Hello world
example insuch a way that it is suitable for automatic
retrieval and evaluation.

## Step 0

Fork the repository

    https://github.com/rladstaetter/fhj.swengb.assignments.tutorial

via the 'fork' button to your own github place. You have now a new
repository which is derived from the original one.

## Step 1

Clone your newly created repository hosted at

    https://github.com/place_here_your_github_username/fhj.swengb.assignments.tutorial

via the "Clone in desktop" button.


## Step 1

The cloned directory should reside in your workspace. The structure
should look like this (for example):

    c:/
    c:/workspace/
    c:/workspace/pom.xml    <- this pom is the one available at https://gist.githubusercontent.com/rladstaetter/82bdb5809e7e3e2aa506/raw/fb8d006a0834674ae13fc10abb11516fab9018a7/pom.xml
    c:/workspace/fhj.swengb.assignments.tutorial

Cloning can be done easily if you install the github client for your OS.

    https://desktop.github.com


## Step 2

Open the project with IntelliJ by pointing the "Open" Dialog to c:/workspace/pom.xml.
Attention: maybe you have to activate the maven profile (button to the right.).


## Step 3

Navigate to the TutorialAssignmentTest, which you can find in

    fhj.swengb.assignments.tutorial/src/test/scala/fhj/swengb/assignments/tutorial/rladstaetter/TutorialAssignmentTest.scala

## Step 4

Right click the JUnit test, execute it with "Run TutorialAssignmentTest"

.. all tests should pass.

## Step 5

rename the package "rladstaetter" to your userId. (See the project
https://github.com/rladstaetter/fhj.swengb.course, object Students) if
you are unsure about your id. Make sure you do it in

    src/main/scala

as well as

    src/test/scala

the renaming also affects the content of the files itself (check out the first
line in TutorialAssignment.scala as well as TutorialAssignmentTest.scala)

## Step 6

Run tutorialAssignment test again, it should work as before, but with
your new / own package

## Step 7

Commit to your local git repository.

## Step 8

Synch ("Push") your data to your "fork" of the tutorial assignment.

When you are finished you should be able to have a look at your data
by entering the following url in your browser:

    https://raw.githubusercontent.com/rladstaetter/fhj.swengb.assignments.tutorial/master/src/main/scala/fhj/swengb/assignments/tutorial/userID/TutorialAssignment.scala
                                      ^-your github account                                                                                                   ^---your userid

That's all.


