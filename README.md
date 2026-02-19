PROJECT: AUTOMATED PROJECT BOOTSTRAPPING AND PROCESS MANAGEMENT

HERE IS A VIDEO EXPLAINING THE PROJECT IN DETAIL [Explanation video](https://drive.google.com/file/d/1ANInxjbKWK0HIEDUo6fiepKEDoPX2aSw/view?usp=sharing).

The setup_project.sh script automates the creation of an attendance tracker enironment

THE SCRIPT CAN DO THE FOLLOWING:

Automated creation of the directory structure, Dynamic editing of config, Signal handling and archiving, Environment checkup for the presence of python3, and Directory structure validation.

HOW TO RUN THE SCRIPT:

USE: bash setup_project.sh

After running the script you will be prompted to enter a unique suffix for the directory, then you can also change the warning and failure threshhold marks (The changes will be directly applied in the config.json file)


Then the script will check for the presence of python3 and check if the directory structure is correct.

After that you then go into the attendance_tracker directory you created and run the attendance_checker python file. It will then review the student attendance from assets file and relating to the new thresholds you entered and create a report in the reports directory with a timestamp.

HOW TO TRIGGER THE ARCHIVE FEATURE

After entering the unique suffix of your directory name click CTR+C

This will archive the current state of the project directory into an archive file named attendance_tracker_(your unique suffix)_archive, and then delete the incomplete directory to keep the work space clean.


