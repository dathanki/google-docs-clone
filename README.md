# Live Deployment

This project was deployed with [Netlify](https://hungry-poincare-4d208d.netlify.app/)

# Technologies used

- React
- React Router Dom
- Quill (handy library for implementing text editing capabilities)
- SocketIO (Real-time client-server communication)
- Nodemon (Real-time server refresh)
- MongoDB

# Notes
Having issues at the moment figuring out how to run my server in production. 

### In order to run this project locally, please follow these steps. 
1. Make sure [NPM](https://www.npmjs.com), [MongoDB](https://www.mongodb.com/try/download/community) are installed on the local machine

2. Download entire project and extract it to a folder somewhere

3. Open first terminal and navigate to client folder within project dir

4. Execute 'npm start' command (do not include the '' & don't close the terminal), this will load the SPA created by react

5. Open second terminal and navigate to server folder within project dir

6. Execute 'npm run devStart' command (do not include the ''), this will initiate the devmon server

7. Should be working now, duplicating the page will show simultaneous typing on both documents 
