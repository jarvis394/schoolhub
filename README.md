# schoolhub 
place where your homework begins *xD*

---

# About

Created by a 15 years old student from Russia for helping each class and teacher to connect more easily.

Created on **`node`**, used **`express`** for handling everything in web, **`node-vk-api`** for VK bot and more and more libs.

Server database based on **Google Firebase** *(Realtime Database)*

> *Look package.json to find all libraries*

---

# Structure

**Server Database**
- users
  - **Date() as ID**
  - ...
- work
  - **Date() as ID**
    - header
    - text
    - option-1
      - settings
        - {"multi": *bool*}
      - text
    - option-2
      - settings
        - {"multi": *bool*}
      - text
    - image-url
    - settings
      - {"class": *num*, "letter": *char*, "lesson": *string*}
- materials
  - **Date() as ID**
    - image
    - text
    - settings
      - {"class": *num*, "letter": *char*, "lesson": *string*}