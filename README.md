# Node.js Hospital API

A RESTful API for managing hospital data, built with Node.js, Express, and MongoDB.

## 📌 Features
- Patient record management
- Doctor and staff information
- Appointment scheduling
- Secure authentication and authorization
- Database integration with MongoDB

## 🛠️ Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project folder
cd nodejs-hospital-api-v1

# Install dependencies
npm install
```

## 🚀 Usage

```bash
# Start the server
npm start
```

## 📡 API Endpoints

| Method | Endpoint          | Description                  |
|--------|------------------|------------------------------|
| GET    | /patients        | Get all patients             |
| POST   | /patients        | Add a new patient            |
| GET    | /doctors         | Get all doctors              |
| POST   | /appointments    | Schedule a new appointment   |

## 📦 Dependencies

- dotenv (^16.4.7)  
- express (^4.21.2)  
- mongodb (^6.14.2)  
- morgan (^1.10.0)  

## 🛠️ Environment Variables

Create a `.env` file and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## 🤝 Contribution
Feel free to fork this project and submit pull requests.

## 📜 License
This project is licensed under the MIT License.
```

ده شامل كل التفاصيل المهمة زي **طريقة التثبيت، الاستخدام، الـ API Endpoints، والبيئة (Environment Variables)**.  
لو عايزة تضيفي حاجة أو تعدلي حاجة، قوليلي! 🚀😊
