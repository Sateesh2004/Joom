

# Joom
The Joom App is a dynamic real-time video calling web application designed to deliver seamless communication experiences for users. Built using modern technologies like Getstream and Next.js, the application supports group video calls for up to 7 participants, screen sharing, and real-time chat, making it ideal for virtual meetings and collaboration. 

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
  - [Frontend Setup](#frontend-setup)
  - [Backend Setup](#backend-setup)
- [Usage](#usage)
- [Screenshot](#screenshot)
- [Future Enhancements](#future-enhancements)

## Features

- **Group Video Calling**: Supports real-time group video calls for up to 7 participants.
- **Screen Sharing**: Enables participants to share their screens for presentations or collaboration.
- **Real-Time Chat**:  Integrated chat functionality for instant messaging during calls.
- **Secure Authentication**: User authentication and management powered by Clerk for enhanced security.
- **Responsive Design**: Built using Next.js and Tailwind CSS for a seamless user experience across devices.

## Technologies Used

- HTML
- CSS
- Tailwind CSS
- JavaScript
- React
- Next.js
- GetStream.io

## Setup and Installation
Clone the repository.
   ```bash
   git clone https://github.com/Sateesh2004/Joom
   ```

### Setup

1. Install the necessary dependencies.
   ```bash
   npm install
   ```
2. Create a `.env` file for environment variables (e.g., clerk-api-key).
   ```bash
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-api-key
   CLERK_SECRET_KEY=your-api-key
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=your-api-key
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=your-api-key
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=your-api-key
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=your-api-key
   NEXT_PUBLIC_STREAM_API_KEY=your-api-key
   STREAM_SECRET_KEY=your-api-key
   ```
3. Run the server.
   ```bash
   npm start
   ```
4. It will run at http://localhost:3000. Make sure port 3000 is available and not in use by any other service.

## Usage

1. Sign up or log in using your credentials.
2. Start or schedule a meeting.
3. Share the link with others.
4. Collaborate on meeting.

## Screenshot

**Homepage**

![image](https://github.com/user-attachments/assets/9ce83cdd-e9d4-45c5-953f-bfdf07e23643)

**Previous Calls**

![image](https://github.com/user-attachments/assets/696763b3-7e96-4800-9577-119a5c65cc5b)

**Personal Meeting Room**

![image](https://github.com/user-attachments/assets/5d69807c-eeb1-46ca-9760-54ee2ce409a2)


**Meeting Room:**

![image](https://github.com/user-attachments/assets/9a5a54d2-ce98-4d4f-a022-bda35504d402)


## Future Enhancements

Here are some potential future enhancements for the platform:

1. **Increase Participant Limit**:
   - Allow more than 7 participants in group video calls to support larger meetings or events.
   - Provide performance metrics (e.g., video call quality, connection stability) and success rates for calls.
