# ZCoder

ZCODER is an online coding platform designed to help developers improve their problem-solving skills through a wide variety of coding challenges, competitions, and interactive learning. Whether you're a beginner looking to learn the basics or an experienced developer sharpening your algorithmic skills, ZCODER provides the perfect environment to practice, learn, and grow.

Our platform features a vast collection of problems across multiple difficulty levels, from basic syntax challenges to advanced algorithms and data structures. The goal is to help you prepare for technical interviews, improve your problem-solving techniques, and track your progress over time.

## Run Locally
### First clone the repo
```bash
git clone https://github.com/praneethgarre/zcoder_.git
cd ZCoder
```

### Run backend
```bash
cd backend
npm i 
nodemon index.js or node index.js
```

Create a `.env` file in the backend folder with the following variables:
```
MONGODB_URI=mongodb://localhost:27017/zcoder
PORT=3000
JWT_SECRET=your_jwt_secret_key
(above jwt key can be found in terminal by this command < node -e "console.log(require('crypto').randomBytes(64).toString('hex'))">)
```

### Run frontend
Then open a new terminal and
```bash
cd frontend
npm i
npm run dev (o+enter to run on chrome)
```
Create a `.env` file in the frontend folder with the following variables:
```
VITE_API_URL = https://alfa-leetcode-api.onrender.com
VITE_BACKEND_URL = http://localhost:3000
VITE_JUDGE = https://emkc.org/api/v2/piston/execute
```

Then visit http://localhost:5173/


