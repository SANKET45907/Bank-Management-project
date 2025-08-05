
 🏦 💰Bank-Management -Project
 
✅ Summary of the Bank Employee CRUD Program

This program is a simple web-based Bank Management System focused on handling Employee Records using basic HTML and JavaScript.


📌 Core Features:

Add Employee: A form to enter employee details like name, email, phone, address, and salary.

View Employee List: Displays all employee records in a table fetched from a backend API

      (http://localhost:3000/api/employees).

Edit/Delete Buttons: UI buttons to edit or delete employee entries (logic placeholders included).

Basic Validation: Uses required fields to ensure form completeness.


🛠️ Tech Stack:

Frontend: HTML + Vanilla JavaScript

Backend (Expected): REST API (e.g., Node.js/Express on localhost)


🚀 Purpose:

Demonstrates CRUD operations (Create, Read, Update, Delete) in a banking context

Useful as a beginner-level project for learning web development and RESTful APIs


✅ Key Fixes Made:

Fixed typos in your script (featch → fetch, responce → response, etc.)

Corrected form structure and input labels (for="=empEmail" → for="empEmail")

Added missing logic for the editEmployee and deleteEmployee buttons (currently placeholders)

Improved formatting for better readability and future extension

3.Run the application
    
    python main.py


🧠 3. Types of Banks in India (as an example)

● Commercial Banks – SBI, HDFC, ICICI, etc.

● Co-operative Banks

● Regional Rural Banks (RRBs)

● Development Banks – NABARD, SIDBI

● central Bank – Reserve Bank of India





 ✅ Expected REST API (Mock Example)

  
    
    | Method |        URL           |     Description     |

    | ------ | -------------------- | ------------------- |

    | GET    | `/api/employees`     | Get all employees   |

    | GET    | `/api/employees/:id` | Get employee by ID  |

    | POST   | `/api/employees`     | Create new employee |

    | PUT    | `/api/employees/:id` | Update employee     |

    | DELETE | `/api/employees/:id` | Delete employee     |





🖼️Screenshots 

<img width="1194" height="619" alt="Screenshot 2025-08-02 183908" src="https://github.com/user-attachments/assets/fc650610-9661-4cc2-8870-eeaf22d797b7" />





📃 Fill Form 


<img width="1275" height="751" alt="Screenshot 2025-08-01 205549" src="https://github.com/user-attachments/assets/f998dc06-3519-458e-b12b-f0e28c3f29c8" />



✅ Setup Instructions

🛠️ 1. Backend Setup (Node.js + Express + JSON Server or Custom API)

Option A: Use json-server (quick mock API)

Install json-server globally (if not already):

     npm install -g json-server


2.Create a file db.json in your project directory:
   
    {
     "employees": []
    }


3.Run the server:

   json-server --watch db.json --port 3000


4.Now your API is available at:
 
 http://localhost:3000/employees

5.⚠️ Important: Your current code uses:

   const API_URL = "http://localhost:3000/api/employees";

Change it to:

   const API_URL = "http://localhost:3000/employees";


🌐 2. Frontend Setup

Create an HTML file (e.g., index.html) and paste your updated code into it.

Open the file in your browser:

Just double-click on the HTML file or run it with a local web server like Live Server in VS Code.


✅ Summary of Files



| File          | Purpose               |

| ------------- | --------------------- |

| `index.html`  | Frontend form & logic |

| `db.json`     | Stores employee data  |

| `json-server` | Acts as REST API      |


▶️ Final Step: Run the App
 
1. Start JSON Server:

    json-server --watch db.json --port 3000

2.Open index.html in your browser.

3.You can now add, update, delete, and view employees.


✍️Developer  Info

👩‍💻Sanket Aswale

👩‍💻Someshwar Hokarne 

👩‍💻Tanuja Dongare

👨‍💻 Pratik Shinde

👩‍💻 Jaywanta Kawale




    
