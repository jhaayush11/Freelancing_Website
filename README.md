GigLink
The freelance website is a platform designed to connect clients with freelance professionals across various industries.It build using Next.js,TailwindCss,Express.js,Prisma,PostgreSQL,JWT token ,also It leverages the power of Next.js,React framework for server-side rendering and dynamic site generation, to provide a fast and efficient user experience

Next.js: Next.js is a popular React framework for building server-rendered React applications. It provides features like server-side rendering, static site generation, and routing, which enhance the performance and SEO of your app.

Tailwind CSS: Tailwind CSS is a utility-first CSS framework that helps you build responsive and customizable user interfaces rapidly. It provides a set of pre-defined CSS classes that you can combine to style your components easily

Express.js: a flexible and minimal web application framework for Node.js, serves as the back-end of the freelance website. It handles routing, API requests, and other server-side operations, providing a robust foundation for building RESTful APIs.

Prisma: To manage data persistence, Prisma, an open-source database toolkit, is integrated with PostgreSQL, a powerful and scalable relational database management system. Prisma simplifies database access by generating a type-safe and auto-completed query builder based on the database schema. It offers seamless integration with Express.js, making data retrieval, manipulation, and storage efficient and secure.

Roadmap
Project Setup

User Authentication

User Profiles

Project Listings

Project Creation and Management

Messaging and Communication

Payments and Escrow

Rating and Reviews

Unread Messages

Admin Dashboard

Documentation
NextJS Express.JS TailwindCSS Prisma Stripe

Installation
Install my-project with npm

  npx create-next-app@latest
  npm install express
  npm install @prisma/client
Running Tests
To run tests, run the following command

  client: npm run dev
  Server: npm run dev
  Prisma: npx prisma studio
Technology
NextJS

TailwindCSS

Express.JS

Prisma

PostgreSQL

Stripe

Features
User registration and authentication
Profile creation and management for freelancers and clients
Gigs creation, management and bidding
Edit Gigs from seller side
Search functionality for finding freelancers and projects
Secure payment processing using Stripe
Real-time messaging between freelancers and clients with read and unread features
Reviews and ratings for freelancers
Notifications for project updates
Project milestones and progress tracking
Screenshot
Home Page
Screenshot (88)

Login and Signup functionality
Screenshot (89)

Set User Profile
Screenshot (90)

Create Gigs
Screenshot (92)

Edit Gigs
Screenshot (94)

Search Gigs
Screenshot (91)

About Gig and Seller
Screenshot (96)

Secured Payment integration
Screenshot (97)

Redirecting to success Page
Screenshot (98)

User Purchase page
Screenshot (93)

Client and freelancer Private Conversation with read and unread features
Screenshot (103)

Reviews and Rating to Seller
Screenshot (95)

Dashboard
Screenshot (104)

Environment Variables
To run this project, you will need to add the following environment variables to your .env file

PORT PUBLIC_URL JWT_KEY DATABASE_URL stripe

Tech Stack
Client: Next.JS, Redux, TailwindCSS

Server: Node.JS, Express.JS

Database: Prisma ,postgreSQL

Payment: Stripe

Lessons Learned
Prisma integration with front-end

How to use prisma for authentication and authorization

How to use payment integration using stripe
