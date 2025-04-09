# Da Grindz

## Table of contents

- [Overview](#overview)
- [Deployment](#deployment)
- [User Guide](#user-guide)
- [Community Feedback](#community-feedback)
- [Developer Guide](#developer-guide)
- [Development History](#development-history)
- [Continuous Integration](#continuous-integration)
- [Walkthrough Videos](#walkthrough-videos)
- [Example Enhancements](#example-enhancements)
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

- [Next.js](https://nextjs.org/) (Frontend + Backend Routing)
- [TypeScript](https://www.typescriptlang.org/)
- [React Bootstrap](https://react-bootstrap.github.io/)
- [PostgreSQL](https://www.postgresql.org/) for persistent data
- Hosted on [GitHub](https://github.com/)
- Custom APIs for menu ingestion or scraping (with permission from vendors)

---

## Deployment

- Production App: [In Progress...](#)
- Hosted on **GitHub** with automatic deployments from `main` branch.

---

## User Guide

### Landing Page

- Welcome message
- Login / Register buttons
- Info about the purpose and benefits of the app

### Dashboard

Displays personalized data:
- Meal recommendations based on current "grindz mood"
- Nutritional overview (calories, macros)
- Quick links to planner, preferences, and vendor menus

### Vendors Page

- List of food vendors on campus
- Real-time open/close status
- Weekly menus with filters (e.g. vegetarian, gluten-free)
- Interactive campus map

<img width="500px" src="../images/food-browser.png">

### Preferences Setup

Users can set:
- Dietary restrictions (e.g. gluten-free, halal)
- Cuisine preferences (e.g. Japanese, Hawaiian, Korean)
- Macro goals (protein/carb/fat ratios)
- "Grindz Mood" – a personal filter that tailors recommendations

### Planner Tool

Drag-and-drop meal planning tool:
- See upcoming meals by vendor availability
- Generate shopping lists or macros per day
- Toggle by weekly view or macro goals

---

## Community Feedback

We are interested in your experience using Da Grindz!  If you would like, please take a couple of minutes to fill out [Da Grindz Feedback Form (In Progress...)](#). It contains only five short questions and will help us understand how to improve the system.

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

## Development History

The development process for BowFolios conformed to [Issue Driven Project Management](https://courses.ics.hawaii.edu/ics314s25/modules/project-management/) practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

---

## Continuous Integration

![ci-badge](https://github.com/bowfolios/bowfolios/workflows/ci-bowfolios/badge.svg)

Bowfolios uses [GitHub Actions](https://docs.github.com/en/free-pro-team@latest/actions) to automatically run ESLint and TestCafe each time a commit is made to the default branch.  You can see the results of all recent "workflows" at [https://github.com/bowfolios/bowfolios/actions](https://github.com/bowfolios/bowfolios/actions).

The workflow definition file is quite simple and is located at
[.github/workflows/ci.yml](https://github.com/bowfolios/bowfolios/blob/main/.github/workflows/ci.yml).

---

## Walkthrough Videos

- [In Progress...](#)

---

## Example Enhancements

- 📱 Mobile PWA version
- 🍍 UH ID login integration
- 🧠 AI-powered meal generation based on nutritional gaps
- 📸 Vendor-sourced food pics
- 🛒 Marketplace for vendor coupons / student-run popups

---

## Team

Da Grindz is designed, implemented, and maintained by:

- [Cassie Huber](https://cassandrahuber.github.io)
- [Jyrum Bohol](https://jyrum.github.io/)
- [Mishalyn Mei Ilmeng](https://mishalyn-mei-ilmeng.github.io)
- [Shade Matsumoto](https://shadematsumoto.github.io)
- [Sydney Hashiro](https://sydhashiro.github.io/)
- [Kevin Lee](https://leek7.github.io)

[Team Contract](https://docs.google.com/document/d/12LfYoMfUt6g-FTpS0mE4qidgtV_ONNVfTD4JU-hROTo/edit?usp=sharing)
