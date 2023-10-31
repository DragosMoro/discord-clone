# Discord Clone

Take a look: [https://discord-clone-next-js-13.up.railway.app/](https://discord-clone-next-js-13.up.railway.app/).

This is a feature-rich web application that replicates the functionality of Discord. It allows users to engage in real-time messaging, share attachments, create channels, manage members, and more. The application is built with cutting-edge technologies to provide a seamless user experience.

## Features

### Real-time Messaging

- Utilizes Socket.io for real-time messaging.
- Users can send text messages instantly.
- Supports sending attachments as messages using UploadThing.

### Message Management

- Allows users to delete and edit messages in real time.
- All changes are reflected for all users in the conversation.

### Communication Channels

- Users can create text, audio, and video call channels.
- Supports 1:1 conversations between members.
- Enables 1:1 video calls between members.

### Member Management

- Provides member management features such as kick and role change (guest/moderator).
- Admins can efficiently manage the community.

### Invite System

- Generates unique invite links for inviting new members.
- Fully functional invite system for growing your community.

### Message Loading

- Implements infinite loading for messages in batches of 10.
- Utilizes Tanstack/Query for efficient data retrieval.

### Server Customization

- Allows server creation and customization to fit your community's needs.

### User Interface

- Features a beautiful UI designed with TailwindCSS and ShadcnUI.
- Ensures full responsiveness and a mobile-friendly interface.
- Supports both light and dark mode.

### Websocket Fallback

- Includes a websocket fallback mechanism using polling with alerts for reliability.

### Database and ORM

- Utilizes Prisma as the ORM for database operations.
- Stores data in a MySQL database hosted on Planetscale.

### Authentication

- Implements authentication using Clerk for secure user management.

## Deployment

The application is deployed at [https://discord-clone-next-js-13.up.railway.app/](https://discord-clone-next-js-13.up.railway.app/).

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository.
2. Install the necessary dependencies.
3. Configure your environment variables.
4. Run the application.

```bash
git clone https://github.com/DragosMoro/discord-clone.git
cd discord-clone
npm install
# Configure your environment variables
npm start
