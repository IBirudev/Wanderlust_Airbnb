# Wanderlust 🏡

**Wanderlust** is a full-stack web application inspired by Airbnb that allows users to explore, create, edit, and manage vacation rental listings. It focuses on an intuitive user interface, reusable templates, clean code architecture, and robust server-side validation.

## 🌐 Live Demo

[View Live Project](https://wonderlust1-9cs2.onrender.com/listings)

## ✨ Features

- **Explore Listings:** Browse vacation rental properties with images, descriptions, locations, and prices.
- **User Authentication:** Sign up, log in, and securely access user-specific functionality.
- **Create Listings:** Add new properties with relevant details and images.
- **Manage Listings:** Edit or delete listings created by users.
- **Reviews and Ratings:** Share feedback and ratings for listed properties.
- **Form Validation:** Validate user input on both the client and server sides.
- **Responsive UI:** Access the application across different screen sizes.
- **Error Handling:** Handle errors through structured middleware and meaningful feedback.
- **Interactive Maps:** Display property locations using map integration.

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript
- EJS Templates
- Bootstrap

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Authentication and Tools**
- Passport.js
- Express Session
- Git and GitHub
- Cloudinary for image storage, if configured

## 📂 Project Structure

```text
Wanderlust/
├── controllers/       # Application logic
├── init/              # Database initialization and sample data
├── models/            # Mongoose database models
├── public/            # CSS, JavaScript, and static assets
├── routes/            # Express application routes
├── utils/              # Utility functions and error classes
├── views/              # EJS templates
│   ├── includes/       # Reusable UI components
│   ├── layouts/        # Page layouts
│   ├── listings/       # Listing pages
│   └── users/          # Authentication pages
├── app.js              # Main application entry point
├── middleware.js       # Custom middleware
├── schema.js           # Validation schemas
├── cloudConfig.js      # Cloud storage configuration
├── package.json
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

- Node.js and npm
- MongoDB
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/IBirudev/Wanderlust_Airbnb.git
cd Wanderlust_Airbnb
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add the environment variables required by your configuration.

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MAP_TOKEN=your_map_api_token
```

Use the variable names expected by your actual application. Remove variables for services you do not use, and never commit real credentials to GitHub.

### 4. Start the Application

```bash
node app.js
```

If your project has a development script configured, you can also use:

```bash
npm run dev
```

Open your browser at:

`http://localhost:8080`

## 🔐 Security

- Keep credentials and API keys in environment variables.
- Add `.env` to `.gitignore`.
- Validate and sanitize user input.
- Protect routes that require authentication.
- Use secure session configuration in production.

## 🚀 Future Improvements

- Advanced search and filtering
- Wishlist functionality
- Booking and availability management
- Payment gateway integration
- Improved user profiles
- Enhanced mobile experience

## 👨‍💻 Author

**Birudev**

- GitHub: [@IBirudev](https://github.com/IBirudev)

## 📄 License

This project is intended for educational and portfolio purposes. Add a suitable open-source license if you plan to distribute or reuse the code publicly.
