**Project Title**
This is a simple text editor built with React and Quill, with data stored in MongoDB.

**Description**
The text editor allows users to create and edit rich text documents, with the data stored in a MongoDB database. 
It uses the Quill library to provide a WYSIWYG editor with a rich set of formatting options, and socket.io 
for real-time collaboration between multiple users.

**Getting Started**
**Prerequisites**
Node.js
npm or yarn
MongoDB

Modify the MongoDB connection string in server/db.js to match your own MongoDB instance:

const uri = 'mongodb://your-username:your-password@your-mongodb-instance-url';

**To Run the project**
=> Go to server repo and run "npm install" after that run "npm start"

=> Go to client repo and run "npm install" after that run "npm start"

_Make sure to modify the db.js in server under database folder_

**Usage**
To use the text editor, simply open the application in your browser at http://localhost:3000.
You can then create or edit rich text documents using the formatting options provided by the Quill library.
Multiple users can collaborate on the same document in real-time thanks to socket.io.


**Acknowledgments**
Quill - The open source WYSIWYG editor used in this project.
MongoDB - The NoSQL database used to store text documents.
socket.io - The real-time websockets library used for collaboration.
