<style>@import url("//readme.codeadam.ca/readme.css");</style>

## Pitch

Date: August 1, 2023  
Domain: [https://flow.brickmmo.com](https://flow.brickmmo.com)  
GitHub: https://github.com/codeadamca/flow  

### Application Purpose

This application will provide BrickMMO developers with a place to login and receive their daily tasks and deadlines. 

This application will intentionally be written in a simplified structure with a simple stack. 

Here are some rules for continued development:

- Languages will include HTML, minimal CSS, and vanilla PHP
- Validation is server-side and will simply simply not add the record if there is an error, it will not display specific errors, or provide a chance to fix errors
- No libraries, frameworks, or JavaScript
- Icons use simple HTML entities [https://www.toptal.com/designers/htmlarrows/symbols/](https://www.toptal.com/designers/htmlarrows/symbols/)

This will provide BrickMMO developers with a simple application to contribute to once they have some understanding of server-side languages such as PHP.

### Front-End

There will be no front-end for this application. All data will be behind a student and admin login. There will however be a GitHub repository to store full tasks descriptions in Markdown:

[https://github.com/BrickMMO/tasks](https://github.com/BrickMMO/tasks)

### Back-End

The backend will include a login area for students and one for admin:

#### Students

- Login to application (registration, login, forgot password)
- Dashboard
- Toggle between classes
- View existing tasks, details, and deadlines
- Mark tasks as complete
- Make notes for each task

![Flow Task List](../images/v1-screenshot-flow-tasks.png)

#### Admin

- Login to application (login, forgot password)
- Dashboard
- Manage classes, tasks, students, and notes
- Import users into classes, assign tasks

### API

This application will not require an API in version one.

| Method | Endpoint | Description |
| - | - | - |
|  |  |  |

[&#10132; Back to Version 1](/flow-about/v1)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
