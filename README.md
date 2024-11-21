# 🚀 Secrets API Integration with Express.js

Welcome to the **Secrets API Integration Project**! This sleek, modern web app allows you to explore API interactions (GET, POST, PUT, PATCH, DELETE) seamlessly. Built with **Node.js**, **Express.js**, and **Axios**, it’s perfect for learning how to integrate APIs with robust backend systems.

---

## 🌟 Features

- **Interactive Web Form:** Submit and test API routes effortlessly.  
- **Real-time Feedback:** See responses instantly in a visually appealing output area.  
- **Full CRUD Operations:** Perform **GET**, **POST**, **PUT**, **PATCH**, and **DELETE** operations on the Secrets API.  
- **Responsive Design:** Built with clean, modern aesthetics and user-friendly styling.  

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **HTTP Client:** Axios  
- **Frontend:** EJS templates with CSS for styling  
- **Secrets API:** Integration with [Secrets API](https://secrets-api.appbrewery.com)  

---

## 🎨 Application Preview

### 🖼️ Interface Overview:
1. **Input Form:** Fields for `id`, `secret`, and `score` to send data to the API.
2. **Route Buttons:** Action-specific buttons for CRUD operations (GET, POST, PUT, PATCH, DELETE).
3. **Response Area:** Displays API responses in real time.

---

## ⚙️ How to Run the Project

### 1️⃣ Prerequisites  
Ensure you have the following installed:
- **Node.js** (v14+ recommended)
- **npm** or **yarn**  

### 2️⃣ Setup Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/secrets-api-integration.git
   cd secrets-api-integration
   ```
2. Install dependencies:  
   ```bash
   npm install
   ```
3. Set your **Bearer Token**:  
   - Replace the `yourBearerToken` variable in `index.js` with your personal token from the Secrets API.  

4. Start the server:  
   ```bash
   npm start
   ```
5. Open your browser and navigate to:  
   ```bash
   http://localhost:3000
   ```

---

## 🧪 Using the Application  

1. **Enter Details:** Fill out the `id`, `secret`, and `score` fields as needed.  
2. **Choose an Operation:** Click the relevant button for the desired API route:  
   - 🟢 `GET` to retrieve a secret.  
   - 🔵 `POST` to add a new secret.  
   - 🟣 `PUT` to fully update an existing secret.  
   - 🟡 `PATCH` to partially update an existing secret.  
   - 🔴 `DELETE` to remove a secret.  
3. **View Results:** API responses will appear in the **Response Area** below the form.  

---

## 🖌️ Form Design  

The UI features:  
- **Clean typography:** Aesthetic and readable fonts.  
- **Dynamic buttons:** Hover effects for a modern feel.  
- **Responsive layout:** Adapts to different screen sizes.

---

## 📂 Project Structure  

```plaintext
📦 secrets-api-integration
 ┣ 📂 views
 ┃ ┗ 📜 index.ejs    # Main template with form and response area
 ┣ 📜 index.js       # Express.js server with API integration
 ┣ 📜 package.json   # Project dependencies and metadata
 ┗ 📜 README.md      # This file!
```

---

## 📢 API Reference

Check out the [Secrets API Documentation](https://secrets-api.appbrewery.com) for details on API endpoints, parameters, and responses.

---

## 🤝 Contributing  

Feel free to submit pull requests or issues to enhance the app. Let’s make this project even better together!  

---

## 💡 Learn More

- [Axios Documentation](https://axios-http.com/docs/intro)  
- [Express.js Documentation](https://expressjs.com/)  

---

🎉 **Enjoy using the Secrets API Integration app!** 🚀
