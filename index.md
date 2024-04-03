# Ube-Dev

## Table of Contents
* [Voluntree Overview](#overview)
* [Goals](#goals)
* [Application Design](#application-design)
* [Developer Guide](#developer-guide)
  * [Continuous Integration](#continuous-integration)
  * [Installation](#installation)
* [Development History](#development-history)
* [Team](#team)

## Overview

1. Voluntree Proof Of Concept: [Voluntree](#) 

<img src="images/Logo.png">

### What Is Voluntree?

Voluntree is a volunteer management system that matches willing volunteers with nonprofits, and other organizations. Currently, there is no easy way for volunteers to find organizations that need their help. Voluntree aims to solve this problem by providing a platform for organizations to post their volunteer opportunities and for volunteers to find them. Voluntree is a web application that is accessible from any device with a web browser.

## Goals

Voluntree aims to provide the following features:
* Account Registration
* Volunteer Profile
* Organization Profile
* Volunteer Opportunities Posting
* Volunteer Opportunities Search
* Volunteer Opportunities committing
* Communication between Volunteers and Organizations
* Organization statistics

## User Guide
This section provides a walkthrough of the Voluntree web app including its user interface and its capabilities.

### Landing Page
The landing page is presented to users when they first visit the site. It provides a brief overview and purpose of the app. It encorages the user to sign-up, log-in, or explore the events page to get started.
![](./images/M5/Landing1.png)
![](./images/M5/Landing2.png)
![](./images/M5/Landing3.png)

### About Us Page
The about page shows the users what Voluntree's mission is, and how it can help their community. It provides contact information and a message form for users to reach out to the team.
![](./images/About-Mockup.png)
![](./images/M2-About2.png)

### Subscribe Page
The subscribe page promotes and encourages users to become a member and donate to the Voluntree.
![](./images/M5/SubscribePage1.png)
![](./images/M5/SubscribePage2.png)

### FAQ Page
Here, users can see any frequently asked questions, and get quick answers to better understand how the app and Voluntree operates.
![](./images/M4/FAQ.png)

### Find Events Page
Without needing to log in, users can freely browse available events. To join an event, users can click on the event card and click the "Commit" button. If not logged in, they will be prompted to log in or register. Events can be searched for by name, location, organization, or description. To maintain focus, search results are limited to 9 events  and uses pagination to navigate through the results.
![](./images/M3/FindEvent.png)
![](./images/M3/FindEventPagination.png)

### Event Page
After selecting an event, users are taken to the event page. Here, they can see event details, location, and organization. They can also see the event's description, date, and time. Users can also commit to the event and have a quick contact button to reach out to the organization.

![](./images/M4/eventPage.png)

### Register/Login Page
Users can then choose to sign in or sign up through the dropdown at the top right, or by clicking the Sign In or Register buttons on the landing page. 
![](./images/M3/SignIn.png)
![](./images/M3/Register.png)

### Home Page
After logging in, users will see the home page. They have access to a brief overview of their dashboard and stats. They can also see their upcoming events and a calendar of events. Easy access to the events page and user profile is also available.
![](./images/M3/Home.png)

### User Profile Page
Users can view and edit their profile. They can see their stats, committed events, and their organization if they have one. They can also edit their profile information and change their password.
![](./images/M3/UserProfile.png)

### Edit User Profile Page
Users can edit their profile information.

![](./images/M4/EditUserProfile.png)

### Create Orgainzation Page
Users can create an organization and fill out the necessary information to get started.

![](./images/M4/CreateOrganization.png)

### Dashboard Page Mockup
Users with organizations can go to the dashboard page for a detailed overview of their stats and performances. They can also see their upcoming events and a calendar of events. Easy access to the events page and organization profile is also available.
![](./images/M4/OrganizationDashboard.png)
![](./images/Dashboard2-Mockup.png)

### Add Event Page
Organizations can create new events which will show up on the Find Events Page for users to browse through.
![](./images/M3/AddEvent-Mockup.png)
![](./images/M3/AddEvent2-Mockup.png)
![](./images/M3/AddEvent3-Mockup.png)

## Developer Guide

### Continuous Integration

[![ci-Voluntree](https://github.com/Ube-Dev/Voluntree/actions/workflows/ci.yml/badge.svg)](https://github.com/Ube-Dev/Voluntree/actions/workflows/ci.yml)

The Voluntree uses GitHub Actions to automatically run ESLint and TestCafe each time a commit is made to the default branch. You can see the results of all recent “workflows” at https://github.com/Ube-Dev/Voluntree/actions.

### Installation

First, install Meteor.

Second, visit the [Voluntree](https://github.com/Ube-Dev/Voluntree) application GitHub page, and click the “Use this template” button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

Third, in your terminal cd into the Voluntree/app directory and install libraries with:

> $ meteor npm install

Fourth, run the system with:

> $ meteor npm run start

If all goes well, the application will appear at http://localhost:3000.

## Development History

The following describes the development process of our app:

### Milestone 1: Basic User Needs and Page Mockups
The goal of milestone 1 was to create a work flow for the app to identify its main features to solve the problem of matching volunteers with organizations. We focused on creating a mockup of the app’s UI and database.

Milestone 1 was managed using [Voluntree GitHub Project Board M1](https://github.com/orgs/Ube-Dev/projects/1/views/2)

<img src="images/M1.png" width="750px">

<hr />

### Milestone 2: Databases and Rendering
Further implementation of the databases of events and users were the forefront of this milestone. Being able to display default events and understanding how to create, update, and remove certain items in the collections allowed us to have a more functioning website.

Milestone 2 was managed using [Voluntree GitHub Project Board M2](https://github.com/orgs/Ube-Dev/projects/3)
![](./images/M2-ProjectBoard.png)

### Milestone 3: Event Commitment and Creation
The third milestone was focused on the ability for users to commit to events and for organizations to create events. Improvements to overall user experience and user interface were also made. Users can now view and edit profiles and committed events.

Milestone 3 was managed using [Voluntree GitHub Project Board M3](https://github.com/orgs/Ube-Dev/projects/5)
![](./images/M3/M3-ProjectBoard.png)

### Milestone 4: Organization Creation, UI improvements, and Bug Fixes
The fourth milestone was focused on the ability for users to create organizations and for organizations to view their dashboard. Improvements to overall user experience and user interface were also made.

Milestone 4 was managed using [Voluntree GitHub Project Board M4](https://github.com/orgs/Ube-Dev/projects/9/views/1)
![](./images/M4/M4ProjectBoard.png)

## Team
Volntree is designed and developed by:

|                                                                                                                     | Name        | Role                         | GitHub Handle   |
|---------------------------------------------------------------------------------------------------------------------|-------------|------------------------------|-----------------|
| <img src="https://github.com/thomasarivera.png" alt="Thomas" width="100" height="100" style="border-radius: 50%;">  | Thomas Rivera | Chief Solutions Architect    | @thomasarivera  |
| <img src="https://github.com/sierranmorales.png" alt="Sierra" width="100" height="100" style="border-radius: 50%;"> | Sierra Morales | UX Dev and Design Lead       | @sierranmorales |
| <img src="https://github.com/aldenparoni.png" alt="Alden" width="100" height="100" style="border-radius: 50%;">     | Alden Paroni | Development Lead             | @aldenparoni    |
| <img src="https://github.com/Jchen20-1.png" alt="Jiawen" width="100" height="100" style="border-radius: 50%;">      | Jiawen Chen | Database Lead                | @Jchen20-1      |
| <img src="https://github.com/jianleliu.png" alt="Jianle" width="100" height="100" style="border-radius: 50%;">      | Jianle Liu  | Integrations Lead            | @jianleliu      |
| <img src="https://github.com/hokwaichan.png" alt="Hokwai" width="100" height="100" style="border-radius: 50%;">     | HokWai Chan | Testing Lead                 | @hokwaichan     |
| <img src="https://github.com/ryanseng32.png" alt="Jianle" width="100" height="100" style="border-radius: 50%;">     | Ryan Seng   | Systems Reliability Engineer | @ryanseng32     |
| <img src="https://github.com/willjsimmons.png" alt="William" width="100" height="100" style="border-radius: 50%;">  | William Simmons | Scrum-Master                 | @willjsimmons   |

 
All members of this team have agreed to abide by the following [contract](https://docs.google.com/document/d/1Kxjdgpj1TOGy7MWezyQWSatDHok7aZ1TTr7NwqdHbww/edit?usp=sharing).

## Team Goals

- Work together as a team and contribute equitably.
- Design a user-friendly and intuitive applications.
- Create a thoughtful projects that help to bring people together.

## Meetings and Communication

The team meets biweekly at a minimum and official Communications are disseminated via project group's Discord server. The team also leverages Github projects as a means of organizing and assigning tasks.

## Contact

Please email [wjs7@hawaii.edu](wjs7@hawaii.edu) for any inquiries.

---
<!---------------------------------------------------------------------------->
