# Jobs
Jeeves Projects can have Jobs. **Jobs** enable you to automate your testing tasks, setting an expected successful responses percentage, running all the Project Test Cases in a sequence without you having to initialize each Test Case. If the results obtained seem that they will not reach the expected percentage during the running of a Job, the Job run stops and delivers a **BAD** status, warning you that your Project availability is not as expected. 

Jobs contain the following information: 

* **Execution notes:** The name of the Job.
* **total tasks**: The number of Test Cases the Job will run. Not editable.
* **required score:** The expected percentage of successful Test Cases.

To know more about the Jobs parameters, see the [Job Details](#job-details) section.

<a href="#test-case-home-page" class="go-back"> ← Go back to the Test Case Home page section </a>


## Create a Job
To create a Job for a project, you can choose one of the following options:

* [Generate a Bash Script](#generate-a-bash-script)
* [Manual Run](#manual-run)

See the sections above to learn how to run a Job.

<a href="#jobs" class="go-back"> ← Go back to the Jobs section </a>

### Generate a Bash Script
To **create and run a Job with a Bash Script**, follow these steps:

1. Select a **Project** profile from the **Jeeves Home page**.
</br>The selected **Project Home page** appears.
2. On your **Project Home page**, select the Jobs tab.
</br>The **Jobs** page appears.
3. Click the **+ Create** button on the top right corner of the **Project Home page**.
</br>The **New Job** page appears.
4. Enter the purpose of the new Job in the **Execution Notes** field. 
5. Enter the expected successful Test Cases percentage in the **Required Score** field.
6. Click the **Generate Bash Script** button.
</br>The auto-generated **Bash Script** appears.
7. Copy the auto-generated **Bash Scrip**t.
8. Open your computer Terminal.
9. Create a **`.sh`** file with the following command:
```
touch name-of-your-file.sh
```

10. Open the file in your Terminal editor with the following command:
```
nano name-of-your-file.sh
```

11. Paste the auto-generated **Bash Script** to the Terminal.
12. Save the Bash Script, press the **`CONTRL + O`** keys.
13. Confirm the file name, press the **`ENTER`** key.
14. Exit the Terminal editor, press the **`CONTRL + X`** keys.
15. Run the Bash Script with the following command:
```
sh the-name-of-your-file.sh
```

</br>The Job starts running and appears in the Project Jobs page.

<aside class="success"> After following the preceding steps, you have run a Job with a Bash Script successfully. 
</aside>

To learn how to do a manual run of a Job, check the [Manual Run](#manual-run) section.

<a href="#jobs" class="go-back"> ← Go back to the Jobs section </a>

### Manual Run
To **create and run a Job** with Jeeves, follow these steps:

1. Select a **Project** profile from the **Jeeves Home page**.
</br>The selected **Project Home page** appears.
2. On your **Project Home pag**e, select the **Jobs** tab.
</br>The **Jobs** page appears.
3. Click the **+ Create** button on the top right corner of the Project Home page**.
</br>The **New Job** page appears.
4. Enter the purpose of the new Job in the **Execution Notes** field. 
5. Enter the expected successful Test Cases percentage in the **Required Score** field.
6. Click the **Manual Run** button.
</br>The Job starts running and the Job Details page appears.

<aside class="success">After following the preceding steps, you have done a Manual Run successfully. 
</aside>

To learn about the information and the status of a Job run, see the [Job Details](#job-details) section.

<a href="#jobs" class="go-back"> ← Go back to the Jobs section </a>

## Job Details
During and after you run a Job, you can check its status and details in the Job Details page.  The **Job Details page** contains the following information:

* **Tracking Number:** The identification number of the Job.
* **Execution Notes:**The purpose of the Job.
* **Total Tasks:** The number of Test Cases in the Job.
* **Progress:** The Test Case number that the Job is running.
* **Termination Code:** The health status code of the Job after finishing.
* **Duration:** The time taken during the Job run.
* **Logs:** The Job run processes description. 

<a href="#jobs" class="go-back"> ← Go back to the Jobs section </a>