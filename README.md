# 🍽️ Recipe Management WebApp

A web application for managing recipes in a restaurant environment. This app allows staff to create, read, update, and delete (CRUD) recipes while ensuring access is restricted to a specific restaurant location using Geolocation API.

## 📌 Features
- 🔄 **CRUD Operations** - Add, view, edit, and delete recipes.
- 📍 **Geolocation Restriction** - Only accessible within a predefined restaurant area.
- 🔒 **Secure Access** - Ensures only authorized staff within the restaurant premises can manage recipes.
- 📜 **User-friendly UI** - Simple and intuitive interface built with Vue.js.

## 🛠️ Technologies Used
- **Frontend:** Vue.js
- **Backend:** Node.js / Express (Optional, if required for API)
- **Database:** Firebase / MongoDB / MySQL (Choose based on preference)
- **Geolocation API** - Used to verify the user's location

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- npm or yarn

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/AutisticKao/recipe-management.git
   cd recipe-management
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Access the app at `http://localhost:5173`

### Environment Variables
Create a `.env` file in the root directory and add:
```sh
VITE_ALLOWED_LATITUDE=your_latitude
VITE_ALLOWED_LONGITUDE=your_longitude
VITE_ALLOWED_RADIUS=your_radius_in_meters
```

## 📍 Geolocation Restriction
The app uses the **Geolocation API** to check the user's location before granting access. If the user is outside the defined area, they will be denied access.



## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to improve.

## 📄 License
This project is licensed under the MIT License.

---

Made with ❤️ for restaurant efficiency! 🍽️

