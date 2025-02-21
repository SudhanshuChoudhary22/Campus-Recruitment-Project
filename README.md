𝐄𝐦𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭 𝐏𝐨𝐫𝐭𝐚𝐥
The project is built with a modern tech stack: Visual Studio Code for code editing, Node.js for server-side development, React.js for the client-side interface, MongoDB for database management, and Cloudinary for efficient resume uploads in JPEG and PNG formats.


𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧
1.	Open the project in Visual Studio Code.

2.	Open the terminal (Ctrl + ~).

3.	Backend Setup:	cd backend
										npm install
4.	Install Dependencies: npm install bcrypt cloudinary cookie-parser cors dotenv express express-fileupload jsonwebtoken mongoose validator





𝐑𝐮𝐧𝐧𝐢𝐧𝐠 𝐭𝐡𝐞 𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧
1.	Frontend:		cd frontend
								npm run dev
2.	Backend: 		cd backend
								node server.js




.𝐞𝐧𝐯 𝐅𝐢𝐥𝐞 𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐚𝐭𝐢𝐨𝐧
1. Create a .env file in the backend folder with: PORT=4000
CLOUDINARY_CLIENT_NAME=your_cloudinary_client_name
CLOUDINARY_CLIENT_API=your_cloudinary_client_api
CLOUDINARY_CLIENT_SECRET=your_cloudinary_client_secret
FRONTEND_URL=http://localhost:5173
MONGO_URI=mongodb://localhost:27017
JWT_SECRET_KEY=your_jwt_secret_key
JWT_EXPIRES=7d
COOKIE_EXPIRE=7d


𝐋𝐨𝐜𝐚𝐥𝐡𝐨𝐬𝐭 𝐒𝐞𝐭𝐮𝐩
Run ipconfig in Command Prompt to find your IPv4 address.
Set FRONTEND_URL in .env to http://localhost:5173.
