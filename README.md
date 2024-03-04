# Realtime Chat App with Next.js

## Project Overview

Realtime Chat App with Next.js is a web application that facilitates instant messaging between users. It features Google authentication for secure logins, friend invitations via email, and real-time chatting functionality. The application uses Redis as the database to store data.

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Kumar7708/realtime-chat-app.git
   cd realtime-chat-app
   ```
Install dependencies:

```bash
npm install
```
Set up environment variables:

Create a .env file in the root directory and add the following:

```bash
NEXTAUTH_SECRET=

UPSTASH_REDIS_REST_URL=
UPSTASH_REDIS_REST_TOKEN=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

PUSHER_APP_ID=
NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_APP_CLUSTER=ap2
```

Run the application:

```bash
npm run dev
```
### Features:

## Google Authentication:
Users can log in securely using their Google accounts, providing a seamless and reliable authentication process.

## Adding Friends:
Users can add friends to their contact list by sending email invitations. Once the friend accepts the invitation, they become part of the user's contacts.

## Real-time Chatting
Enjoy real-time conversations with added friends. Messages are delivered instantly, providing a smooth and responsive chat experience.

### Usage:

1. Log in using your Google account.
2. Add friends by sending email invitations.
3. Start real-time conversations with added friends.
