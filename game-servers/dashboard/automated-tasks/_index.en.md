+++
title = "Schedules"
date =  2021-03-24T22:10:47-04:00
weight = 103
+++

## Automated Server Tasks
Included in the game panel is the ability to automatically run timed server commands and actions. For this guide, a server restart will server as an example.

###
1. Navigate to the Schedules tab of your game panel. 
![Screenshot](/game-servers/images/tasks.png)
2. Create a schedule. Name it whatever you please, but we will name it "Auto Restart".
3. Specify the time you want the auto restart to take place. This menu uses chronjob syntax. If you are looking to set it to midnight, the minute and hour boxes should be set to 0, illustrated below. If you are wanting a different time, [this tool](https://crontab.guru/) will help you figure it out.
![Screenshot](/game-servers/images/tasks2.png)
4. Create the schedule and expand it from the schedules menu. Click "new task".
5. Here you are presented with three different options; send command, send power action, and create backup. For our purposes, select send power action.
6. Expand the payload dropdown and select "restart the server".

The task has been saved! It should now run every day at exactly 00:00. Feel free to experiment with this powerful tool, as automating your server tasks means less manual intervention.

---
#
This page written by [wizerd](/contributors/wizerd/).
![Banner](/images/fishy.gif)