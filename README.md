
#Kanban App
####built using React and webpack.

Deployed via gh-pages [here](https://alexthedar.github.io/kanbantut/)

This is a kanban web app built to learn react.  It basically is a glorified todo list.

1. User can create, edit, destroy lanes
2. User can create, edit, destroy, drag and drop notes.
3. Data is persists.

*What is Kanban?*
[wikipedia](https://en.wikipedia.org/wiki/Kanban)

###For local dev:
####Node and npm required
1. clone repo: https://github.com/alexthedar/kanbantut.git
2. npm install
3. npm run start
4. goto: localhost:8080

---

**Things left undone**

Styling, styling, styling!  Yes, this needs better styling.  Right now it is functional but not pretty.

Drag and Drop Lanes.  It would be nice to have the ability to reorder lanes via drag and drop as notes are currently.  

Deleting a Lane does not delete its notes.  Currently when you delete a lane with notes the notes are no longer accessible to the user but the notes still exist to the app.  

Drag and Drop for touch screens.  Drag and drop does not work on touch screens and so something needs to be implemented to accommodate mobile devices.  
