# HOWTOs

Several HOWTOs relevant to Data 602

# HOWTO: Load a file in Colab from your Google Drive

* When you are using the browser to view your Google Drive, you can right click on any file in your drive and then “Get shareable link.” You’ll get prompted to share the file, and you should set permissions so that anyone with the URL can read.  That URL will contain the file ID.  
* Here’s some code that works for accessing a CSV with the IMDb movie reviews, which I’m sharing from my google drive.  The part that appears after “id=“ is the ID, which I obtained from the shareable link. As a result, the following works in colab for anyone.
    import pandas as pd
    url = "https://drive.google.com/uc?export=download&id=1C7Rw06hhv0HgyjN28nMie6iI77F7jaiL"
    df = pd.read_csv(url)
If you put the URL into a browser that’s running with Incognito mode, then it will download the CSV to your local machine.

# HOWTO: Get started with Blackboard

It's easy to get lost in the Blackboard GUI. The left-hand menu bar has a zillion options. And sometimes you can navigate to the course content in multiple ways.

* Start with the default URL for "Courses"
    * https://blackboard.umbc.edu/ultra/course
* Click on the icon for the course of interest.
    * This will open a popup with a purple "X" in the upper left.
    * The left-hand menu bar on this page will open up with the configuration from the last time you were here
* This is where it can get confusing. So remember, the left-hand menu bar has two main roots...
    * A menu item with the course name: "Data 602 Introduction to Data Analysis and Machine Learning..."
        * This is where you go to create and deploy tests, etc.
    * A menu item under "Course Management" called: "Control Panel"
        * This is where you start Blackboard Collaborate sessions, check student grades, etc.

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

# HOWO: Create a test

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

# HOWTO: Send email

* Login to blackboard
* Click on Courses
* Click on "Course Tools" in left-hand menu
* Scroll down and click on "Send email"
* Click on "All users"

# HOWO: class notebooks

* Colab allows you to "pin" a version of the code -- I should probably back up the "pinned" version
