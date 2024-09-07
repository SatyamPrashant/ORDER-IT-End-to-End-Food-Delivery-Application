# WSA MERN Stack Internship Project

## Overview
This project was developed by me during my internship at Web Stack Academy. This is an end-to-end Food Ordering Web Application built using MERN Stack.

## YouTube Tutorial
Watch my [detailed demonstration on YouTube](https://youtu.be/aiyqyTXEroE?si=LBdNQl4w0E9-GPzC) to get started and learn how to use all the features in the application.

## Key Features
- **Interactive User Interface:** Users can navigate restaurants, add items to cart, sort restaurants according to ratings and reviews and see thier order history.
- **User Registeration and Authentication:** New users can register. Once registered, they can login through their credentials, update their profile and can reset their password if they forget it.
- **Integrated Payment Gateway:** Once orders are placed, the user can checkoout to the payment gateway and can complete their payment by entering their credit card and other details.

## Technology Stack
- **ReactJS:** Creates a user friendly frontend interface, client-side.
- **Node.js:** runtime environment, communicates b/w server and client.
- **Express.js:** web framework to manage the application's data.
- **MongoDB:** stores the database using NoSQL using json files.

## Setup and Installation

### Prerequisites
- Visual Studio Code Installed
- Node.js, React.js, MongoDB installed.
- Signed in to Cloudinary, Mailtrap and Stripe accounts and generated API keys.

### Installation Steps
1. **Clone the Repository:**
   ```cmd
   git clone https://github.com/SatyamPrashant/Order-It-WSA-MERN-Stack-Internship-Project.git

2. **Open the Cloned Folder in Visual Studio Code:**
   
   Navigate to the frontend and backend folder in the project.

4. **Install the Required Libraries and Dependencies:**
   ```
   npm install
   //run this command in both frontend and backend folders.

4. **Connect Database to MongoDB:**

   Inside your project directory, navigate to config.env file, copy the URI and paste it into your MongoDB compass application. Then navigate to the database folder and import the required json files.

6. **Update config.env File:**

   Update your config.env file by entering your cloudinary API keys, Mailtrap Credentials and Stripe API keys

9. **Run the Application**
   ```
   npm start
   //First run this command in your backend folder and then in your frontend folder.
   // The application will get hosted on your local system.
