# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR-task-3


 **COMPANY**: CODTECH IT SOLUTIONS
 
 **NAME**: DIKSHITH M Y
 
 **INTERN ID**:CT08LXT
 
 **DOMAIN**: Full Stack Web Development
 
 **BATCH DURATION**:m January 15th, 2025 to February 15th, 2025
 
 **MENTOR NAME**:Neela Santhosh Kumar 

**DESCRIPTION OF TASKS PERFORMED**  




This project is a real-time collaborative document editor that allows multiple users to edit a document simultaneously, with changes reflecting instantly for all connected users. Built using HTML, CSS, and JavaScript for the frontend, and Node.js, Express.js, and Socket.io for the backend, this application enables seamless collaboration through WebSocket-based communication. The editor provides a simple and distraction-free interface, making it easy for users to focus on content creation while ensuring real-time synchronization across multiple devices and browsers.

The backend is powered by Node.js and Express.js, which handle server requests and manage WebSocket connections using Socket.io. When a user connects, they receive the latest version of the document stored in memory. As users type, their changes are transmitted in real-time to the server, which then broadcasts updates to all connected clients. This ensures that every user sees the most up-to-date version of the document without needing to refresh the page. The frontend consists of a basic text editor created using an HTML contenteditable div, styled with CSS for a clean and intuitive user experience. JavaScript handles WebSocket communication, detecting input changes and sending updates to the server while receiving real-time updates from other users.

To set up the project, simply install Node.js and clone the repository. After installing the necessary dependencies with npm install, start the server using node server.js. Then, open index.html in a browser and begin editing. Opening multiple browser windows will demonstrate real-time synchronization, as any changes made in one window instantly reflect in others. This implementation currently stores document content in memory, but it can be extended to use a database like MongoDB or Firebase for persistent storage.

Future enhancements for this project include adding user authentication, enabling multiple document support, and implementing conflict resolution techniques such as Operational Transformation (OT) or Conflict-Free Replicated Data Types (CRDTs) to handle simultaneous edits more efficiently. Additionally, integrating rich-text formatting and export options would make this editor more versatile for various use cases.

This project showcases the power of WebSockets for real-time communication and is an excellent foundation for building collaborative web applications. Whether for note-taking, team collaboration, or online coding environments, this real-time editor demonstrates the potential of real-time synchronization with modern web technologies. 🚀


This project is a real-time collaborative document editor built using only HTML, CSS, and JavaScript, without any backend or external libraries. The goal is to create a simple text editor where users can type and see their changes in real time. This is achieved by utilizing local storage and JavaScript event listeners to save and retrieve content dynamically.

The editor consists of a contenteditable div, allowing users to type freely without requiring a traditional <textarea>. JavaScript listens for user input and updates the local storage, ensuring that the text remains saved even if the page is refreshed. This setup enables basic collaboration within a single device but does not support real-time synchronization across multiple users.

CSS is used to enhance the appearance of the editor, making it visually appealing and user-friendly. The styling ensures proper spacing, borders, and a clean interface for text editing. JavaScript handles user interactions by detecting changes in the div and saving them automatically.

To use the project, simply open the index.html file in a browser and start typing. The editor will automatically save the content, allowing users to return later and continue where they left off. This implementation can be further improved by adding real-time syncing via WebSockets or cloud storage integration for multi-user collaboration.

This project serves as a foundational implementation of a collaborative text editor and can be expanded with more advanced features like multi-user editing, formatting options, and document management. 🚀

![Image](https://github.com/user-attachments/assets/d838a78f-ae6d-48db-b731-9c409040f3f3)
