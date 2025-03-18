# Pharmacy Management System with AI Chatbot and QR Code Scanner
## 📖 Overview
This project is a Pharmacy Management System built using Streamlit, MySQL, and Google's Gemini AI. It includes features for both Customers and Managers, such as placing orders, viewing inventory, managing suppliers, and generating sales reports. Additionally, it integrates an AI Chatbot powered by Gemini AI for virtual assistance and a QR Code Scanner to retrieve medicine details.

The system supports multi-language functionality and includes features like email notifications for out-of-stock drugs, drug interaction warnings, and secure user authentication.

## 🚀 Features
### 1. User Authentication
- **Login/Signup**: Customers and Managers can log in or sign up securely.

- **Password Validation**: Ensures strong passwords with specific requirements.

- **Email Validation**: Validates email format during signup.
### 2. Customer Features
- **Place Orders**: Customers can place orders for medicines.

- **View Orders**: Customers can view their order history.

- **Drug Interaction Warnings**: Provides warnings for potential drug interactions using FDA API.
### 3. Manager Features
- **View Inventory**: Managers can check the current inventory status.

- **Manage Suppliers**: Add, update, or delete supplier information.

- **Sales Report**: View detailed sales reports.

- **Out-of-Stock Notifications**: Automatically sends email notifications to managers when drugs are out of stock.
### 4. AI Chatbot
- **Virtual Assistance**: Powered by Google's Gemini AI, the chatbot can answer user queries in real-time.

- **Multi-Language Support**: The chatbot supports multiple languages for better accessibility.
### 5. QR Code Scanner
- **Medicine Details**: Scan QR codes to retrieve detailed information about medicines.

- **Image Upload**: Users can upload QR code images for scanning.
### 6. Multi-Language Support
The application supports multiple languages, including English, Spanish, French, German, Chinese, Kannada, and Hindi.
### 7. Email Notifications
- **Out-of-Stock Alerts**: Managers receive email notifications when drugs are out of stock.

- **SMTP Integration**: Uses Gmail's SMTP server for sending emails.

## Technologies Used
- **Streamlit**: For building the web application interface.

- **MySQL**: For database management (stores user data, orders, inventory, etc.).

- **Google Gemini AI**: For the AI-powered chatbot.

- **Deep Translator**: For multi-language translation.

- **Pyzbar**: For QR code scanning.

- **Pillow (PIL)**: For image processing in QR code scanning.

- **SMTPLib**: For sending email notifications.

- **Pandas**: For data manipulation and display (e.g., sales reports, inventory).

##  🔧 Installation
### Prerequisites
- **Python 3.8+**: Ensure Python is installed on your system.

- **MySQL**: Install and set up a MySQL database.

- **Google Gemini API Key**: Obtain an API key from Google Gemini.

- **SMTP Credentials**: Set up an SMTP server (e.g., Gmail) for email notifications.

### Steps to Run the Application
#### 1.Clone the Repository:
```git clone https://github.com/your-username/pharmacy-management-system.git````
```cd pharmacy-management-system```
#### 2.Install Dependencies
#### 3.Set Up MySQL Database:
- Create a database named PharmacyManagement.

- Import the provided SQL schema (if available) to set up tables.
#### 4.Configure Environment Variables:
- Update the API_KEY in the code with your Google Gemini API key.

- Update the MySQL connection details (host, user, password, database) in the get_db_connection() function.

- Update the SMTP credentials (smtp_username, smtp_password) in the send_notification_email() function.

#### 5.Run the Application:
```streamlit run app.py```

#### 6.Access the Application:
Open your browser and navigate to http://localhost:8501.

## Contributing
Contributions are welcome! Please follow these steps:

- **Fork the repository.**

- **Create a new branch**:
```git checkout -b feature/YourFeatureName```

- **Commit your changes**:
```git commit -m 'Add some feature```

- **Push to the branch**:
```git push origin feature/YourFeatureName```

- **Open a pull request**.

## Contact
For any queries or feedback, feel free to reach out:

- **Name**: Shreyashwini

- **Email**: shreyashwinir@gmail.com

- **GitHub**:Shreyashwini-R





