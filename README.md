# Discord Clone

Take a look [here](https://discord-clone-next-js-13.up.railway.app/).

This is a feature-rich web application that replicates the functionality of Discord. It allows users to engage in real-time messaging, share attachments, create channels, manage members, and more. The application is built with cutting-edge technologies to provide a seamless user experience.

## Features

1. **Real-time Messaging**

    - Utilizes Socket.io for real-time messaging.
    - Users can send text messages instantly.
    - Supports sending attachments as messages using UploadThing.

    ![Real-time Messaging](https://github.com/DragosMoro/discord-clone/blob/master/public/1-1chat.png)

2. **Message Management**

    - Allows users to delete and edit messages in real time.
    - All changes are reflected for all users in the conversation.

    ![Message Management](https://github.com/DragosMoro/discord-clone/blob/master/public/overview.png)

3. **Communication Channels**

    - Users can create text, audio, and video call channels.
    - Supports 1:1 conversations between members.
    - Enables 1:1 video calls between members.

    ![Communication Channels](https://github.com/DragosMoro/discord-clone/blob/master/public/1-1voice.png)

4. **Member Management**

    - Provides member management features such as kick and role change (guest/moderator).
    - Admins can efficiently manage the community.

    ![Member Management](https://github.com/DragosMoro/discord-clone/blob/master/public/manage-members.png)

5. **Invite System**

    - Generates unique invite links for inviting new members.
    - Fully functional invite system for growing your community.

    ![Invite System](https://github.com/DragosMoro/discord-clone/blob/master/public/invite.png)

6. **Message Loading**

    - Implements infinite loading for messages in batches of 10.
    - Utilizes Tanstack/Query for efficient data retrieval.

7. **Server Customization**

    - Allows server creation and customization to fit your community's needs.

    ![Server Customization](https://github.com/DragosMoro/discord-clone/blob/master/public/create-server.png)

8. **User Interface**

    - Features a beautiful UI designed with TailwindCSS and ShadcnUI.
    - Ensures full responsiveness and a mobile-friendly interface.
    - Supports both light and dark mode.

    ![User Interface Light](https://github.com/DragosMoro/discord-clone/blob/master/public/light-mode.png)

9. **Websocket Fallback**

    - Includes a websocket fallback mechanism using polling with alerts for reliability.


10. **Database and ORM**

    - Utilizes Prisma as the ORM for database operations.
    - Stores data in a MySQL database hosted on Planetscale.


11. **Authentication**

    - Implements authentication using Clerk for secure user management.

    ![Authentication](https://github.com/DragosMoro/discord-clone/blob/master/public/auth.png)

## Deployment

The application is deployed [here](https://discord-clone-next-js-13.up.railway.app/).
