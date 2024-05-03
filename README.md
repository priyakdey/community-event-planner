# Community Event Planner

## Table of Content

- [Problem Statement](#problem-statement)
- [Core Features](#core-features)
- [Technologies](#technologies)
- [Mockup Ideas](#mockup-ideas)
- [Development Phases](#development-phases)
- [Deployment](#deployment)
- [LICENSE](#license)

## Problem Statement

Local communities often lack a centralized platform where community members can
plan, organize, and attend events. An interactive platform could make it easier
for organizers to manage events and for participants to find and engage with
events near them.

## Core Features

1. **User Accounts**

   - **Registration/Login**: Users can register and log in to access
     personalized features.
   - **Profile Management**: Users can edit their profiles, including
     preferences and contact information.

2. **Event Management**

   - **Create Events**: Users can create events, setting details like title,
     description, location (virtual or physical), and time.
   - **Browse Events**: Users can view a list of upcoming events, filter them by
     categories or location, and search for specific events.
   - **Event Details**: Clicking on an event shows full details, including a map
     integration if it's a physical location.
   - **RSVP to Events**: Users can RSVP to events, and organizers can see a list
     of attendees.
   - **Update and Delete Events**: Event creators can update or delete events,
     with notifications sent to RSVP’d users if significant changes occur.

3. **Interactive Features**

   - **Commenting on Events**: Users can comment on events to ask questions or
     engage with other attendees and organizers.
   - **Notifications**: Users receive notifications about event updates,
     upcoming events they’ve RSVP’d to, and comments on threads they’re
     following.

4. **Admin Panel**
   - **User Management**: Admins can manage user accounts, including roles and
     statuses.
   - **Event Oversight**: Admins can moderate events, ensuring content is
     appropriate.

## Technologies

- **Frontend**: React.js for a dynamic and responsive UI.
- **Backend**: Go (Golang) for robust server-side logic.
- **Database**: MongoDB for storing user data, event details, comments, etc.,
  benefiting from its flexible schema for an evolving data structure.
- **API**: RESTful APIs to connect the frontend and backend.
- **Authentication**: JWT (JSON Web Tokens) for secure user authentication and
  authorization.

## Mockup Ideas

1. **Homepage**: Features a simple, clean design with a navigation bar, a search
   field, and a list of upcoming events.
2. **Event Detail Page**: Includes detailed information about the event, a
   comment section, and an RSVP button.
3. **User Profile Page**: Allows users to manage their information and view
   events they’re interested in or attending.
4. **Admin Dashboard**: Provides metrics on user activity, event statistics, and
   tools for managing users and events.

## Development Phases

1. **Phase 1: Setup and Basic Backend**

   - Setup basic Go server.
   - Implement MongoDB connection.
   - Create basic user authentication.

2. **Phase 2: Basic Frontend and API Integration**

   - Setup React application.
   - Develop components for displaying events.
   - Connect React to the Go backend via API.

3. **Phase 3: Advanced Features and Testing**
   - Add advanced features like commenting, notifications, and admin tools.
   - Perform thorough testing, focusing on security and performance.

## Deployment

- Use Docker containers for both the Go backend and the MongoDB database to
  simplify deployment and scaling.
- Consider deploying on a cloud platform like AWS or Heroku for accessibility
  and reliability.

**NOTE**: This is an education project for learning Full Stack developement. Not
for any use in production.

## LICENSE

All code under this repository under MIT License, a copy of which can found
[here](LICENSE).
