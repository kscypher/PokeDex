# PokeDex - Fullstack Web & App Development

PokeDex is a dynamic platform designed for Pokémon card collectors to showcase, trade, buy, sell, and auction cards globally. Users can share their Pokémon cards, chat with other enthusiasts, and participate in exciting features like auctions, trades, and card scanning.

The PokeDex platform is a **full-stack solution** with both a **web application** and **mobile app**. This project allows users to collect all Pokémon cards and achieve the prestigious title of **Saints**.

## Key Features

### **Web Application** (Front-End & Back-End)

* **Sign Up / Login**: Users can create an account and sign in to access their profile and collections.
* **Pokémon Card Scanning**: Using webcam technology, users can scan their physical Pokémon cards and upload them to their profile.
* **Auction House**: Join live auctions to bid on rare and exclusive Pokémon cards.
* **Trade / Buy / Sell**: Users can engage in trading, buying, and selling Pokémon cards within the platform.
* **Saints**: Users who collect all available Pokémon cards are honored with the title of **Saint**.
* **Global Community**: Chat with other Pokémon collectors, share stories, and discuss card collection strategies.

### **Mobile Application** (iOS/Android)

* A mobile version of PokeDex (future release) will allow users to:

  * Access their profiles and card collections on the go.
  * Participate in auctions, trades, and buying/selling of cards via mobile.
  * Scan Pokémon cards using the phone's camera.
  * Chat with other users in real-time.
  * Keep track of their progress in the race to become a Saint.

---

## Technologies Used

### **Front-End** (Web)

* **HTML/CSS/JavaScript**: For building the user interface and interactive features.
* **React** (Optional for future updates): A JavaScript library for building user interfaces with reusable components.
* **WebRTC** (for Webcam Integration): Allows webcam access to scan physical Pokémon cards.

### **Back-End** (Web)

* **Node.js**: JavaScript runtime for server-side development.
* **Express.js**: Web framework for handling HTTP requests and building RESTful APIs.
* **MongoDB** (or SQL-based DB): Database for storing user profiles, card collections, trades, auction data, and more.
* **JWT Authentication**: Used for secure user login and session management.
* **WebSockets** (Optional): Real-time communication for chat functionality and live auctions.

### **Mobile Application** (iOS/Android)

* **React Native**: Framework for building native mobile applications using JavaScript.
* **Expo**: For simplifying the development and deployment of React Native apps.
* **Firebase** (for Authentication & Database, optional): Provides easy-to-use real-time database and authentication services for mobile.

---

## Features in Detail

### 1. **Sign Up & Login**

* **Web**: Users can sign up and log in using their email address and password. Authentication is managed using JWT (JSON Web Tokens).
* **Mobile**: The mobile app will provide the same functionality with secure authentication via Firebase or another secure authentication method.

### 2. **Card Scanning & Sharing**

* **Web**: Users can use their webcam to scan their physical Pokémon cards, which are then uploaded to their profile for display.
* **Mobile**: The mobile app allows users to scan cards using their phone’s camera and instantly add them to their collection.

### 3. **Auction House**

* **Web**: Users can participate in live auctions where they can bid on rare cards. The auction data is handled in real-time using WebSockets for seamless interactions.
* **Mobile**: The mobile app will feature live auctions that update in real-time, allowing users to place bids directly from their devices.

### 4. **Trade, Buy & Sell**

* Users can list cards for sale, request trades with other users, and negotiate deals.
* **Web**: The marketplace feature allows users to easily find and trade cards.
* **Mobile**: The app will offer the same marketplace features for mobile users.

### 5. **Saints**

* The users who manage to collect all available Pokémon cards will receive the prestigious title of **Saint**.
* This achievement will be recognized across both web and mobile platforms.

### 6. **Chat & Community**

* **Web**: Built-in chat functionality allows users to connect with other Pokémon enthusiasts.
* **Mobile**: Mobile users can chat in real-time, share tips, and engage in conversations with other collectors.

---

## How to Run the Web Application (Local Development)

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/pokedex.git
   cd pokedex
   ```

2. **Set Up the Backend**:

   * Install necessary dependencies for the backend server:

   ```bash
   cd backend
   npm install
   ```

3. **Start the Backend Server**:

   ```bash
   npm start
   ```

4. **Set Up the Frontend**:

   * Install necessary dependencies for the frontend:

   ```bash
   cd frontend
   npm install
   ```

5. **Start the Frontend Server**:

   ```bash
   npm start
   ```

   * The app will now be running on `http://localhost:3000`.

6. **Access the Web App**:

   * Open your browser and navigate to `http://localhost:3000` to view the app.
   * You can sign up, log in, scan cards, and interact with other users.

---

## How to Build & Run the Mobile App

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/pokedex.git
   cd pokedex
   ```

2. **Set Up the Mobile Development Environment**:

   * Install **Node.js**, **React Native CLI**, and **Expo**.
   * Follow the official [React Native Environment Setup](https://reactnative.dev/docs/environment-setup) for iOS/Android.

3. **Install Dependencies**:

   ```bash
   cd mobile
   npm install
   ```

4. **Run the App on a Simulator/Device**:

   ```bash
   npm start
   ```

   * This will launch the app in the Expo Go app on your device or in the iOS/Android emulator.

---

## Contributing

We welcome contributions to the PokeDex project! Whether it's adding new features, improving the user interface, fixing bugs, or enhancing the back-end functionality, your input is appreciated.

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to your forked repository (`git push origin feature/your-feature`).
5. Create a pull request with a description of the changes.

---

## Future Development

* **Mobile App**: Full-featured mobile app for both iOS and Android (React Native).
* **Real-Time Auctions**: Enhance auction features to include real-time bidding, timers, and notifications.
* **Card Scanning Enhancements**: Add advanced features to card scanning, including automatic recognition and categorization.
* **Backend Services**: Integration with a more robust back-end using real-time databases (Firebase) or other back-end services to support scaling.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or collaboration inquiries, feel free to reach out:

**Konduru Sri Ankith**
\sriankith.k@gmail.com
\[[https://www.linkedin.com/in/sri-ankith-konduru-010280221/]]

---

### Happy Collecting and Trading! 🃏

*** WARNING ***

It's still in development phase.
---
