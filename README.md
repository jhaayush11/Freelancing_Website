# Freelancing_Website

# GigLink

The freelance website is a platform designed to connect clients with freelance professionals across various industries.It build using Next.js,TailwindCss,Express.js,Prisma,PostgreSQL,JWT token ,also It leverages the power of Next.js,React framework for server-side rendering and dynamic site generation, to provide a fast and efficient user experience


Next.js: Next.js is a popular React framework for building server-rendered React applications. It provides features like server-side rendering, static site generation, and routing, which enhance the performance and SEO of your app.

Tailwind CSS: Tailwind CSS is a utility-first CSS framework that helps you build responsive and customizable user interfaces rapidly. It provides a set of pre-defined CSS classes that you can combine to style your components easily

Express.js: a flexible and minimal web application framework for Node.js, serves as the back-end of the freelance website. It handles routing, API requests, and other server-side operations, providing a robust foundation for building RESTful APIs.

Prisma: To manage data persistence, Prisma, an open-source database toolkit, is integrated with PostgreSQL, a powerful and scalable relational database management system. Prisma simplifies database access by generating a type-safe and auto-completed query builder based on the database schema. It offers seamless integration with Express.js, making data retrieval, manipulation, and storage efficient and secure.

## Roadmap

- Project Setup

- User Authentication

- User Profiles

- Project Listings

- Project Creation and Management

- Messaging and Communication

- Payments and Escrow

- Rating and Reviews

- Unread Messages

- Admin Dashboard


## Documentation

[NextJS](https://nextjs.org/docs)
[Express.JS](https://expressjs.com/)
[TailwindCSS](https://tailwindcss.com/)
[Prisma]( https://www.prisma.io/)
[Stripe](https://stripe.com/docs/payments/quickstart)


## Installation

Install my-project with npm

```bash
  npx create-next-app@latest
  npm install express
  npm install @prisma/client
```
    
## Running Tests

To run tests, run the following command

```bash
  client: npm run dev
  Server: npm run dev
  Prisma: npx prisma studio
```


## Technology

- NextJS

- TailwindCSS

- Express.JS

- Prisma

- PostgreSQL

- Stripe
## Features

- User registration and authentication
- Profile creation and management for freelancers and clients
- Gigs creation, management and bidding
- Edit Gigs from seller side
- Search functionality for finding freelancers and projects
- Secure payment processing using Stripe
- Real-time messaging between freelancers and clients with read and unread features
- Reviews and ratings for freelancers
- Notifications for project updates
- Project milestones and progress tracking

## Screenshot

- Home Page
  
![Screenshot (88)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/520d7430-9f3e-4511-a154-b8f3e944d085)

- Login and Signup functionality
  
![Screenshot (89)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/ff6fbd02-a34d-49fd-83bf-7aec66718b1a)

- Set User Profile
  
![Screenshot (90)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/f8e42726-24e9-429d-8da0-1805fec83a4b)

- Create Gigs
  
![Screenshot (92)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/e9428f25-22cd-44aa-828c-769aae58260a)

- Edit Gigs
  
![Screenshot (94)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/de75eb12-1ea6-478f-adf5-35c01ad322cd)

- Search Gigs
  
![Screenshot (91)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/7268e288-8c0e-45b1-b8b8-b5a99fb0161f)

- About Gig and Seller
  
![Screenshot (96)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/d719523d-e254-4164-88b9-e6612ef20267)

- Secured Payment integration
  
![Screenshot (97)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/5f287354-924a-4fca-bb99-b6e516675269)

- Redirecting to success Page
  
![Screenshot (98)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/27dcc960-b794-4702-a712-2b9d0a811b09)

- User Purchase page
  
![Screenshot (93)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/80c279af-84c7-4221-9ca2-4970546c55d6)

- Client and freelancer Private Conversation with read and unread features
  
![Screenshot (103)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/c1024ec0-caaf-43b3-8b31-cf77271fb1db)

-  Reviews and Rating to Seller
  
![Screenshot (95)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/a927ecc5-2b6c-4f55-ac64-b86ba049ac72)

- Dashboard 
  
![Screenshot (104)](https://github.com/Sandarbha-K/fiverr-new-repo/assets/101709644/b978998c-ae59-4f13-8524-fd1702fb7552)



## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PORT` `PUBLIC_URL` `JWT_KEY` 
`DATABASE_URL` `stripe`







## Tech Stack

**Client:** Next.JS, Redux, TailwindCSS

**Server:** Node.JS, Express.JS 

**Database:** Prisma ,postgreSQL

**Payment:** Stripe


## Lessons Learned

Prisma integration with front-end

How to use prisma for authentication and authorization

How to use payment integration using stripe
