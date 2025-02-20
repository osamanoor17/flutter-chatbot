# Flutter Chatbot

A simple chatbot application built using **Flutter** for the frontend and **Flask (Python)** for the backend.

## Features
✅ User-friendly chat interface
✅ Rule-based chatbot responses
✅ Flask-powered API for chatbot logic
✅ Flutter integration with REST API
✅ Responsive UI

---



## Installation & Setup
### **1. Clone the Repository**
```sh
git clone https://github.com/osamanoor17/flutter-chatbot.git
cd flutter-chatbot
```

### **2. Backend Setup (Flask API)**
#### **Prerequisites**
- Python 3 installed
- Flask installed (`pip install flask flask-cors`)

#### **Run the Flask Server**
```sh
cd backend  # Navigate to the backend folder
python app.py  # Run the Flask server
```
The server should now be running on `http://localhost:5000`.

---

### **3. Frontend Setup (Flutter App)**
#### **Prerequisites**
- Flutter installed ([Flutter Setup Guide](https://flutter.dev/docs/get-started/install))
- Android Studio or VS Code

#### **Run the Flutter App**
```sh
cd flutter-chatbot  # Navigate to the project folder
flutter pub get  # Install dependencies
flutter run  # Run the app on an emulator or real device
```

---

## API Endpoints
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/chat`  | POST   | Sends a message and gets a bot response |

**Example Request:**
```json
{
  "message": "Hello"
}
```
**Example Response:**
```json
{
  "response": "Hi! How can I help you?"
}
```

---

## Folder Structure
```
flutter-chatbot/
├── backend/        # Flask API
│   ├── app.py      # Python server
│   ├── requirements.txt  # Dependencies
│
├── lib/            # Flutter App Code
│   ├── main.dart   # Entry point
│   ├── chat_screen.dart  # UI screens
│
├── pubspec.yaml    # Flutter dependencies
├── README.md       # Project documentation
```

---

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Added new feature"`)
4. Push the branch (`git push origin feature-name`)
5. Create a pull request

---

## License
This project is licensed under the MIT License.

---

## Contact
For any issues, feel free to open an issue in the repository or reach out at **mosamanoor17@gmail.com**.
