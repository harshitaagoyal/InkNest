InkNest:
InkNest is a full-stack blogging web application that allows users to create, read, like, comment on, and manage blogs. It supports user authentication, image uploads, and secure data handling with a clean UI and modern backend architecture.

Live Demo: https://inknest.onrender.com

Features:
User Authentication (Register / Login / Logout)
Create, Edit, Delete Blogs
Like & Dislike Blogs
Comment on Blogs
Image Upload with Cloudinary
User Profiles
Secure Sessions & Input Sanitization
Responsive UI

Tech Stack:
Frontend
EJS (Embedded JavaScript Templates)
Bootstrap
CSS
Backend
Node.js
Express.js
MongoDB & Mongoose
Passport.js (Authentication)
Cloud & Tools
MongoDB Atlas
Cloudinary (Image Storage)
Multer (File Uploads)
Render (Deployment)
Git & GitHub

Environment Variables:

Create a .env file in the root directory and add:

MONGODB_URL=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_api_secret

Installation & Setup (Local):

1. Clone the repository
   git clone https://github.com/harshitaagoyal/InkNest.git
2. Navigate to the project directory
   cd InkNest
3. Install dependencies
   npm install
4. Add environment variables (.env)
5. Start the server
   node app.js
6. Open browser at: http://localhost:7000

Author: Harshita Goyal
GitHub: https://github.com/harshitaagoyal
License: This project is licensed under the ISC License.


