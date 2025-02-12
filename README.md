

# **Omegle Clone**  

A real-time random chat and video call web application, similar to Omegle, allowing users to connect with strangers.
The project is built using **Node.js, Express.js, MongoDB, and Socket.IO**, enabling seamless text and video communication.  

## **Table of Contents**  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Project Structure](#project-structure)  
- [Installation](#installation)  
- [Environment Variables](#environment-variables)  
- [Running the Project](#running-the-project)  
- [Usage](#usage)  
- [Screenshots](#screenshots)  
- [Contributing](#contributing)  
- [License](#license)  

---

## **Features**  
✅ Random text chat with strangers  
✅ Video calling feature  
✅ Secure authentication using **bcryptjs**  
✅ Real-time messaging with **Socket.IO**  
✅ User sessions and data stored in **MongoDB**  
✅ Responsive UI built with **Tailwind CSS**  

---

## **Technologies Used**  

| Technology  | Description  |
|-------------|-------------|
| **Node.js**  | JavaScript runtime for backend  |
| **Express.js**  | Web framework for Node.js  |
| **MongoDB**  | NoSQL database for storing user sessions  |
| **Socket.IO**  | Enables real-time communication between users  |
| **bcryptjs**  | Password hashing for authentication  |
| **Tailwind CSS**  | Styling for UI components  |
| **EJS**  | Templating engine for rendering views  |

---

## **Project Structure**  

```
omegle-clone/
│── public/                  # Static assets (CSS, JS, images)
│── views/                   # EJS template files for frontend
│── routes/                  # Express routes for handling API calls
│── models/                  # Mongoose models (User schema, messages, etc.)
│── config/                  # Configuration files (MongoDB connection, etc.)
│── server.js                # Main server file (entry point)
│── package.json             # Dependencies and scripts
│── .env                     # Environment variables (ignored in Git)
│── README.md                # Project documentation
```

---

## **Installation**  

### **Prerequisites**  
Ensure you have the following installed on your system:  
- [Node.js](https://nodejs.org/)  
- [MongoDB](https://www.mongodb.com/)  
- [Git](https://git-scm.com/)  

### **Clone the Repository**  
```bash
git clone https://github.com/Shreshtasingh/omegle-clone.git
```
```bash
cd omegle-clone
```

### **Install Dependencies**  
```bash
npm install
```

---

## **Environment Variables**  

Create a `.env` file in the root directory and add the following values:  
```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/omegleclone
SECRET_KEY=your_secret_key
```

> Replace `your_secret_key` with a strong random string.

---

## **Running the Project**  

### **Start MongoDB** (if not running already)  
```bash
mongod
```

### **Run the server**  
```bash
npm start
```

The server will start on `http://localhost:3000`

---

## **Usage**  
1. Open `http://localhost:3000` in your browser.  
2. Click **Start Chat** to get connected with a random stranger.  
3. If you allow camera access, you can start a **video call**.  
4. Enjoy chatting anonymously with others!

---

## **Contributing**  

Contributions are welcome! Follow these steps:  
1. **Fork** this repository.  
2. **Create** a new branch:  
   ```bash
   git checkout -b feature-name
   ```
3. **Make your changes** and commit:  
   ```bash
   git commit -m "Added new feature"
   ```
4. **Push** to your branch:  
   ```bash
   git push origin feature-name
   ```
5. **Open a Pull Request** and wait for approval.  

---

## **License**  

📜 This project is open-source and available under the **MIT License**.

![WhatsApp Image 2025-02-12 at 22 45 09_d0ad3468](https://github.com/user-attachments/assets/cb4ba153-158a-4908-a500-3f5f81333fb7)
![WhatsApp Image 2025-02-12 at 22 45 09_90ead167](https://github.com/user-attachments/assets/eed4addb-1de5-486c-aa58-842c93ce6157)
![WhatsApp Image 2025-02-12 at 22 45 09_ca02f6f4](https://github.com/user-attachments/assets/88e7c0cf-375b-4296-9af2-72afa960ab2e)
![WhatsApp Image 2025-02-12 at 22 45 09_9ec79cdc](https://github.com/user-attachments/assets/ee74b44b-d198-4ac5-b935-8615220f6f25)

