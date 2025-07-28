# AryanXchange 

A full-stack trading application built with the MERN stack (MongoDB, Express.js, React, Node.js). This project simulates a financial exchange platform, featuring a robust REST API backend and a dynamic, component-based React frontend.

---

##  Table of Contents

- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [API Endpoints](#-api-endpoints)
- [Future Scope](#-future-scope)
- [License](#-license)
- [Contact](#-contact)

---

##  Features

- **Dynamic Frontend:** A responsive and interactive user interface built with **React.js**.
- **Component-Based Architecture:** Modular frontend structure with reusable components like `Navbar`, `Footer`, `Pricing`, etc., for maintainability.
- **RESTful Backend:** A powerful backend built with **Node.js** and **Express.js** to handle all business logic and data processing.
- **Database Management:** Utilizes **MongoDB** with **Mongoose** for defining clear data schemas (`name`, `qty`, `avg`, etc.) and models.
- **API Ready:** Currently uses dummy data for development but is architected to seamlessly integrate the **Zerodha API** for live data.
- **Error Handling:** Includes a custom `NotFound` page for a better user experience on invalid routes.

---

##  Technology Stack

- **Frontend:**
  - React.js
  - Bootstrap
- **Backend:**
  - Node.js
  - Express.js
- **Database:**
  - MongoDB
  - Mongoose
- **API Testing:**
  - Thunder Client (during development)

---

##  API Endpoints

The backend provides the following REST API endpoints. They were tested using **Thunder Client**.

| Method | Endpoint              | Description                      |
| :----- | :-------------------- | :------------------------------- |
| `POST` | `/api/auth/signup`    | Register a new user.             |
| `POST` | `/api/auth/login`     | Authenticate a user.             |
| `GET`  | `/api/products`       | Get a list of all products/stocks. |
| `GET`  | `/api/products/:id`   | Get details for a single product.  |
| `GET`  | `/api/pricing`        | Get pricing information.         |

---

##  Future Scope

- [ ] Integrate the official **Zerodha Kite Connect API** to fetch live data.
- [ ] Implement user authentication and authorization using JSON Web Tokens (JWT).
- [ ] Develop more detailed product/stock pages with charts and historical data.
- [ ] Enhance form validation on both client and server sides.
- [ ] Deploy the application to a cloud service like Vercel or Heroku.

---

##  License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 👨‍💻 Contact

Aryan - [your.email@example.com](mailto:your.email@example.com)

Project Link: [https://github.com/[your-username]/AryanXchange](https://github.com/[your-username]/AryanXchange)
