<h1 align="center">Discord Clone</h1>

<p align="center">
  <img src="./public/discord-logo.svg" alt="Discord Clone Logo" width="200">
</p>

## Introduction

Welcome to the Discord Clone repository! This project is a developer-friendly real-time messaging application that emulates the functionality of Discord. It is built using modern web technologies and offers various features for seamless communication and collaboration.

## Key Features

- **Real-time Messaging:** Instantly chat with other users using Socket.io.
- **File Attachments:** Send files and images as messages using UploadThing.
- **Message Editing & Deletion:** Edit and delete messages in real-time.
- **Voice & Video Calls:** Create text, audio, and video call channels.
- **One-on-One Conversations:** Private one-on-one conversations between members.
- **Member Management:** Kick members and change their roles.
- **Invite System:** Generate unique invite links and set up an invite system.
- **Message Batching:** Load messages in batches of 10 for seamless conversation.
- **Server Customization:** Create and customize your server.
- **Stunning UI:** Beautifully designed using TailwindCSS and ShadcnUI.
- **Responsiveness:** Works flawlessly on both desktop and mobile devices.
- **Light & Dark Mode:** Choose your preferred viewing mode.
- **Websocket Fallback:** Ensures uninterrupted communication.
- **Database & ORM:** Prisma for database operations.
- **MySQL Database:** Utilize Planetscale for your MySQL database.
- **Authentication:** Secure the app with Clerk.

## Getting Started

To get started with this Discord Clone, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies using **Bun**, our lightweight and energetic package manager. Just run `bun install` and let the magic happen!
3. Configure your environment variables by creating a `.env` file based on the provided `.env.example`.
4. Set up your database and authentication configurations.
5. Run the application using `npm start`.
6. Explore the features and start developing or testing your own Discord-like application.

## Environment Variables

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=nclerk_publishable_key
CLERK_SECRET_KEY=clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# Database Configuration
DATABASE_URL=postgres://your_db_username:your_db_password@your_db_host/your_db_name?pgbouncer=true&connect_timeout=10
DIRECT_URL=postgres://your_db_username:your_db_password@your_db_host/your_db_name?connect_timeout=10

# UploadThing Configuration
UPLOADTHING_SECRET=uploadthing_secret
UPLOADTHING_APP_ID=uploadthing_app_id

# LiveKit Configuration
LIVEKIT_API_SECRET=livekit_api_secret
LIVEKIT_API_KEY=livekit_api_key
NEXT_PUBLIC_LIVEKIT_URL=wss://discord-clone.livekit.cloud
```

## Roadmap

Here's a roadmap outlining the planned features and improvements for my Discord clone application.

- [x] **Voice Chat Integration**

  - Implement real-time voice chat functionality for seamless communication.

- [x] **Video Chat Support**

  - Introduce video chat features for face-to-face conversations.

- [x] **Screen Sharing**

  - Enable screen sharing during calls for collaborative interactions.

- [x] **Direct Messaging**

  - Allow users to send private messages to other users.

- [x] **Message Editing**

  - Allow users to edit their messages in real-time.

- [x] **Real-time Typing Indicators**

  - Display the typing status of users in real-time.

- [ ] **Emojify Your Messages**

  - Allow users to react to messages with emojis. Also, display the number of reactions.

- [x] **Stay in the Loop**

  - Display the online status of users and their last active time.

- [ ] **Server Discovery**

  - Create a server discovery mechanism to help users find and join communities.

- [ ] **Server Categories**

  - Allow users to categorize their servers for better organization.

- [ ] **Rich Media Integration**

  - Improve media sharing capabilities, including support for gifs, videos, and link previews.

- [ ] **Custom Emojis and Stickers**

  - Allow users to personalize their messages with custom emojis and stickers.

- [ ] **Server Bots**

  - Integrate a bot API or allow users to add custom bots to their servers.

- [ ] **User Feedback and Bug Reporting**

  - Establish a feedback and bug reporting system to gather user input and improve the app.

- [ ] **Notifications**

  - Implement a notification system to keep users updated on new messages and events.

- [ ] **Localization**
  - Add support for multiple languages to cater to a global audience.

This roadmap is a dynamic plan that I'll continually update as I progress and gather feedback from everyone. If you have any suggestions or feature requests, please feel free to open an issue or submit a pull request.

## Contributing

We welcome contributions to this Discord Clone repository! If you find any bugs or issues, feel free to open an issue or submit a pull request. I also encourage you to add new features and improve the existing codebase.

## License

This Discord Clone repository is licensed under the MIT license. Please see the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Clerk](https://clerk.dev/)
- [Prisma](https://www.prisma.io/)
- [UploadThing](https://uploadthingy.com/)
- [LiveKit](https://livekit.io/)
- [TailwindCSS](https://tailwindcss.com/)
- [ShadcnUI](https://shadcnui.com/)
- [Socket.io](https://socket.io/)

## Credits

- [Discord Logo SVG](https://github.com/NNTin/discord-logo) by [NNTin](https://github.com/NNTin).
- [CodeWithAntonio](https://www.codewithantonio.com/) for the inspiration and guidance.
