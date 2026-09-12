## 📋 Summary

<!-- Provide a brief description of what this PR introduces or fixes for the Book Library Management API. -->

## 🔗 Related Issue

<!-- Link related issues (e.g. Closes #12, Fixes #45) -->

## 🛠️ Type of Change

- [ ] 🐛 Bug fix (non-breaking change fixing an issue)
- [ ] ✨ New feature (non-breaking change adding an endpoint or capability)
- [ ] 💥 Breaking change (fix or feature modifying existing API response/contracts)
- [ ] 🗄️ Database schema / Model update
- [ ] 🔐 Auth / Security enhancement
- [ ] 📖 Documentation / Swagger update
- [ ] ⚡ Performance improvement / Refactoring

## 📡 Affected API Endpoints (if applicable)

| Method                | Endpoint      | Description |
| :-------------------- | :------------ | :---------- |
| `GET/POST/PUT/DELETE` | `/api/v1/...` |             |

## ⚙️ Environment / Configuration Changes

- [ ] Requires new environment variable(s) (Updated `.env.example`)
- [ ] Requires database re-seeding (`pnpm run seed`)
- [ ] No configuration changes required

## 🧪 Testing & Verification

- [ ] Tested endpoint(s) locally using cURL / Postman / Swagger UI (`http://localhost:7000/`)
- [ ] Verified database read/write in MongoDB
- [ ] Ran `pnpm run format:check` and all files adhere to Prettier standards
- [ ] JavaScript syntax validated (`node --check` across `src/`)

## 📋 Checklist

- [ ] My code follows the project's code style and architectural conventions
- [ ] I have updated [README.md](file:///README.md) or [swagger.yaml](file:///src/swagger.yaml) if API contracts changed
- [ ] My changes do not introduce unhandled errors or memory leaks
- [ ] Sensitive secrets or `.env` files are not included in this PR
