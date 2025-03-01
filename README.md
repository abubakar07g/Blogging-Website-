Blogging Website - Full Stack Development

Overview
The Blogging Website is a full-stack web application designed to provide users with a platform to create, manage, and share blog posts. Built using modern web technologies, the application offers a seamless and intuitive experience for bloggers, allowing them to publish content with multimedia integration, interact with other users, and manage their profiles.

Key Features
•	User Authentication: Secure login and registration using Firebase Authentication with Google sign-in support.
•	Blog Creation: Users can create, edit, and publish blog posts with rich text and multimedia content (images).
•	Image Management: Images are stored and managed using Cloudinary, ensuring fast loading times and efficient storage.
•	Database: MongoDB is used for storing blog posts, user profiles, and comments, providing a scalable and flexible data structure.
•	Responsive Design: The frontend is built using React.js and Tailwind CSS, ensuring a modern and responsive user interface.
•	Deployment: The application is deployed using Vercel for the frontend and Render for the backend

Technologies Used

  Frontend
    •	React.js: For building a dynamic and interactive user interface.
    •	Tailwind CSS: For styling and responsive design.
    •	JavaScript (ES6+): For frontend logic and interactivity.
    
  Backend
    •	Node.js: For server-side logic.
    •	Express.js: For building RESTful APIs.
    •	MongoDB: For database management.
    •	Mongoose ODM: For MongoDB object modeling.
    
  Authentication & Image Management
    •	Firebase Authentication: For secure user login and registration.
    •	Cloudinary: For image storage and management.
    
  Deployment
    •	Vercel: For frontend deployment.
    •	Render: For backend deployment.

Project Structure
  The project is divided into two main parts:
    1.	Frontend: Contains the React.js application with components for user interface, blog creation, and user interaction.
    2.	Backend: Contains the Node.js server with Express.js for API endpoints, MongoDB for data storage, and Firebase for authentication.

Installation and Setup

  Prerequisites
    •	Node.js and npm installed on your machine.
    •	MongoDB Atlas account for database setup.
    •	Firebase project for authentication.
    •	Cloudinary account for image management.
    
Steps to Run the Project
  1.Clone the Repository:
        git clone https://github.com/your-username/blogging-website.git
        
  2.Install Dependencies:
    Navigate to the frontend and backend directories and install the required dependencies:
          cd frontend
          npm install
          cd ../backend
          npm install
          
  3.Set Up Environment Variables:
    Create a .env file in the backend directory and add the following variables:
        •	MONGO_URI=your_mongodb_connection_string
        •	FIREBASE_API_KEY=your_firebase_api_key
        •	CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
        •	CLOUDINARY_API_KEY=your_cloudinary_api_key
        •	CLOUDINARY_API_SECRET=your_cloudinary_api_secret
        
  4.Run the Backend Server:
    Navigate to the backend directory and start the server:
      npm start
      
  5.Run the Frontend Application:
    Navigate to the frontend directory and start the React application:
     npm run dev

  6.Access the Application:
    Open your browser and go to http://localhost:5173 to view the application.
    
Sample Screenshots
Here are some sample screenshots of the application:

1.Login Page:<br>
![image](https://github.com/user-attachments/assets/068dd7d6-c162-436f-a8d3-610e379c596e)

2.Sign up Page:<br>
![image](https://github.com/user-attachments/assets/b909e33e-155f-4e26-9ecf-771b6b3ea2c0)

3.Home Page:
![image](https://github.com/user-attachments/assets/c42918e7-3589-4a90-b7db-9e6449ef3413)

4.Write Page:
![image](https://github.com/user-attachments/assets/56212a35-ce5c-4be7-942e-23a8e0357d7e)

5.Preview Page:
![image](https://github.com/user-attachments/assets/2e2446e4-e6bb-4879-96bc-3bf2224d28d5)

6.Profile Page:

  ![image](https://github.com/user-attachments/assets/bde8c05c-a94a-40cb-987c-51a8f7d0c085)

7.Deatail Blog Page

![image](https://github.com/user-attachments/assets/f6a72acb-81ba-4c52-8e4a-9cde3005b403)



Working Application  Link:

		https://frontend-lime-nu.vercel.app/






