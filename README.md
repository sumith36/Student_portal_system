**##📰 Student Management System**

Student Management System is a web-based portal for managing student registrations, profiles, academic info, and fee status.
Built using HTML, CSS, and JavaScript, it provides a clean, responsive dashboard and interactive forms for students and admins.

**🚀 Features**

Student registration with auto-generated Student ID

Login system with password visibility toggle and strength checker

Dashboard displaying profile, academic info, and fee status

Form validation with real-time error messages

Loading spinner and toast notifications for better UX

Support section with contact details

**🧠 How It Works**

Frontend uses HTML, CSS, and JavaScript to create forms, dashboards, and dynamic sections.

Form validation is implemented using JavaScript regex for email, phone, and PIN code.

Password strength checking dynamically updates a progress bar based on character types (uppercase, lowercase, number, special character).

Student data is stored in a mock database (JavaScript object), simulating backend functionality.

On login, JavaScript checks credentials against the mock database and loads the appropriate dashboard view.

Dashboard sections (Profile, Academic Info, Fees, Support) are dynamically updated using JavaScript DOM manipulation.

**🛠️ Technologies Used**

Frontend: HTML5, CSS3, JavaScript(ES6+), AngularJS

IDE: Visual Studio Code

Deployment: GitHub pages

**🧩 API Endpoints**

POST /addStudent → Add a new student

GET /getStudents → Retrieve all student records

PUT /updateStudent/:id → Update an existing student record

DELETE /deleteStudent/:id → Delete a student record 

**💡 Challenges and Solutions**

Challenge1: Connecting AngularJS to SQL database Solution: Used a lightweight backend (Node.js or PHP) to handle SQL queries safely.

Challenge2: Data not updating instantly on UI Solution: Implemented $scope and $apply() to refresh data dynamically.

Challenge3: Form validation errors Solution: Used AngularJS directives like ng-model, ng-required, and real-time validation messages.
