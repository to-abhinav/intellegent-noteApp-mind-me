<<<<<<< HEAD
# Intelligent Note-Taking App with Chatbot

This application is a **Next.js-powered intelligent note-taking app** that combines note management with an AI-based chatbot. The bot has access to all saved notes and enables interaction based on their content.

## Key Features

1. **Note Management**  
   - Easily create, update, and delete notes as needed.
2. **AI Chatbot**  
   - Interact with an intelligent chatbot that can answer questions based on saved notes, enhancing productivity and organization.
3. **Efficient Search and Retrieval**  
   - Integrated with Pinecone for vector-based search, enabling fast and contextually relevant responses.
4. **Secure Authentication**  
   - User authentication and OTP verification powered by Clerk.
5. **Powered by OpenAI**  
   - Utilizes OpenAI's API to deliver natural language responses based on the content of your notes.


## Tech Stack

- **Frontend**: Next.js
- **Authentication**: Clerk (for authentication and OTP verification)
- **Backend**: Node.js, Express (optional for API routes)
- **Database**: MongoDB (for storing notes)
- **ORM**: Prisma (for managing MongoDB data models and database access)
- **Vector Database**: Pinecone (for storing and retrieving embeddings)
- **AI Model**: OpenAI API (for language understanding and responses)

## Installation

### Prerequisites

1. Node.js (v14 or later)
2. MongoDB (local instance or MongoDB Atlas)
3. Pinecone account and API key
4. OpenAI account and API key
5. Clerk account and API keys

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/to-abhinav/intellegent-noteApp-mind-me.git

   ```
```bash
cd intellegent-noteApp-mind-me.git
```

```bash
npm install
```
## create a .env(dotenv) file
```
DATABASE_URL=your_mongoDB_uri
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/notes
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/notes
OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
```

## Set up prisma
```bash
npx prisma db push
```
## Run the application 
```bash
npm run dev
```
##Access the Application 
Open your browser and go to http://localhost:3000 to start using MindMe.


### Feel free to message me on [Linkedin](https://www.linkedin.com/in/to-abhinav/) 


##License
This project is licensed under the MIT License.

=======
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
>>>>>>> 01ea5ca (Initial commit)
