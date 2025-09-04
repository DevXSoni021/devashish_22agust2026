

**A sleek and modern international payment system designed for banks.**

 Payments Portal empowers customers to securely log in, register, and make international payments using the SWIFT method. This system prioritizes data security and integrity with robust encryption and validation.

## 👥 Team


## ✨ Features

* **Secure Authentication:** User registration and login with robust password hashing.
* **International Payments:** SWIFT-based payments with support for various currencies.
* **Responsive UI:** Sleek and professional design built with React and Material UI.
* **Real-time Processing:** Integrated system for secure payment data storage.
* **Employee Dashboard:**  Admin panel for payment verification and management.

**Note:** Other payment methods (Mastercard, PayPal, EFT) are currently unavailable in this release, with SWIFT as the primary method.  



## 🚀 Quick Start

1. **Clone the Repository:**

```bash
git https://github.com/soni0021/payment_portal.git
cd globalPaymentsPlatform
```

2. **Install Dependencies:**

Navigate to the frontend folder and install the dependencies:

```bash
cd frontend && npm install
cd ../backend && npm install
```

3. **Run the App:**

   * **Frontend:**  
    ```bash
     cd globalPaymentsPlatform/frontend
     npm start
     ```
     The React app will now run at http://localhost:3000/.  
   * **Backend:**  
    ```bash
     cd ../backend
     npm run dev
     ```
     The backend API will run at http://localhost:5000/.  

## 🤔 How It Works


### Customer Workflow

* **Dashboard:** View and manage your payments.
* **Add Payment:** Enter payment details, including amount, currency, and SWIFT information.
* **Payment Confirmation:** Review and confirm your payment.

### Employee Workflow

* **Dashboard:** View all payments made by users.
* **Verify Payments:** Confirm legitimate payments and mark them as "verified."
* **Revert Payments:** Revert payments to "pending" status if needed.

## 💻 Tech Stack

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Material UI](https://img.shields.io/badge/Material%20UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)](https://mui.com/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/en)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA9B0?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

* **Validation:** Regex
* **Security:** bcrypt, JWT, Nodemon (for development)

## 📂 Project Structure
```bash
├── globalPaymentsPlatform
│   ├── backend               # Node.js/Express backend
│   │   ├── db                
│   │   ├── keys              # Private and public keys for the SSL Certificates
│   │   ├── middleWare
│   │   ├── models            # Data models (for storing users, payments)
│   │   └── routes            # API routes (login, register, payment)
│   └── frontend              # Node.js frontend
│       ├── public            # Public assets like index.html
│       └── src               # React components and assets
└── README.md                 # Project documentation
```

