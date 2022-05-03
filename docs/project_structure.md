---
layout: default
title: Project Structure
nav_order: 3
---

# Project Structure

The JARS project structure is an opinionated one. This is because we want to remove the burden of such decisions from the developer's shoulders. Having said that, if you still want to change how the project is structured, it isn't very difficult to do.

The project structure is as follows:
{: .fs-6 .fw-300 }

```
JARS
 ├── assets
 ├── libs
 ├── services
 ├── native
 ├── web
 ├── App.js
 ├── app.json
 ├── package.json
 ├── paths.js
 └── README.md
 
```

Let's talk about some of the important folders:

- **assets:** As the name suggests, this is where we store assets for both Web and Native.
 
- **services:** This is where we store files that interact with backend APIs. This folder is at the root of the project structure because we expect both the Web and Mobile app to have the same backend API.

- **libs:** Developers using the JARS framework should use this folder to write libraries that could be used in web, native or even both.

- **web:** This folder contains all React components, business logic and utils that are needed to create the web application. 

- **native:** This folder contains all React Native components, business logic and utils that are needed to create the mobile applications. (iOS and Android)