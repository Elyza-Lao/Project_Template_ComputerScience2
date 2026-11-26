# 📌 Project Proposal (Draft)

## 📝 Project Title  
Student Study Buddy (Planner)

---

## 🔍 Problem Statement  
What real-world problem does your project want to solve?  
Brief Description:
This project aims to help students have a personal helper that keeps them on track with their assessments, requirements, deadlines and tests to help them stay organized with their schedules. The system helps them by creating study plans and tracking their progress on requirements so they can work on them day by day rather than cramming. In addition, it reminds students of upcoming assignments, assessments, and tests.

Problem Statement:
Many students have a difficult time keeping track of their assignments, assessments, requirements, and deadlines, mainly due to forgetting about assigned tasks or having disorganized schedules. This makes them resort to cramming when studying for tests or completing requirements. This is a problem because it may lead to missed tasks and poor time management. In addition, some students immediately resort to using AI without actually understanding what the requirement is all about, focusing more on quickly completing the work rather than learning from it. Without a proper study plan, students may also have difficulty balancing their academic workload and tracking their progress.

Target Users / Beneficiaries:
The target users are mainly students who have difficulty organizing their schedules and those who often cram when studying for tests or completing requirements

- Relate the problem to the dataset you selected (e.g., hospital, ecommerce, students, etc.).  

---

## 🎯 Project Objectives  
Write at least **2–3 clear objectives** your project aims to achieve. Example:  
- Objective 1: To analyze and summarize data from the chosen JSON dataset.  
- Objective 2: To help users gain meaningful insights (e.g., averages, trends, patterns).  
- Objective 3: To practice JSON handling and Python programming concepts.  

---

## ⚙️ Planned Features  
Your program must have **at least 5 features (minimum)**.  
We have provided **2 starter ideas** for each dataset — you must design **at least 3 additional features**.  
Outline of Features
The features include adding subjects, schedule study sessions, track completed tasks, and summarize study hours.
Add School Tasks/To-do 
- Allows users to add assignments, schoolwork, or a simple reminder.
- Stores assignments, schoolwork, and reminders added and set by users, including their task names, subjects, deadlines, priority levels, and completion status
 
Set Deadlines and Priorities 
-Allows users to set a deadline and priority level for each Tasks
-Stores the deadline and priority level assigned to each task, allowing users to organize their schoolwork and identify which tasks need to be completed first. 

Update task progress
- allows users to update the status of tasks as NOT  STARTED, IN PROGRESS, or COMPLETED
- Stores the status of each task, allowing users to track their progress and easily identify what they need to work on next. 

View Task 
- Allows user to view what task they have left
- Retrieves stored task information, such as task names, subjects, deadlines, priorities, and statuses, so that users can easily keep track of their remaining tasks. 

Edit Tasks
- Stores the updated task information so users can make changes to their saved tasks whenever necessary
- Allows users to modify the details of an existing task, such as its name, subject, deadline, or priority level.
  
Delete Tasks
- Allows users to remove tasks that are no longer needed or that were added by mistake.
- Updates the stored task information by removing the selected task from the saved records.

View Deadline Alerts
- Allows users to see upcoming deadlines and identify tasks that are due soon or overdue.
- Retrieves saved task deadlines and show upcoming and overdue tasks.

---

## ⌨️ Planned Inputs and Outputs  
Inputs
Task Name
- Name of the assignment, schoolwork, assessment, or reminder
Subject
-	Subject related to the task
Deadline
-	Date when the task should be completed
Priority Level
-	Importance of the task (High, Medium, or Low)
Task Status
-	Progress of the task (Not Started, In Progress, or Completed)
Estimated Study Hours
-	Estimated time needed to complete or study for the task
Menu Selection
-	Allows users to choose an action, such as adding, viewing, editing, or deleting tasks

**Outputs**  
Task List
- Displays all saved assignments, schoolwork, and reminders
Task Details
- Shows the task name, subject, deadline, priority, and status
Updated Task
- Progress	Displays the latest status of each task
Deadline Alerts
-	Shows upcoming deadlines, tasks due today, and overdue tasks
Study Schedule
-	Displays the user's planned study sessions
Progress Report
-	Summarizes completed, ongoing, and unfinished tasks
Study Hour Summary
-	Displays the total estimated study hours

---

## 🧠 Logic Plan  
Describe your program’s logic:  

### Pseudocode  
START

Load the saved task information from the JSON file.

Check the saved tasks for upcoming and overdue deadlines.

Display deadline alerts, if there are any.

Display the main menu:
    1. Add a New Task
    2. View Tasks
    3. Update Task Progress
    4. Edit Task
    5. Delete Task
    6. View Study Schedule
    7. View Progress Report
    8. Exit

Ask the user to select an option.

IF the user selects 1:
    Ask for the task name, subject, deadline, priority level, and estimated study hours. 
    Set the initial task status.
    Save the new task in the JSON file.

ELSE IF the user selects 2:
    Display all saved tasks and their details.

ELSE IF the user selects 3:
    Display the saved tasks.
    Ask the user to select a task.
    Allow the user to update its status.
    Save the changes in the JSON file.

ELSE IF the user selects 4:
    Display the saved tasks.
    Ask the user to select a task.
    Allow the user to edit its information.
    Save the changes in the JSON file.

ELSE IF the user selects 5:
    Display the saved tasks.
    Ask the user to select a task.
    Confirm the deletion.
    Remove the selected task from the JSON file.

ELSE IF the user selects 6:
    Display the user's study schedule
    based on their saved tasks and planned study sessions.

ELSE IF the user selects 7:
    Calculate the number of completed,
    ongoing, and unfinished tasks.
    Calculate the task completion rate.
    Display the progress report and estimated study hours.

ELSE IF the user selects 8:
    Display an exit message.

ELSE:
    Display an invalid selection message.

Repeat the menu until the user chooses to exit.

END


### Flowchart  
Attach or draw a flowchart showing how the program will work.  

---


## 📂 GitHub Repository Link  
Paste your GitHub repository link here:  
`https://github.com/username/project-proposal`  

---
