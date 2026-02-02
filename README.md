cd backend / frontedn 
npm install on both

create .env file backend
PORT=5000
MONGO_URI=mongodb://localhost:27017/ecommerce
JWT_ACCESS_SECRET=your_access_secret
JWT_REFRESH_SECRET=your_refresh_secret

CLIENT_URL=http://localhost:5173

EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password

create .env file frontend
VITE_API_URL=http://localhost:5000/e-com/api
VITE_AUTH_URL=http://localhost:5000/auth/api

run both of them

