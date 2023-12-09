# bredit

Built with the Next.js App Router, TypeScript & Tailwind

## Features
* Implement infinite scrolling for dynamically loading posts
* Enable authentication using NextAuth along with Google
* Create a custom feed for authenticated users
* Utilize Prisma as the database for efficient data storage
* Advanced caching using Upstash Redis
* Modern data fetching using React-Query
* Image uploads & link previews
* Full comment functionality with nested replies

## Getting started
To get started with this project, follow these steps

### 1. clone the Repository
```
git clone <repository-url>
```
### 2. install Dependencies
Navigate to the project directory and install the necessary dependencies, run
```
npm install
```
### 3. run the Development Server
Start the development server to preview project, run
```
npm run dev
```
### 4. connect to the Database
To set up the database, use Prisma to apply migrations, run
```
npx prisma db push
```

### 5. to check the Database
To view all the post recorded， Prisma Studio is up on http://localhost:5555， run
```
yarn prisma studio
```
