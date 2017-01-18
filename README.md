# base master = react-boilerplate from "SurviveJS - React"
# Thanks to the author Juho Vepsalainen for the work in putting together this book
# Dennis G Davis ddavis914
See [SurviveJS - React](http://survivejs.com/react/introduction/) for the book.

## Pre-requisites Web browser, node.js, git installed on the local computer.

## Getting Started - on Windows 10

1. Create a parent working directory on the local computer and navigate 'cd' to it
2. From the parent directory execute:
> git clone https://github.com/ddavis914/kanban-app.git kanban-app
2a. There were plenty of deprecation warnings - but no errors
2. When it finishes cd to the new kanban-app directory
3. From the kanban-app directory run:
> npm start
3a.if no other server is running on port 8080 you should see:

> react-boilerplate@2.5.6 start Drive:\Directories\kanban-app
> webpack-dev-server

 http://localhost:8080/
webpack result is served from /
content is served from Drive:\Directories\kanban-app
404s will fallback to /index.html
Child html-webpack-plugin for "index.html":

webpack: bundle is now VALID.

3b. Where Drive:\Directories = the hdd/parent driectory from which step 1 was applied
4. Open a web browser and navigate to:
http://localhost:8080/index.html

Functional Directions
1. The upper left hand corner of the browser page is a plus sign - right click to add a lane
2. In the 'New Lane' - right click open lane change editor
3. Notice an x appears as well right clicking on the x will delete the lane
4. The plus next to the lane name will add 'tasks' to the lane
5. As before clicking on the task lane opens the task name editor to edit the task name
6. As before the x that appears when hovering over the task name allows to delete the task from the lane
7. Drag and drop of tasks is enabled between lanes  
4. Start modifying the code. The browser should pick up the changes.

## Book applied to the base repository by Dennis G. Davis
