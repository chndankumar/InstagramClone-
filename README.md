# MystaGrawm - Instagram Clone

## Overview
**MystaGrawm** is a simplified Instagram clone created as a learning project to understand web application development. It demonstrates the use of modern technologies and showcases essential features of a social media platform.

---

## Key Features
- **User Authentication**: Secure login and registration system.
- **Image Uploading**: Seamless upload and management of images.
- **Follower Tracking**: Ability to follow and unfollow users.
- **Engagement Features**: Supports comments and likes on posts.
- **CRUD Operations**: Comprehensive operations for managing user-generated content.

---

## Tech Stack
- **Backend**: Java, Spring Boot, Hibernate
- **Database**: MySQL
- **Tools**: Postman (API testing)
- **Other**: SQL for database queries and operations

---

## Project Highlights
- Developed core features of a social media platform, including user authentication, follower management, and post interactions (likes and comments).
- Implemented **CRUD operations** for efficient content management and image uploading.
- Integrated **MySQL** for scalable and efficient data storage and retrieval.
- Conducted thorough API testing using **Postman**, identifying and resolving potential vulnerabilities for a robust application.
- Gained hands-on experience with web application architecture and end-to-end development.

---

## Installation and Setup
### Prerequisites
- Java 17+
- MySQL
- Maven
- Postman (optional, for testing)

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mystagrawm.git
   cd mystagrawm


Here’s a README.md file for your MystaGrawm - Instagram Clone project:

markdown
Copy code
# MystaGrawm - Instagram Clone

## Overview
**MystaGrawm** is a simplified Instagram clone created as a learning project to understand web application development. It demonstrates the use of modern technologies and showcases essential features of a social media platform.

---

## Key Features
- **User Authentication**: Secure login and registration system.
- **Image Uploading**: Seamless upload and management of images.
- **Follower Tracking**: Ability to follow and unfollow users.
- **Engagement Features**: Supports comments and likes on posts.
- **CRUD Operations**: Comprehensive operations for managing user-generated content.

---

## Tech Stack
- **Backend**: Java, Spring Boot, Hibernate
- **Database**: MySQL
- **Tools**: Postman (API testing)
- **Other**: SQL for database queries and operations

---

## Project Highlights
- Developed core features of a social media platform, including user authentication, follower management, and post interactions (likes and comments).
- Implemented **CRUD operations** for efficient content management and image uploading.
- Integrated **MySQL** for scalable and efficient data storage and retrieval.
- Conducted thorough API testing using **Postman**, identifying and resolving potential vulnerabilities for a robust application.
- Gained hands-on experience with web application architecture and end-to-end development.

---

## Installation and Setup
### Prerequisites
- Java 17+
- MySQL
- Maven
- Postman (optional, for testing)

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mystagrawm.git
   cd mystagrawm
Configure the database:

Create a MySQL database named mystagrawm (or update application properties).
Update application.properties with your database credentials.
Build and run the project:

mvn clean install
mvn spring-boot:run

Access the application:

## API endpoints: 
- Use Postman or any other tool to test.
- Frontend: Currently not implemented (future improvement).

### API Endpoints
Authentication
- POST /api/register - User registration.
- POST /api/login - User login.

### Posts
- POST /api/posts - Upload a new image.
- GET /api/posts - Fetch all posts.
- GET /api/posts/{id} - Fetch a specific post.

### Comments
- POST /api/comments - Add a comment to a post.
- GET /api/comments/{postId} - Get comments for a post.
 
### Likes
- POST /api/likes - Like a post.
- DELETE /api/likes/{postId} - Unlike a post.

## Learning Outcomes
- Mastered the basics of Spring Boot for building RESTful APIs.
- Learned Hibernate for seamless integration with relational databases.
- Gained practical knowledge of CRUD operations and API development.
- Developed debugging and testing skills using Postman.
