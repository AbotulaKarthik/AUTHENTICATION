# Authentication

✨ Features <br>
✅ User Signup with email and password <br>
✅ Email Verification using OTP sent to the user's email <br>
✅ User Login with JWT-based authentication <br>
✅ Forgot Password functionality <br>
✅ Reset Password via OTP sent to registered email <br>
✅ Token-based protected routes <br>
✅ Responsive frontend using React <br>

🛠️ Technologies Used <br>
Frontend: React, Axios, React Router DOM, Tailwind CSS (optional) <br>
Backend: Node.js, Express.js, JWT, bcrypt, nodemailer <br>
Database: MongoDB (with Mongoose) <br>
Email Service: Nodemailer with SMTP or service provider like Gmail <br>

📁 Project Structure <br>
/client: React frontend <br>
/server: Node.js/Express backend with all authentication logic <br>

📧 Email Functionality <br>
On signup, an OTP is sent to the user’s email to verify their account. <br>
For password reset, another OTP is sent to initiate a secure reset process. <br>

🔒 Security Measures <br>
Passwords are hashed using bcrypt.  <br>
All sensitive routes are protected using JWT tokens. <br>
Email verification and OTP expiry checks are implemented. <br>
