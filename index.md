# Da Grindz

View the [Da Grindz Github Organization](https://github.com/da-grindz)

## Table of contents

- [Overview](#overview)
- [Deployment](#deployment)
- [User Guide](#user-guide)
- [Developer Guide](#developer-guide)
- [Development History](#development-history)
- [Continuous Integration](#continuous-integration)
- [Team](#team)

---

## Overview

**Da Grindz** is a nutrition-focused web application designed for the students and staff of **UH Mānoa**. It combines local campus dining information with personalized meal planning and nutritional tracking to support healthier eating habits and more mindful food choices.

### Key Features

- Personalized meal recommendations based on allergies, dietary preferences, and nutritional goals.
- Real-time listings and map locations of on-campus food vendors.
- Calendar-based meal planning based on current and future menus.
- Nutritional intake tracking with progress suggestions.
- UH Mānoa-focused experience including local dishes, events, and promotions from vendors.

### Special Sauce: "Mood-Based Meal Matching"

After registration, users set their current **"grindz mood"** (e.g., *ono kine comfort food*, *grindz for gains*, *quick bento run*, *vegetarian vibes*, etc.). This affects:

- Meal suggestions from vendors
- Displayed nutritional goals
- UI themes and motivational quotes tied to that mood

Users can update their mood anytime, and it subtly personalizes how the app talks to them and what it shows.

### Technologies Used

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [React Bootstrap](https://react-bootstrap.github.io/)
- [PostgreSQL](https://www.postgresql.org/)
- Hosted on [GitHub](https://github.com/)
- [Vercel](https://vercel.com/home)

---

## Deployment

- Production App: [Da Grindz](https://da-grindz.vercel.app/)
- Hosted on **GitHub** with automatic deployments from `main` branch.

---

## User Guide

### Landing Page

- Welcome message
- Login / Register buttons
- Info about the purpose and benefits of the app
- Guide to getting started

<img width="400px" class="rounded p-4" src="../images/landingpage.png">  
<img width="400px" class="rounded p-4" src="../images/langingpage2.png">  
<img width="400px" class="rounded p-4" src="../images/langingpage3.png">  
<img width="400px" class="rounded p-4" src="../images/langingpage4.png">  

### Dashboard

Displays personalized data:
- Meal recommendations based on current "grindz mood"
- Nutritional overview (calories, macros)
- Quick links to planner, preferences, and vendor menus

<img width="400px" class="rounded p-4" src="../images/dashboardpage.png">  

### Vendors Page

- List of food vendors on campus
- Real-time open/close status
- Weekly menus with filters (e.g. vegetarian, gluten-free)
- Interactive campus map

<img width="400px" class="rounded p-4" src="../images/vendorlist.png">

### Preferences Setup

Users can set:
- Dietary restrictions (e.g. gluten-free, halal)
- Cuisine preferences (e.g. Japanese, Hawaiian, Korean)
- Macro goals (protein/carb/fat ratios)
- "Grindz Mood" – a personal filter that tailors recommendations

Allergies Page:

<img width="400px" class="rounded p-4" src="../images/allergiespage.png">

Grindz Mood Page:

<img width="400px" class="rounded p-4" src="../images/grindzmoodpage.png">

### Planner Tool

Drag-and-drop meal planning tool:
- See upcoming meals by vendor availability
- Generate shopping lists or macros per day
- Toggle by weekly view or macro goals

<img width="400px" class="rounded p-4" src="../images/plannerpage.png">

---

## Developer Guide

- **Stack**: Next.js (w/ TypeScript), React Bootstrap, PostgreSQL
- **Local Dev**:
  ```bash
  npm install
  npm run dev
  ```
- **Database**: PostgreSQL schema with Prisma ORM  
- **GitHub Flow**:
  - Must pass eslint tests and build before merge

---

## Community Feedback

To better understand the usability and effectiveness of our application, we conducted a test involving five community members. Each participant was asked to go on our website and provide feedback based on their experience. The goal was to gather suggestions for improvement from real users representing our target audience.

* "The website is user friendly and it’s helpful to see all of the food options that are offered on campus in one place. The map is also useful because it shows you where the campus dining options and vending machines are, as well as where meal points are accepted." - UHM Economics student
* "" - UHM CS student
* insert feedback here
* insert feedback here
* insert feedback here
* make as many or as little bullet points as you need

---

## Development History

The development process for Da Grindz conformed to [Issue Driven Project Management](https://courses.ics.hawaii.edu/ics314s25/modules/project-management/) practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

---

## Milestone 1 

[M1 Project](https://github.com/orgs/da-grindz/projects/9)

<details>
<summary>View Details</summary>
  
<h3>Milestone 1 Mockups</h3>

<h4>Landing Page</h4>
<img width="400px" class="rounded p-4" src="../images/landingpage.png">

<h4>Sign In</h4>
<img width="400px" class="rounded p-4" src="../images/sign-in.png">

<h4>Sign Up</h4>
<img width="400px" class="rounded p-4" src="../images/sign-up.png">

<h4>Dashboard</h4>
<img width="400px" class="rounded p-4" src="../images/dashboard.png">

<h4>Planner</h4>
<img width="400px" class="rounded p-4" src="../images/planner.png">

<h4>Preferences</h4>
<img width="400px" class="rounded p-4" src="../images/allergies.png">
<img width="400px" class="rounded p-4" src="../images/mood-descriptions-page.png">

</details>

---

## Milestone 2 

[M2 Project](https://github.com/orgs/da-grindz/projects/12)  
[Live Deployment on Vercel](https://da-grindz.vercel.app)

<details>
<summary>View Details</summary>

<h3>Here are the updated pages during M2.</h3>

<h4>Logo</h4>
<img width="400px" class="rounded p-4" src="../images/bone-apple-teeth.png">

<h4>Landing Page</h4>
<img width="400px" class="rounded p-4" src="../images/landingpage.png">

<h4>Sign In</h4>
<img width="400px" class="rounded p-4" src="../images/sign-in.png">

<h4>Sign Up</h4>
<img width="400px" class="rounded p-4" src="../images/sign-up.png">

<h4>Dashboard</h4>
<img width="400px" class="rounded p-4" src="../images/base-mood-dashboard.png">
<img width="400px" class="rounded p-4" src="../images/gainz-dashboard.png">
<img width="400px" class="rounded p-4" src="../images/quick-bento-dashboard.png">

<h4>Planner</h4>
<img width="400px" class="rounded p-4" src="../images/macros-planner.png">
<img width="400px" class="rounded p-4" src="../images/planner.png">

<h4>Preferences</h4>
<img width="400px" class="rounded p-4" src="../images/preferenceform.png">
<img width="400px" class="rounded p-4" src="../images/m2allergy.png">
<img width="400px" class="rounded p-4" src="../images/m2grindz-mood.png">

</details>

---

## Milestone 3

[M3 Project](https://github.com/orgs/da-grindz/projects/14)

<details>
<summary>View Details</summary>

<h3>Here are the updated pages during M3.</h3>

<h4>Landing</h4>
<img width="400px" class="rounded p-4" src="../images/homeM3.png">

<h4>Dashboard</h4>
<p>The dashboard received a visual update also offers a randomize feature for users who don't know what mood they want.</p>
<img width="400px" class="rounded p-4" src="../images/dashboardSugarRushM3.png">

<h4>School Map</h4>
<img width="400px" class="rounded p-4" src="../images/mapM3.png">

<h4>Admin</h4>
<img width="400px" class="rounded p-4" src="../images/adminPageM3.png">

<h4>Vendors</h4>
<img width="400px" class="rounded p-4" src="../images/vendorListM3.png">

<h4>Menu Item Forms</h4>
<img width="400px" class="rounded p-4" src="../images/addMenuItemM3.png">
<img width="400px" class="rounded p-4" src="../images/editMenuItemM3.png">

<h4>Grindz Mood</h4>
<img width="400px" class="rounded p-4" src="../images/grindzMoodM3.png">

<h4>Preference Editor</h4>
<img width="400px" class="rounded p-4" src="../images/preferencesEditorM3.png">

</details>

---

## Continuous Integration

[![ci-da-grindz](https://github.com/da-grindz/da-grindz/actions/workflows/ci.yml/badge.svg)](https://github.com/da-grindz/da-grindz/actions/workflows/ci.yml)

Da Grindz uses [GitHub Actions](https://docs.github.com/en/free-pro-team@latest/actions) to automatically run ESLint and TestCafe each time a commit is made to the default branch.  You can see the results of all recent "workflows" at [https://github.com/da-grindz/da-grindz/actions](https://github.com/da-grindz/da-grindz/actions).

The workflow definition file is quite simple and is located at
[.github/workflows/ci.yml](https://github.com/da-grindz/da-grindz/blob/main/.github/workflows/ci.yml).

## Team

Da Grindz is designed, implemented, and maintained by:

- [Cassie Huber](https://cassandrahuber.github.io)
- [Jyrum Bohol](https://jyrum.github.io/)
- [Mishalyn Mei Ilmeng](https://mishalyn-mei-ilmeng.github.io)
- [Shade Matsumoto](https://shadematsumoto.github.io)
- [Sydney Hashiro](https://sydhashiro.github.io/)
- [Kevin Lee](https://leek7.github.io)

[Team Contract](https://docs.google.com/document/d/12LfYoMfUt6g-FTpS0mE4qidgtV_ONNVfTD4JU-hROTo/edit?usp=sharing)
