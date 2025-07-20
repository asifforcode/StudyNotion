# StudyNotion

StudyNotion is a comprehensive ed-tech platform that enables instructors to create and publish courses while providing students with an interactive learning experience. The platform features secure user authentication, payment integration, course management, and a responsive user interface.

## Features

- **User Authentication**: Secure signup and login functionality for students and instructors
- **Course Management**: Create, edit, and manage courses with rich content
- **Payment Integration**: Secure payment processing for course purchases
- **Responsive Design**: Optimized for various devices and screen sizes
- **Contact Form**: Email functionality for user inquiries

## Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Payment Processing**: Razorpay
- **Email Service**: Nodemailer

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
   ```
   git clone https://github.com/asifforcode/StudyNotion.git
   ```

2. Install dependencies for both frontend and backend
   ```
   # Install backend dependencies
   cd server
   npm install

   # Install frontend dependencies
   cd ../
   npm install
   ```

3. Set up environment variables
   Create a `.env` file in the server directory with the following variables:
   ```
   MONGODB_URL=your_mongodb_connection_string
   MAIL_HOST=your_mail_host
   MAIL_USER=your_mail_username
   MAIL_PASS=your_mail_password
   JWT_SECRET=your_jwt_secret
   RAZORPAY_KEY=your_razorpay_key
   RAZORPAY_SECRET=your_razorpay_secret
   CLOUD_NAME=your_cloudinary_name
   API_KEY=your_cloudinary_api_key
   API_SECRET=your_cloudinary_api_secret
   PORT=4000
   ```

4. Start the development servers
   ```
   # Start backend server
   cd server
   npm run dev

   # Start frontend server
   cd ../
   npm run dev
   ```

## Project Structure

- `/src`: Frontend React application
- `/server`: Backend Express API
  - `/controllers`: Request handlers
  - `/models`: Database models
  - `/routes`: API routes
  - `/utils`: Utility functions
  - `/middlewares`: Custom middleware
  - `/mail`: Email templates

## License

This project is licensed under the MIT License.