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
<br>
NODEJS_AUTH<br>
├── controller<br>
| --- ├── accountRoutes.js<br>
| --- ├── googleAuth.js<br>
| --- ├── passportLocal.js<br>
| --- ├── routes.js<br>
| --- └── sendmail.js<br>
├── model<br>
│ --- ├── resetTokens.js<br>
│ --- └── user.js<br>
├── node_modules<br>
├── views<br>
│ --- ├── forgot-password.ejs<br>
│ --- ├── index.ejs<br>
│ --- ├── login.ejs<br>
│ --- ├── profile.ejs<br>
│ --- ├── signup.ejs<br>
│ --- └── success.ejs<br>
├── .gitignore<br>
├── .env<br>
├── index.js<br>
├── package.json<br>
├── package-lock.json<br>
└── README.md<br>
