Blogging Website - Full Stack Development

Overview
The Blogging Website is a full-stack web application designed to provide users with a platform to create, manage, and share blog posts. Built using modern web technologies, the application offers a seamless and intuitive experience for bloggers, allowing them to publish content with multimedia integration, interact with other users, and manage their profiles.

Key Features<br>
•	User Authentication: Secure login and registration using Firebase Authentication with Google sign-in support.<br>
•	Blog Creation: Users can create, edit, and publish blog posts with rich text and multimedia content (images).<br>
•	Image Management: Images are stored and managed using Cloudinary, ensuring fast loading times and efficient storage.<br>
•	Database: MongoDB is used for storing blog posts, user profiles, and comments, providing a scalable and flexible data structure.<br>
•	Responsive Design: The frontend is built using React.js and Tailwind CSS, ensuring a modern and responsive user interface.<br>
•	Deployment: The application is deployed using Vercel for the frontend and Render for the backend<br>

Technologies Used

  Frontend<br>
    •	React.js: For building a dynamic and interactive user interface.<br>
    •	Tailwind CSS: For styling and responsive design.<br>
    •	JavaScript (ES6+): For frontend logic and interactivity.<br>
    
  Backend<br>
    •	Node.js: For server-side logic.<br>
    •	Express.js: For building RESTful APIs.<br>
    •	MongoDB: For database management.<br>
    •	Mongoose ODM: For MongoDB object modeling.<br>
    
  Authentication & Image Management<br>
    •	Firebase Authentication: For secure user login and registration.<br>
    •	Cloudinary: For image storage and management.<br>
    
  Deployment<br>
    •	Vercel: For frontend deployment.<br>
    •	Render: For backend deployment.<br>

Project Structure<br>
  The project is divided into two main parts:<br>
    1.	Frontend: Contains the React.js application with components for user interface, blog creation, and user interaction.<br>
    2.	Backend: Contains the Node.js server with Express.js for API endpoints, MongoDB for data storage, and Firebase for authentication.<br>

Installation and Setup

  Prerequisites<br>
    •	Node.js and npm installed on your machine.<br>
    •	MongoDB Atlas account for database setup.<br>
    •	Firebase project for authentication.<br>
    •	Cloudinary account for image management.<br>
    
Steps to Run the Project<br>
  1.Clone the Repository:<br>
        git clone https://github.com/your-username/blogging-website.git<br>
        
  2.Install Dependencies:<br>
    Navigate to the frontend and backend directories and install the required dependencies:<br>
          cd frontend
          npm install
          cd ../backend
          npm install
          
  3.Set Up Environment Variables:
    Create a .env file in the backend directory and add the following variables:<br>
        •	MONGO_URI=your_mongodb_connection_string<br>
        •	FIREBASE_API_KEY=your_firebase_api_key<br>
        •	CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name<br>
        •	CLOUDINARY_API_KEY=your_cloudinary_api_key<br>
        •	CLOUDINARY_API_SECRET=your_cloudinary_api_secret<br>
        
  4.Run the Backend Server:<br>
    Navigate to the backend directory and start the server:<br>
      npm start
      
  5.Run the Frontend Application:<br>
    Navigate to the frontend directory and start the React application:<br>
     npm run dev

  6.Access the Application:<br>
    Open your browser and go to http://localhost:5173 to view the application.<br>
    
Sample Screenshots<br>
Here are some sample screenshots of the application:<br>

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






