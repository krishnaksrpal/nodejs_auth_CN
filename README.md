# Node Passport Authentication

This repo contains code for Local email-passport authentication and Google Authentication.

## 1. USAGE

### Install All Packages

```bash
npm install express ejs mongoose bcryptjs connect-flash cookie-parser express-session csurf memorystore passport passport-local passport-google-oauth20 nodemailer
```

### Install Nodemon For Development

```bash
npm install -D nodemon
```


✔ Add User Password reset
✔ Add Verify Account
✔ Add Email Sending Options
✔ Added Flash messages for errors
✔ Passwords are stored in encrypted format

NODEJS_AUTH
├── controller
| --- ├── accountRoutes.js
| --- ├── googleAuth.js
| --- ├── passportLocal.js
| --- ├── routes.js
| --- └── sendmail.js
├── model
│ --- ├── resetTokens.js
│ --- └── user.js
├── node_modules
├── views
│ --- ├── forgot-password.ejs
│ --- ├── index.ejs
│ --- ├── login.ejs
│ --- ├── profile.ejs
│ --- ├── signup.ejs
│ --- └── success.ejs
├── .gitignore
├── .env
├── index.js
├── package.json
├── package-lock.json
└── README.md
