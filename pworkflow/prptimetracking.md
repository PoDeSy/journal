- [ ] +podesy time tracking
Using apps epsilon, agrep, clockwork tomato and tasker to track time spent on project tasks

modifies:
[prjmanage](prjmanage.md)

2021-04-09: I had to give tasker clipboard monitor access via ADB on laptop. When tasker sees copied text starting with a checkbox, clockwork tomato is started and task name and start time is added to a CSV file. When clockwork tomato stops, end time is appended to the file.