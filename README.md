# Education Hub: Full-Stack Learning Platform

A Django web application for discovering colleges, filtering them by stream and city, browsing food and sightseeing spots by city, and submitting reviews, with user registration and login. Built with Python, Django, SQLite, Bootstrap and JavaScript between March 2024 and June 2024.

> This is a **showcase repository**. The source code lives in a private repository. This page documents what the project does and how it is built. Happy to walk through the code on request.
>
> Student portfolio project. It is not affiliated with any real education portal, and all college, fee and rating data are sample data.

[LinkedIn](https://linkedin.com/in/ratnesh-pathak-087466279) | [Email](mailto:pathakratnesh03@gmail.com)

## Preview

![Education Hub dashboard](screenshots/dashboard-ui.jpg)

## What Is Implemented

| Area | Status |
| --- | --- |
| College listing and search by name, city, country, course and stream | Implemented |
| Filters by stream (Engineering, Management, Medical) and by city | Implemented |
| Add a college through a form | Implemented |
| Food and sightseeing places by city | Implemented |
| Review submission and display of the latest review | Implemented |
| Newsletter subscription (sends an email to the entered address) | Implemented |
| Registration, login with remember me, logout, password change, password reset by email | Implemented |
| Profile page with bio and avatar | Implemented |
| Django admin for colleges, food, reviews and profiles | Implemented |
| GitHub and Google login buttons | Present, but need your own OAuth keys to work |

## Tech Stack

- **Backend:** Python 3, Django 5.0
- **Database:** SQLite
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 4
- **Libraries:** Pillow, social-auth-app-django

## Limitations

- The data is sample data, not real college information.
- Some pages that write data (add college, review, subscribe) do not require login and have limited input validation, so treat it as a demo.
- Logout is a GET link, while Django 5 expects POST for logout.
- A `Course` model exists but has no views yet.
- It runs locally on Django's development server and is not hosted.

## Author

Ratnesh Pathak - M.Sc. Information Technology, AI / ML Engineer, Founder of Team Ignites

GitHub: [@RatneshPathak](https://github.com/RatneshPathak) | LinkedIn: [Ratnesh Pathak](https://linkedin.com/in/ratnesh-pathak-087466279) | Email: pathakratnesh03@gmail.com

(c) Ratnesh Pathak. All rights reserved. The text and images in this repository may not be reused without permission.
