# Harper Kikuchi
### Assignment 8 - Plate Scout
#### A Yelp-style restaurant search app!!

## Live URLs

- **Client:** https://platescout-harperkikuchi.vercel.app
- **Server:** https://platescout-harperkikuchi.onrender.com
- **Server health check:** https://platescout-harperkikuchi.onrender.com/api/health

## Local setup

1. Clone the repo
2. Copy `server/.env.example` to `server/.env` and fill in `MONGO_URI` + `JWT_SECRET`
3. From the root: `npm install` (client) and `cd server && npm install` (server)
4. Two terminals: `npm run dev` (root, client) + `npm run dev` (server)
5. Open http://localhost:5173

## What I learned during deployment

I learned a lot from this development. My background in creating web apps has mostly been styling in css. This project taught me so much more about what it truly means to develop a web app. The process of connecting a backend and a front end surprised me so much just due to it needing to be split into two separate entities. I would have never guessed although I am guessing there are ways to have it all within one service. For debugging setting everything up at the end server-wise took the longest. Early on I had typed a capital on something which was able to be read on a local machine but not through vercel, so I needed to find that error. As well as updating the vite env variable within SignupForm & LoginForm. I would give myself more time if I were to make this again in the future. Overall this has been such a fun project to work on!!