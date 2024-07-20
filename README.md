# About
Skyrockit is an advanced platform designed to help users manage and track their job applications. 
This project focused on the backend side and developing a robust MEN (MongoDB, Express.js, Node.js) stack application and demonstrates the implementation of essential CRUD operations.
This app incorporating features such as user authentication and embedding application data within user models using Mongoose with an aesthetic UI view.

![Screenshot 2024-07-19 at 11 00 46 PM](https://github.com/user-attachments/assets/e9d8c110-9360-4e18-9c1c-8fac757f5bf6)


# The Design

## ERD Diagram 
![Screenshot 2024-07-19 at 11 35 41 PM](https://github.com/user-attachments/assets/d7583fa5-1599-4bd6-9516-e043e7081c9c)

In the ERD (Entity Relationship Diagram), I have implement an embedded relationship model, where the job application data is directly incorporated into the user model.
This approach was intentional because it makes data retrieval much easier in the application. By embedding the application data within the user’s document, it can minimize the need for multiple database read operations. Since users are already logged in, their associated applications are embedded within their own user document.

## RESTful routing charts
![Screenshot 2024-07-19 at 11 40 03 PM](https://github.com/user-attachments/assets/e70199d3-6f58-4e60-9222-7479b05edbbb)


## Snap-Shots
![Screenshot 2024-07-19 at 11 45 23 PM](https://github.com/user-attachments/assets/04541c9c-2e2b-4d03-8867-01ce2aaf0b82)

![Screenshot 2024-07-19 at 11 46 44 PM](https://github.com/user-attachments/assets/4a36e2e6-ec0c-4ecb-bb3f-4ff6ac0f9b29)



## Tech Stack 
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=javascript,html,css,nodejs,expressjs,mongodb&perline=6" />
</a>
