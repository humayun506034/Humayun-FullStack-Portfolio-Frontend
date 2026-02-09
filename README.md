# Portfolio & Blog Website 📚

This project is a Personal Portfolio & Blog Website built using Next.js. It provides a platform to showcase your portfolio, blog posts, and manage them through an authenticated dashboard. The website allows users to explore various pages like home, projects, blogs, and contact, while also offering an admin panel for managing content such as blog posts, projects, and messages

[![Live Demo](https://img.shields.io/badge/Live_Demo-Available-green)](https://humayun506034.vercel.app/)

Live :

```
https://humayun506034.vercel.app/
```

# 🔹 Features

## 1️⃣ Public Pages (Accessible to All Users)

### Home Page (/):

- Displays an introduction with your name, bio, and
- profile picture.
- Showcases your skills using icons or skill bars.
- Highlights featured projects, either static or fetched from an API.
- Provides a resume download button.

### Projects Page (/projects):

- Lists all your projects with images, descriptions, and links.
- Clicking on a project opens a detailed page (/projects/[id]).

### Blog Page (/blog):

- Displays a list of blog posts fetched from an API or JSON file.
- Clicking on a blog opens a detailed blog page (/blog/[id]).
### Contact Page (/contact):

- Contains a contact form where users can send messages (name, email, and message).
- Messages are saved in local storage or a database

## 2️⃣ Dashboard (Only for Logged-in Users)
### Login (/dashboard):

- Uses Next Auth for social login.
- Only authenticated users can access the dashboard.
### Blog Management (/dashboard/blogs):

- Allows users to create, read, edit, or delete blog posts.
- Form with fields like title, content, image, and category.
### Project Management (/dashboard/projects):

- Allows users to perform CRUD (Create, Read, Update, Delete) operations on projects.
- Upload project image, title, live link, descriptions, etc.
### Message Management (/dashboard/messages):

- Displays all the messages submitted from the contact form.

## Tech Stack 💻

#  Project Setup Guide

![Project Stack](https://img.shields.io/badge/Full_Stack-Project-blueviolet)

## Technology Stack 🔧

**Frontend**  
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-blueviolet)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-blue)
![Ant Design](https://img.shields.io/badge/Ant_Design-%230072f6)

## Development Setup 🛠️

### Frontend Setup

## Installation 🛠️

1. Clone repository

```
Clone Repository : https://github.com/humayun506034/Humayun-FullStack-Portfolio-Frontend.git
```

2. cd Humayun-FullStack-Portfolio-Frontend

```
npm install
```

1. Create .env file

```
BACKEND_URL=<provide your BACKEND_URL link here>
NEXT_PUBLIC_BACKEND_URL<provide your BACKEND_URL link here>
```

4. Run Project

```
npm run dev
```

Developed with ❤️ by [Md. Humayun Kabir Sobuj]

Contact: devhumayun@gmail.com