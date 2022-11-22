# FindIt - A university-centric lost and found progressive web application

## Team Members

- Ahammed Jafar Saadique
- Mohammed Saheel A
- Manvi Khurana
- Ali Noori
- Rupinder Kaur

## Project Description

This is a web application where users can create an account using university email id and post items they have lost or found. The application will have a map view where users can see the location of the items posted by other users. Users can also search for items by category, location, and date. The application will also have a feature where users can report lost items to the university administration.

## Novelty in the Project

The application will be university-centric, which means that users will have to use their university email id to create an account. This will ensure that only students of the university can use the application. The application will also have a feature where users can report lost items to the university administration. This will help the university administration to keep track of the items that are lost on campus.

## Project Feasibility

The application will be built using NextJS and MongoDB. The application will be hosted on MongoDB. The application will be a progressive web application, which means that it will be available on all devices.

## Research Gap

There is no application that is university-centric and has a feature where users can report lost items to the university administration. It is not physically possible for the university administration to keep track of all the items that are lost on campus, and also for the students as the campus is huge.

## Expected Project Outcomes

- Help students to find their lost items
- Help the university administration to keep track of the items that are lost on campus
- One stop solution for all the lost and found items on campus

## Project Architecture

The project will be built using the MERN stack. The backend will be built using Node.js and Express.js. The frontend will be built using Nextjs. The database will be built using MongoDB. The application will be deployed on Vercel.

## Project Timeline

- Week 1: Project setup, database setup, and authentication
- Week 2: Map view, item posting, and item search
- Week 3: Item reporting, item filtering, and deployment

## Project Management

We will be using GitHub Projects to manage our project. We will have a project board for each sprint. Each sprint will have a set of issues that need to be completed. We will use the GitHub Projects Kanban board to track the progress of each issue. We will also use GitHub Issues to track bugs and feature requests.

## Project Website

Yet to be decided

## Data Flow Diagram

![Data Flow Diagram](./public/dfd.png)

## Data Model

### User

- name: String
- email: String
- password: String
- items: [ObjectId]
- reports: [ObjectId]

### Item

- name: String
- category: String
- description: String
- location: String
- date: Date
- image: String
- user: ObjectId

### Report

- item: ObjectId
- user: ObjectId

## Wireframes

### Login Page

![Login page](./public/page%201.jpg)

### Home page

![Home Page](./public/page%202.0.jpg)

### Home page when cursor over the option

![Home Page 2](./public/Page%202.1.jpg)

### Item Search

![Home Page 2](.public/page%203.0.jpg)
### Item Report

![Home Page 2](.public/page%203.1.jpg)



![Home Page 2](.public/page%204.jpg)

### Item Filter

![Home Page 2](.public/page%205.jpg)

## Project Schedule

### Week 1

- Project setup
- Database setup
- Authentication
- Map view
- Item posting
- Item search

### Week 2

- Item reporting
- Item filtering
- Deployment

### Week 3

- Deployment
- Project documentation
