# QuickMeet: Next-Gen Video Conferencing Solution

QuickMeet is a robust video conferencing platform, built using the latest technologies to provide a seamless, secure, and feature-rich meeting experience. Whether you're hosting or attending a meeting, QuickMeet offers a full suite of functionalities for effective communication, from recording sessions to managing participants.

This project leverages the power of Next.js and TypeScript for optimal performance and scalability.

## Features

- **Secure Authentication:** Users can log in securely using Clerk, with support for social sign-ons and traditional email/password methods.
- **New Meeting Creation:** Start a meeting instantly, with options to configure camera and microphone settings before joining.
- **Meeting Controls:** Manage various aspects of the meeting, including:
  - Recording
  - Screen sharing
  - Emoji reactions
  - Mute/unmute controls
  - Participant management (pinning, muting, blocking, etc.)
- **Join via Link:** Easily join meetings using a unique link shared by the meeting host.
- **Schedule Meetings:** Set up future meetings with date and time details, accessible through the 'Upcoming Meetings' section.
- **View Past Meetings:** Browse a history of previous meetings with full details and metadata.
- **Personal Room:** Every user has a personal meeting room with a unique link for instant, on-demand meetings.
- **Recorded Meetings:** Access and view recorded meetings for review or reference.
- **Responsive Design:** The UI is designed to work seamlessly across all device types, from desktops to mobile phones.

## Tech Stack

- **Framework:** Next.js
- **Language:** TypeScript
- **Authentication:** Clerk
- **Real-time Messaging:** getstream
- **UI Design:** Tailwind CSS, shadcn

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
