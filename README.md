# Connectopia

## Overview

It is a website created using Next.js 13 with a wide range of features and technologies to provide users with a robust chat and communication platform. It offers real-time messaging, multimedia support, voice and video calls, member management, server customization, and more.

## Features

### Real-time Messaging

- Utilizes Socket.io for real-time messaging, ensuring instant communication between users.

### File Attachments

- Users can send attachments as messages, enhancing the user experience.

### Message Management

- Allows users to delete and edit messages in real time, ensuring a smooth and interactive chat experience.

### Communication Channels

- Supports text, audio, and video call channels, offering various communication options to users.

### Private Conversations

- Enables one-on-one conversations between members for private interactions.

### Video Calls

- Supports one-on-one video calls between members for face-to-face communication.

### Member Management

- Admins can kick users and change their roles between guest and moderator for effective member management.

### Invite System

- Implements a unique invite link generation system for inviting new members to the platform.

### Message Pagination

- Uses tanstack/query to load messages in batches of 10, providing an efficient and seamless chat experience.

### Server Customization

- Allows users to create and customize servers to tailor their experience to their preferences.

### User Interface

- Features a beautiful and responsive UI design using TailwindCSS and ShadcnUI, ensuring an aesthetically pleasing user experience.

### Light/Dark Mode

- Offers both light and dark mode options to accommodate user preferences and reduce eye strain.

### Websocket Fallback

- Implements a fallback mechanism using polling with alerts in case WebSocket connectivity is unavailable.

### Database and ORM

- Utilizes Prisma as an Object-Relational Mapping (ORM) tool and a MySQL database hosted on Planetscale for efficient data management.

### Authentication

- Implements user authentication using Clerk for secure and personalized user experiences.



## Technologies Used

The Discord clone website is built using the following technologies and tools:

- **Next.js 13:** A popular JavaScript framework for building modern web applications, offering server-side rendering and a great developer experience.

- **Socket.io:** A library for real-time, bidirectional communication between clients and the server, enabling instant messaging.

- **UploadThing:** Used for sending attachments as messages within the chat application.

- **Prisma:** An Object-Relational Mapping (ORM) tool for working with databases, simplifying database interactions.

- **MySQL (Planetscale):** A relational database used for storing and managing data, hosted on Planetscale for scalability and reliability.

- **Clerk:** Provides user authentication and user management features to enhance security and user experiences.

- **Tanstack/Query:** Used for efficient message pagination, fetching data in batches for a smooth chat experience.

- **TailwindCSS:** A utility-first CSS framework for creating beautiful and responsive user interfaces.

- **ShadcnUI:** A UI component library or framework used to enhance the aesthetics and user experience of the website.


