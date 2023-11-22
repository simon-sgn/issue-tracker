# Issue tracker

## About the project

Issue tracker is a web application designed to facilitate the creation, viewing, and management of issues. This is a project with the primary aim of learning Next.js, created during a Next.js development course.

## Live demo

Experience Issue tracker in action at **https://issue-tracker-simon-sgn.vercel.app**.

## Main stack

Next.js (App Router), Radix UI, TailwindCSS, TypeScript, RESTful APIs, Prisma, MySQL.

## Key features

User authentication with Google account (NextAuth.js), CRUD operations for issues, issues filtering and sorting, assignment of issues to users, dashboard for summary of issues, pagination, and responsive design.

## Installation

1. Clone **[the repository](https://github.com/simon-sgn/issue-tracker)** to your local machine.
2. Create a `.env` file and add the following lines:

```
DATABASE_URL="YOUR_MYSQL_DATABASE_URL" # You can find various examples of DATABASE_URL here: https://www.prisma.io/docs/reference/database-reference/connection-urls
NEXTAUTH_URL="http://localhost:3000" # THE URL OF YOUR DEVELOPMENT SERVER
NEXTAUTH_SECRET="YOUR_NEXTAUTH_SECRET"
GOOGLE_CLIENT_ID="YOUR_GOOGLE_CLIENT_ID" # You need to set up OAuth on Google Cloud Platform to get a Client ID and Secret
GOOGLE_CLIENT_SECRET="YOUR_GOOGLE_CLIENT_SECRET"

```

3. Install the necessary dependencies with `npm install`.
4. Run `npx prisma migrate` dev to generate your database tables.
5. Run `npm run dev` to start the web server.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## Contact

If you have any questions or suggestions, please feel free to contact me at simonnguyen.sgn@gmail.com. Also, feel free to connect with me on [Linkedin](https://www.linkedin.com/in/thien-nguyen-sgn).
