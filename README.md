 Simple Login System (HTML Only)

This project is a basic multi-page Login System developed using pure HTML as part of the FS Java Internship Assignment.

It demonstrates page navigation between common authentication screens without using CSS, JavaScript, or a backend — focusing on **HTML structure and flow.

 Project Structure

assignment2/
│
├── login.html        → Login Page
├── register.html     → Registration Page
├── forgot.html       → Forgot Password Page
├── reset.html        → Reset Password Page
└── dashboard.html    → Dashboard Page

 
 Pages Included

 Login Page (`index.html`)

* Accepts Username and Password
* Redirects to Dashboard on login
* Provides links to:

  * Registration Page
  * Forgot Password Page

 Registration Page (`register.html`)

* Collects:

  * Name
  * Email ID
  * Phone Number
  * Password & Confirm Password
* Redirects back to Login after registration.

 Forgot Password Page (`forgot.html`)

* User enters registered Email ID
* Redirects to Reset Password page.

 Reset Password Page (`reset.html`)

* Allows user to:

  * Enter New Password
  * Confirm Password
* Redirects back to Login page.

 Dashboard Page (`dashboard.html`)

* Displays Welcome message after login
* Includes Logout button
* Logout redirects to Login page.

 Navigation Flow

```
Login → Dashboard → Logout → Login

Register → Login

Forgot Password → Reset Password → Login



This project is intentionally built without styling or scripting to demonstrate **basic HTML form handling and page linking**.


 How to Run the Project Locally

1. Clone the repository:

```
git clone [https://github.com/your-username/fs-java-internship.git](https://github.com/PREE445/html-authentication-poc)
```

2. Move into the folder:

```
cd assignment2
```

3. Open `login.html` in any browser
   **OR** run using XAMPP:



---

 Git Workflow Used

```
git add .
git commit -m "Updated project"
git push
```


 Learning Outcome

Through this project, we understood:

* Creating multiple HTML pages
* Using `<form>` and `action` for navigation
* Structuring a small web application
* Managing code using Git & GitHub
* Version control workflow (Add → Commit → Push)


