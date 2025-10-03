# Smart Task Prioritizer ✅

Smart Task Prioritizer is a simple tool that helps you organize your tasks effortlessly. Just add your tasks, and the system automatically suggests a priority level (High, Medium, Low) based on keywords like ‘urgent’, ‘deadline’, or ‘tomorrow’. Stay focused and manage your work smarter with just a few clicks.

## ✨ Features

- **Smart Prioritization**: Automatically categorizes tasks into "Urgent & Important", "Important & Not Urgent", etc.
- **Simple Interface**: Clean UI to add and view your prioritized tasks.
- **NLP-Powered**: Uses two separate classification models (`Urgency` and `Importance`) to make decisions.
- **REST API**: A simple backend API to serve the ML model.

---

## ⚙️ Tech Stack

| Component           | Technology / Library                                       |
| ------------------- | ---------------------------------------------------------- |
| **Backend**         | Python, Flask / FastAPI                                    |
| **Machine Learning**| Scikit-learn, Pandas, NLTK                                 |
| **Frontend**        | HTML, CSS, JavaScript                                      |
| **Database**        | SQLite (optional, for persistence)                         |

---

## 📊 Project Workflow

The application follows a simple data flow from the user to the machine learning model and back.

![[WhatsApp Image 2025-10-03 at 20.47.00_c5efdc8d.jpg]]

## 🤝 Contributing
Contributions are welcome! Please feel free to fork the repository, make changes, and submit a pull request.