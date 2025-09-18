---
layout: project
type: project
image: img/vacay/chaticon.png
title: "Real-Time Chat"
date: 2025
published: true
labels:
  - React
  - Node.js
  - Websockets
summary: "A full-stack chat app enabling real-time messaging over WebSockets with support for multiple users."
---

<div class="text-center p-4">
  <img width="600px" src="..img/vacay/chatscreenshot" class="img-thumbnail" >
</div>
The Real-Time Chat Application is a full-stack personal project built to explore real-time communication technologies using React, Node.js, and WebSockets. The application allows multiple users to connect simultaneously and exchange messages instantly, with dynamic updates to chat windows as new messages arrive. It supports both group conversations and one-on-one chats, offering a versatile environment for different communication needs. To extend beyond text messaging, I added support for image and file sharing, as well as delivery and read receipts to improve usability. Authentication and session management were integrated to ensure that conversations remained secure, and chat history could be retrieved whenever a user returned.

I designed and developed the project end-to-end, starting with setting up a Node.js server to handle WebSocket connections and efficiently route messages between clients. On the front end, I built a responsive React interface that displayed real-time updates, managed multiple active chats, and incorporated features like read receipts and file previews. I also implemented secure authentication and database integration to store user accounts and persistent chat records. Throughout the project, I focused on performance and scalability by optimizing socket event handling and ensuring that the system could support multiple users at once without lag. The finished application provided a feature-rich demonstration of real-time web development and gave me practical experience in building secure, scalable, and interactive applications from scratch.
