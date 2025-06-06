# ZCoder

A interactive coding community platform to practise and scale up your skills.

## Run Locally
### First clone the repo
```bash
git clone https://github.com/vijay-kumar-79/ZCoder.git
cd ZCoder
```

### Run backend
```bash
cd backend
npm i 
nodemon index.js
```

### Run frontend
Then open a new terminal and
```bash
cd frontend
npm i
npm run dev
```

Also create a new file called `.env` in the frontend folder at the same level of src,public. The format for it is:
```
VITE_API_URL = https://alfa-leetcode-api.onrender.com
VITE_BACKEND_URL = http://localhost:3000
VITE_JUDGE = https://emkc.org/api/v2/piston/execute
```

Then visit http://localhost:5173/

# Zcoder
