# Quiz Application

This is a **Java-based Quiz Application** that allows users to participate in a timed quiz with multiple-choice questions. The application consists of four main Java classes: `Login`, `Rules`, `Quiz`, and `Score`. It is designed with a graphical user interface (GUI) using the `Swing` framework.

---
## **Table of Contents**
1. [Features](#features)
2. [Project Structure](#project-structure)
3. [How to Run the Application](#how-to-run-the-application)
4. [Class Descriptions](#class-descriptions)
5. [Screenshots](#screenshots)
6. [Contributing](#contributing)
7. [License](#license)

---

## **Features**
- User-friendly GUI.
- Timed quiz with a countdown timer for each question.
- Multiple-choice questions with four options.
- Lifeline feature (50-50).
- Score calculation and display.
- Option to restart the quiz.

---

## **Project Structure**
The project follows the following structure:
```
quiz_application/
├── icon/
│   └── istockphoto-933914672-170667a.jpg
│   └── maxresdefault.jpg
│   └── th.jpeg
├── src/
│   └── quiz/
│       └── application/
│           ├── Login.java
│           ├── Rules.java
│           ├── Quiz.java
│           └── Score.java
```

---

## **How to Run the Application**
1. Ensure you have **Java Development Kit (JDK)** installed on your system.
2. Open the project in an **IDE** (such as IntelliJ IDEA or Eclipse) or compile the Java files using the terminal.
3. Navigate to the project directory and compile the files:
   ```
   javac Login.java Rules.java Quiz.java Score.java
   ```
4. Run the application:
   ```
   java quiz.application.Login
   ```

---

## **Class Descriptions**

### **1. Login.java**
This class displays the login screen where users can enter their UID to start the quiz. It has the following components:
- **TextField** for UID input.
- **Buttons** for "Rules" and "Back".
- Action listeners to handle button clicks.

### **2. Rules.java**
This class displays the rules of the quiz. It shows a set of instructions for the user before starting the quiz.
- **Start Button**: Proceeds to the `Quiz` class.
- **Back Button**: Returns to the `Login` screen.

### **3. Quiz.java**
This class contains the main quiz logic. It includes:
- **Questions and options array**.
- **Radio buttons** for answer selection.
- **Buttons** for "Next", "50-50 Lifeline", and "Submit".
- Timer logic to ensure each question is answered within 10 seconds.
- Score calculation based on correct answers.

### **4. Score.java**
This class displays the final score at the end of the quiz.
- **Thank you message** with the user's name.
- **Play Again button** to restart the quiz.

---

## **Screenshots**
Include screenshots of the application interface:
 **Login Screen**
   ![Screenshot 2025-01-08 120529](https://github.com/user-attachments/assets/37c3bee7-dd49-48ae-9bc2-4dad5b94a308)

**Quiz Screen**
![Screenshot 2025-01-08 120559](https://github.com/user-attachments/assets/d54cb3e6-a40c-43f7-8a81-e3891ce654ac)

---

## **Contributing**
If you would like to contribute to this project, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

---

## **License**
This project is licensed under the MIT License. You are free to use, modify, and distribute the project, provided you include the original license.

---
## Credits
- **Developer:** Bharat Bhushan
---
**Happy Coding!** 🎉

