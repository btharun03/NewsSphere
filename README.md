<h1 align="center">
NewsSphere 🌐
</h1>

<h3 align="center">Your daily dose of global headlines.</h3>

<p align="center">
  NewsSphere is a dynamic news aggregator that delivers the latest news from around the world directly to you. With a clean, intuitive interface, you can explore news by category, country, or dive into a comprehensive global feed.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
</p>

---

## ✨ Key Features

* **📰 Top Headlines:** Stay updated with top stories across various categories like Business, Entertainment, Health, Science, Sports, and Technology.
* **🌍 Country-Specific News:** Get localized headlines from a wide range of countries.
* **🌐 All News Feed:** A comprehensive feed aggregating news from multiple reputable sources.
* **🎨 Dark & Light Mode:** Seamlessly switch between themes for a comfortable viewing experience.
* **📱 Responsive Design:** Enjoy a flawless experience on desktops, tablets, and mobile devices.

---

## 🛠️ Technologies Used

### Frontend

* **React:** A powerful JavaScript library for building user interfaces.
* **React Router:** For declarative routing within the application.
* **Tailwind CSS:** A utility-first CSS framework for rapid and custom UI development.
* **Vite:** A next-generation frontend tooling for a faster and leaner development experience.

### Backend

* **Node.js:** A JavaScript runtime for building scalable server-side applications.
* **Express:** A minimal and flexible Node.js web application framework.
* **Axios:** A promise-based HTTP client for making requests to the NewsAPI.
* **NewsAPI:** The external API providing the news data.
* **Vercel:** The platform for deploying the serverless backend.

---

## ⚙️ Setup and Installation

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js (v14 or higher)
* npm

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/btharun03/newssphere.git](https://github.com/btharun03/newssphere.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd newssphere
    ```

3.  **Install server dependencies:**
    ```bash
    cd server
    npm install
    ```

4.  **Create a `.env` file in the `server` directory and add your NewsAPI key:**
    ```
    API_KEY=your_news_api_key
    ```

5.  **Start the development server:**
    ```bash
    npm start
    ```

6.  **In a new terminal, navigate to the client directory:**
    ```bash
    cd ../client
    ```

7.  **Install client dependencies:**
    ```bash
    npm install
    ```

8.  **Start the client application:**
    ```bash
    npm run dev
    ```

---

## 📈 Future Enhancements

* **Search Functionality:** Implement a robust search feature to find articles based on keywords.
* **User Accounts:** Allow users to create accounts to save their favorite articles and customize their news feed.
* **More News Sources:** Integrate with other news APIs to provide a wider variety of news sources.
* **Social Sharing:** Add buttons to easily share articles on social media platforms.
* **Offline Support:** Implement service workers to cache articles for offline reading.

---
