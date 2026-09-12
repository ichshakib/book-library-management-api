---
name: 🐛 Bug Report
about: Report a bug or issue in the Book Library Management API
title: "[BUG] "
labels: ["bug"]
assignees: []
---

## 🐛 Bug Description

<!-- A clear and concise description of what the bug is. -->

## 🛠️ Affected Component

- [ ] Authentication / Session (JWT, Passport.js, Cookies)
- [ ] OAuth SSO (Google / GitHub)
- [ ] Book Management (`/books`)
- [ ] Reviews & Ratings (`/reviews`)
- [ ] User Favorites (`/favorites`)
- [ ] Email Notifications (Nodemailer / MailHog)
- [ ] Swagger API Docs (`/`)
- [ ] Docker / Deployment
- [ ] Other

## 📡 Request Details (if API-related)

- **HTTP Method:** `GET` / `POST` / `PUT` / `DELETE` / `PATCH`
- **Endpoint URL:** `http://localhost:7000/...`
- **Request Body (JSON / FormData):**
  ```json
  {}
  ```

## 🔁 Reproduction Steps

1. Start server with `pnpm run dev`
2. Send request to `...`
3. See error response / server crash

## 🧐 Expected vs Actual Behavior

- **Expected Response:** (e.g. `200 OK` with `{ statusCode: 200, data: ... }`)
- **Actual Response:** (e.g. `500 Internal Server Error` or unexpected status code)

## 📋 Server Console Logs / Stack Trace

```text
<!-- Paste error logs from terminal or Docker container here -->
```

## 💻 Environment

- **Node.js Version:** [e.g. v20.18.0, v22.12.0]
- **pnpm Version:** [e.g. 12.4.1]
- **MongoDB:** [e.g. Local v7.0, Docker container, MongoDB Atlas]
- **Operating System:** [e.g. Windows 11, Ubuntu 24.04, macOS]
