# HOWTOs

Several HOWTOs relevant to Data 602

# HOWTO: Get started with Blackboard

The Blackboard GUI has a zillion options, so it's easy to get lost. Start with the default URL for "Courses"..

https://blackboard.umbc.edu/ultra/course

* Click on the icon for the specific course of interest.
    * This opens a full-size popup with a purple "X" in the upper left.
    * The left-hand menu bar on this page opens with the configuration from the last time you were here
    * That can be confusing. So remember, The left-hand menu bar has two main roots:
1. Class Name
    * This expandable menu item is at the top and uses the specific course name
    * For example: "Data 602 Introduction to Data Analysis and Machine Learning..."
    * This is where you go to create and deploy tests, etc.
2. Control Panel 
    * This expandable menu item is right underneath "Course Management"
    * This is where you start Blackboard Collaborate sessions, check student grades, etc.

# HOWTO: Create a test

There are 3 paths to create a test. This can be confusing. In each case, start in the left-hand menu:

1. Class name > Assignments
    * THIS IS PROBABLY THE BEST WAY
    * In the **top** dropdown menu bar (not the left-hand menu bar), click: Assessments > Test
    * Click "Create" to create a new test, or
    * Select a previously created test (if you made one in step 3 below) from the list in "Add an existing test"
2. Class name > Course Materials
    * THIS IS EQUIVALENT TO #1
    * From the **top** dropdown menu, click: Assessments > Test
    * Select a test made previously the click "Submit", or click "Create" to create a new one
3. Control Panel > Course Tools > Tests, Surveys and Pools
    * THIS IS **NOT** RECOMMENDED -- just because it's confusing. 
        * If you go this route, you create a reusable test template
        * This is different from the test you create in approach #1 (above).
        * If you create a test template, you still need to add it to your course before you can deploy it.
    * Click on "Tests"
    * Click on "Build a test"
    * Follow instructions to create questions
    * NOTE: This test can be re-used, and it needs to be added to the course.
* Once a test is created, it must be deployed within a content folder before students can take the test. 
* Test results are reviewed in the Grade Center. Note that some question types are not automatically graded.

# HOWTO: Deploy a test

Deploying a test involves two steps:

1. To "Add Test" (this is when you can configure test options), start in the left-hand menu bar
    * Class name > "Assignments" **OR** "Course Materials"
        * On the **TOP** menu bar, click: Assessments > Test
            * If you already created a test, it should appear in the "Add an Existing Test" list
        * Select the test you want to add, then click "Submit"
        * Modify the test options (e.g. time it's visible, etc.) -- you can edit these later if you like
        * Click "Submit"
        * Now the test should appear in the "Assignments", so proceed to step 2.
2. To "Make Available" (i.e., "deploy), assuming you have completed step 1, then start in the left menu bar:
    * Class name > "Assignments" (**NOT** "Course Materials")
    * You should see the test you want to deploy in the list on this page. If it's not there, then go back to step 1.
    * The dropdown arrow/menu next to the test name should include "Make Available" (third from the top)
        * The text below the test name should read: "Availability: Item is hidden from students"
        * Note: You can "Edit the Test" or "Edit the Test Options" at this point.
    * Click "Make Available" in the dropdown menu to "deploy" the test
        * The text under the test name should change to indicate know it's status
        * For example, it will display the time the test will be made available, etc.

# HOWTO: Start a Blackboard Collaborate Ultra session

Start in the left-hand menu

* Control Panel > Course Tools > Blackboard Collaborate Ultra
* Click "Create Session"
* Add the title of the session, then other options appear
* Change "Guest role" to "Presenter" in the dropdown menu on the right
* Change End time to 9:00pm
* Copy the "Guest link" to the clipboard and email it to all the students
* Return to the Blackboard Ultra page and click on the session that I just created

# HOWO: Compute/review grades

Start in the left-hand menu

* Control Panel > Grade Center
* Click "Tests" or "Full Grade Center" to see a list of students and their grades.

# HOWTO: Load a file into Colab from your Google Drive

* Check out [these instructions](./colab.md)
* Check out this notebook [colab_data.ipynb](./colab.md)

# HOWTO: Send email

* Login to blackboard
* Click on Courses
* Click on "Course Tools" in left-hand menu
* Scroll down and click on "Send email"
* Click on "All users"

# HOWO: class notebooks

* Colab allows you to "pin" a version of the code -- I should probably back up the "pinned" version
