legalisludu-auth/
├─ server.js                (from the canvas)
├─ .env                     (you create this file)
├─ package.json             (copy the snippet below)
└─ public/
   ├─ register.html         (from the canvas)
   └─ login.html            (from the canvas)

Create package.json (copy–paste)
{
  "name": "legalisludu-auth",
  "version": "1.0.0",
  "main": "server.js",
  "type": "commonjs",
  "scripts": { "start": "node server.js" },
  "dependencies": {
    "bcrypt": "^5.1.1",
    "better-sqlite3": "^9.4.3",
    "cors": "^2.8.5",
    "dotenv": "^16.4.5",
    "express": "^4.19.2",
    "jsonwebtoken": "^9.0.2",
    "nodemailer": "^6.9.13"
  }
}


Create .env (fill in your details)

APP_PUBLIC_URL=https://legalisludu.com
API_PUBLIC_URL=https://legalisludu.com

JWT_SECRET=change_this_to_a_long_random_string
DB_PATH=./legalisludu.db

# If using Gmail App Password:
SMTP_HOST=smtp.gmail.com
SMTP_PORT=465
SMTP_SECURE=true
SMTP_USER=yourgmail@gmail.com
SMTP_PASS=YOUR_16_CHAR_APP_PASSWORD

# Shown to your users as the sender
MAIL_FROM="Legal iSludu <no-reply@legalisludu.com>"
<img width="451" height="662" alt="image" src="https://github.com/user-attachments/assets/33d5b085-17a6-487a-9830-1189ea9461fc" />
