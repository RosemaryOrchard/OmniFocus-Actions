# OmniFocus-Actions

These are some of the actions I use in OmniFocus on a regular basis.

### [Device Tasks](device-tasks.omnifocusjs)
This requires a tag called 'Devices'. When the action is run, you are asked for a task name and the contents of a note (optional), and then presented with a choice of the sub-tags of your Devices tag. Then one task per selected tag is added to the end of your OmniFocus inbox with the suffix ' on [tagName]' and the tag of the device.

### [Export Project List](export-project-list.omnifocusjs)
Export a list of your active projects, with the folder(s) prepended to the front. This will go as deep as you can nest, and it excludes any projects which are not active (i.e. dropped, completed, or on hold), single action lists, and those deferred to more than 7 days in the future.

### [Increase Due Dates in Project](increase_due_dates.omnifocusjs)
This requires you to have a project selected, and increases the due date of all the tasks in that project by one day. Tasks without a due date are not effected, and the project itself is not modified.

### [Process Inbox Tasks](process-inbox-tasks.omnifocusjs)
This finds any number of tasks which are of the sort regularly added to my inbox, and adds tags, cleans up task names, and moves the tasks to the right projects where possible. Used primarily for tasks added to OF through the share sheet from various websites, but also handles Blog Post Ideas and Waiting tasks.
