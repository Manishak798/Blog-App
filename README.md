# Blogify 📝

Blogify is a full-stack web application where users can perform CRUD (Create, Read, Update, Delete) operations on blog posts. It features authentication and authorization using JWT (JSON Web Tokens) for session management, built with Node.js, Express.js, MongoDB with Mongoose, and hosted on AWS. The app has a seamless UI and utilizes EJS (Embedded JavaScript) for templating.

## Features 🚀

- 🛡️ **User Authentication:** Sign up, sign in, and sign out functionality.
- 🔑 **Authorization:** Protected routes accessible only to authenticated users.
- ✏️ **Create, Read, Update, and Delete (CRUD) operations** on blog posts.
- 🍪 **Session Management:** JWT-based authentication with cookies for session management.
- 📂 **MongoDB Database:** Persistence using MongoDB with Mongoose ODM.
- 🖥️ **Responsive UI:** Seamless user interface for optimal user experience.
- 🌐 **Hosted on AWS:** Deployed and hosted on Amazon Web Services.

## Technologies Used

- Node.js
- Express.js
- MongoDB with Mongoose
- EJS (Embedded JavaScript)
- JSON Web Tokens (JWT) for authentication
- Cookies for session management
- AWS for hosting

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Blogify.git
```

2. Install dependencies:

```bash
cd BLOGAPP
npm install
```

3. Set up environment variables:

Create a `.env` file in the root directory and add the following:

```
PORT=8080
MONGODB_URI=mongodb://localhost:27017/blogify
SECRET_KEY=your_secret_key
```

Replace `your_secret_key` with your desired secret key for JWT token generation.

4. Start the server:

```bash
npm start
```

5. Visit `http://localhost:3000` in your web browser.

## Screenshots

![image](https://github.com/Manishak798/Blog-App/assets/90680330/5af8562f-a341-4484-b4cd-929b3e4844be)

![image](https://github.com/Manishak798/Blog-App/assets/90680330/858293b0-6ea5-475c-b4e4-9a7ccc484f72)


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.


