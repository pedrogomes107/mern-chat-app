Tutorial: https://www.youtube.com/watch?v=HwCqsOis89

Install server packages:

### `npm install express dotenv cookie-parser bcryptjs mongoose socket.io jsonwebtoken`

Run Server:

### `npm run server`

Update Server Automatically:

### `npm install nodemon --save -dev`

Update package.json:

### `"main": "server.js"`

### `"scripts": {"server": "nodemon backend/server.js"}`

## Update/create the file .env with the lines:

PORT=5000

MONGO_DB_URI=mongodb+srv://pedromcgomes95:YBwAhbg3z4YPZBWz@cluster0.f8mqb.mongodb.net/chat-app-db?retryWrites=true&w=majority&appName=Cluster0

JWT_SECRET=+5kPiwytrP0i6ZUUTLZ0yFZCHQ3YGi3Xpm7MuR84Xqg=

NODE_ENV=development
