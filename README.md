# TaskTracking

A new software has been rolled out in the company called "TaskTrack", which is used for time tracking, task management, and productivity monitoring. You are a customer engineer for TaskTrack. 

You receive a complaint from one of your customers that the application isn't accurately tracking time on certain tasks. They suspect this might be due to the system not properly recognizing when a task starts and stops, which leads to the inaccurate time tracking.

The customer has provided you with a data set of task logs from their TaskTrack application. Each log entry contains the following information:

1. The timestamp (in UNIX time) of the event.
2. The user ID of the person who created the event.
3. The task ID of the task involved in the event.
4. The event type - "Task Started", "Task Stopped", or "Task Completed".

The log entries are not sorted in any particular order. 

Your task is to analyze the log data, identify any discrepancies that might lead to inaccurate time tracking, and propose a solution to fix it. To do this:

1. Write a program that accepts the log data as input and produces a report of time spent on each task by each user. 
2. Test your program with different datasets and debug any issues you encounter.
3. Provide an explanation of your approach and any potential issues you identified in the dataset.
4. If there are any identified issues, provide a plan on how you would resolve them if given the opportunity.
