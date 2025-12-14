# ⚽ Hotfut Coach App

[![React Native](https://img.shields.io/badge/React%20Native-0.72-blue)](https://reactnative.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green)](https://nodejs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-blue)](https://www.postgresql.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3+-blue)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-Proprietary-red)](LICENSE)

> A comprehensive mobile application for coaches to manage daily attendance, track student progress using a 10-level system, and create session plans across all Hotfut Sports academies.

**📚 [View Documentation](https://yourusername.github.io/hotfut-coach-app/)** | **🚀 [Quick Start](./RUN_APP.md)** | **📖 [Full Setup Guide](./QUICK_START.md)**

## 🎯 Project Overview

The Coach App is designed to work in real academy conditions with:
- **Offline-first architecture** for poor internet connectivity
- **Fast UX** - attendance + progress marking in under 2 minutes
- **Scalable** for 1000+ coaches
- **Production-ready Phase 1** with Phase 2 enhancements architected

## 📱 Primary Users

- **Coach** (Phase 1 & 2) - Daily operations
- **Head Coach / Program Manager** (Phase 2) - Review & oversight

## 🏗️ Architecture

- **Frontend**: React Native (Android priority)
- **Backend**: Node.js + Express (API-first)
- **Database**: PostgreSQL with offline sync
- **Offline Storage**: SQLite (React Native)
- **Authentication**: OTP-based mobile authentication

## 📂 Project Structure

```
├── docs/                    # Documentation
│   ├── user-flows.md
│   ├── screen-list.md
│   ├── database-schema.md
│   ├── api-design.md
│   ├── tech-stack.md
│   └── roadmap.md
├── mobile/                  # React Native App
│   ├── src/
│   │   ├── screens/
│   │   ├── components/
│   │   ├── services/
│   │   ├── store/
│   │   └── utils/
│   └── package.json
├── backend/                 # Node.js API
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── middleware/
│   │   └── utils/
│   └── package.json
└── database/                # Database migrations
    └── migrations/
```

## 🚀 Quick Start

**👉 Want to see the app running? Check [RUN_APP.md](./RUN_APP.md) for the fastest way!**

**👉 For detailed setup, see [QUICK_START.md](./QUICK_START.md)**

### Prerequisites
- Node.js 18+
- React Native CLI
- PostgreSQL 14+
- Android Studio (for Android development)

### Installation

```bash
# Install dependencies
cd mobile && npm install
cd ../backend && npm install

# Setup database
cd database && npm run migrate

# Start backend
cd backend && npm run dev

# Start mobile app
cd mobile && npm run android
```

## 📋 Phase 1 Features (MVP)

✅ Authentication via mobile + OTP  
✅ Coach profile with assigned batches  
✅ Daily session view with batch switching  
✅ Offline-first attendance marking  
✅ 10-level progress tracking system  
✅ Session plan creation & management  

## 📋 Phase 2 Features (Future)

🔜 Head Coach review dashboard  
🔜 Advanced analytics & reports  
🔜 Parent-ready data exports  
🔜 Media tagging & evidence  
🔜 Notifications & reminders  
🔜 Multisport configuration  

## 📸 Preview

> **Note**: Add screenshots to `docs/screenshots/` and update this section with actual app screenshots.

<!-- 
### Login Screen
![Login](docs/screenshots/login.png)

### Dashboard
![Dashboard](docs/screenshots/dashboard.png)

### Session Management
![Session](docs/screenshots/session.png)
-->

## 📖 Documentation

See the `docs/` folder for detailed documentation:
- [User Flows](./docs/user-flows.md)
- [Screen List](./docs/screen-list.md)
- [Database Schema](./docs/database-schema.md)
- [API Design](./docs/api-design.md)
- [Tech Stack](./docs/tech-stack.md)
- [Development Roadmap](./docs/roadmap.md)
- [GitHub Preview Guide](./docs/GITHUB_PREVIEW.md)

## 👥 Team

**Hotfut Sports Pvt LTD**  
Head of Operations: Mithun

## 📄 License

Proprietary - Hotfut Sports Pvt LTD

