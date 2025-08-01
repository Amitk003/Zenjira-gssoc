### AI-Powered Jira Management Platform

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Slack](https://img.shields.io/badge/slack-join%20community-blueviolet.svg)](https://join.slack.com/t/promptzy/shared_invite/zt-3acy22kkh-R~nMYTl7op_MF5UaLnwdsA)
[![TypeScript](https://img.shields.io/badge/typescript-4.9+-blue.svg)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/next.js-13+-black.svg)](https://nextjs.org/)

*Intelligent automation and AI-driven insights for modern development teams*

---

</div>

**Zenjira** is an enterprise-grade web platform that revolutionizes Jira workflow management through intelligent automation, AI-powered sprint planning, and comprehensive analytics — delivered via an intuitive, centralized dashboard.

---

## 🚀 Project Overview

Zenjira is like a personal AI assistant for Jira teams. It helps save time and reduce manual work by offering:

* **No-code automation** using n8n (just drag and drop rules!)
* **AI features** like ticket summarization and sprint planning with GPT‑4
* **Live dashboards** and visual tools like Gantt charts
* **Deep integrations** with GitHub/GitLab, Slack, CI/CD tools, and more

It’s built as a full **web application** — not just a browser extension — meaning teams log into Zenjira just like any other SaaS platform to get started.

---

## ✨ Features

### Core Features

* **Automation Designer**: Use n8n's drag-and-drop editor to automate Jira events like task transitions or sending Slack notifications.
* **AI Sprint Planner**: GPT‑4 helps generate sprints based on team capacity and priorities.
* **Smart Ticket Summaries**: Instantly summarize long issue descriptions with AI.
* **ChatOps Bot**: Use Slack or Microsoft Teams to ask things like "What are today's blockers?"
* **Developer Load Balancer**: Distribute tasks more evenly to avoid burnout.

### Advanced Features

* **Semantic Search**: Use Hugging Face models to search Jira issues based on meaning, not just keywords.
* **AI Test Case Generator**: Turn bug reports into suggested test cases.
* **Retrospective Insights**: Get reports on what worked and what didn’t after every sprint.
* **Gantt and Calendar Views**: Visual tools to see due dates, timelines, and sprint plans.
* **Cross-Project Heatmap**: Identify bottlenecks and dependencies between multiple projects.
* **Auto Release Notes**: Generate release notes from closed issues and merged pull requests.

---

## 🛠 Technology Stack

<details>
<summary><strong>Frontend Architecture</strong></summary>

| Technology | Purpose | Version |
|------------|---------|---------|
| **Next.js** | React Framework | 13+ |
| **TypeScript** | Type Safety | 4.9+ |
| **Tailwind CSS** | Styling System | 3.x |
| **shadcn/ui** | Component Library | Latest |
| **Redux Toolkit** | State Management | 1.9+ |

</details>

<details>
<summary><strong>Backend Infrastructure</strong></summary>

| Technology | Purpose | Implementation |
|------------|---------|----------------|
| **Node.js + Express** | Runtime & API Framework | REST/GraphQL |
| **PostgreSQL** | Primary Database | 14+ |
| **Redis** | Caching & Sessions | 7+ |
| **BullMQ** | Job Queue System | Latest |
| **JWT + OAuth2** | Authentication | Jira Integration |

</details>

<details>
<summary><strong>AI & Machine Learning</strong></summary>

| Service | Purpose | Provider |
|---------|---------|----------|
| **GPT-4** | Natural Language Processing | OpenAI |
| **LangChain** | AI Pipeline Management | Community |
| **Hugging Face** | Semantic Search Models | Transformers |

</details>

<details>
<summary><strong>DevOps & Infrastructure</strong></summary>

| Technology | Purpose | Environment |
|------------|---------|-------------|
| **Docker** | Containerization | All |
| **Kubernetes** | Orchestration | Production |
| **GitHub Actions** | CI/CD Pipeline | All |
| **AWS EKS** | Managed Kubernetes | Production |
| **Prometheus + Grafana** | Monitoring & Metrics | Production |

</details>

---

## 💬 Community & Support

<div align="center">

### Join Our Developer Community

[![Slack Community](https://img.shields.io/badge/Slack-Join%20Community-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://join.slack.com/t/promptzy/shared_invite/zt-3acy22kkh-R~nMYTl7op_MF5UaLnwdsA)

Connect with fellow developers, get technical support, and stay updated on the latest features and releases.

</div>

---

## � Development Roadmap

<div align="center">

### 4-Month Sprint to Production

</div>

```mermaid
gantt
    title Zenjira Development Timeline
    dateFormat  MM-DD
    section Phase 1
    Requirements & Setup    :active, p1, 08-01, 08-31
    section Phase 2  
    Core Features          :p2, 09-01, 09-30
    section Phase 3
    AI & Integrations      :p3, 10-01, 10-31
    section Phase 4
    Testing & Launch       :p4, 11-01, 11-30
```

### 🗓 **Phase 1: Foundation** *(Month 1)*
- [ ] **Architecture Design** - System design and technical specifications
- [ ] **UI/UX Design** - Figma wireframes and design system
- [ ] **Infrastructure Setup** - Docker, PostgreSQL, Redis, authentication
- [ ] **Development Environment** - CI/CD pipelines and tooling

### 🔧 **Phase 2: Core Platform** *(Month 2)*
- [ ] **Automation Engine** - n8n integration and workflow builder
- [ ] **Jira Integration** - OAuth2, issue management, real-time sync
- [ ] **AI Features** - GPT-4 integration for summaries and planning
- [ ] **ChatOps Bot** - Slack/Teams integration for team communication

### 🤖 **Phase 3: Intelligence Layer** *(Month 3)*
- [ ] **Semantic Search** - Hugging Face model integration
- [ ] **VCS Integration** - GitHub/GitLab pull request insights
- [ ] **Advanced Analytics** - Retrospectives and performance metrics
- [ ] **Visual Dashboards** - Gantt charts and project heatmaps

### 🚀 **Phase 4: Production Ready** *(Month 4)*
- [ ] **Quality Assurance** - Comprehensive testing suite (Jest, Cypress)
- [ ] **Performance Optimization** - Load testing and optimization
- [ ] **Monitoring & Observability** - Prometheus, Sentry, logging
- [ ] **Documentation & Launch** - API docs, user guides, beta release

---

## 🚀 Quick Start

### Prerequisites

- **Node.js** 18+ and **npm** (or **yarn**)
- **Git** for version control

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-org/zenjira.git
   cd zenjira
   ```

2. **Install dependencies**
   ```bash
   # Install all dependencies (root, frontend, and backend)
   npm run install:all

   # Or install individually:
   # Frontend: cd frontend && npm install
   # Backend: cd backend && npm install
   ```

3. **Environment setup**
   ```bash
   # Copy environment file and configure
   cd backend
   cp .env.example .env
   # Edit .env with your configuration
   ```

### Development Commands

#### 🎨 **Frontend (Next.js)**
```bash
cd frontend

# Start development server with Turbopack
npm run dev        # Runs on http://localhost:3000

# Build for production
npm run build

# Start production server
npm run start

# Run linting
npm run lint
```

#### ⚙️ **Backend (Express API)**
```bash
cd backend

# Start development server with auto-reload
npm run dev        # Runs on http://localhost:5000

# Start production server
npm start

# Check API health
curl http://localhost:5000/health

# Format backend code
npm run format

# Check code formatting
npm run format:check
```

#### 🔄 **Full Stack Development**
```bash
# Option 1: Run both frontend and backend simultaneously (recommended)
npm run dev        # Runs both servers with auto-reload

# Option 2: Run individually in separate terminals
# Terminal 1: Start backend
npm run dev:backend

# Terminal 2: Start frontend  
npm run dev:frontend
```

#### 🎨 **Code Formatting (Prettier)**
```bash
# Format backend code
npm run format:backend

# Check backend formatting
npm run format:check:backend

# Or from backend directory
cd backend
npm run format
npm run format:check
```

### API Endpoints

| Endpoint | Method | Description |
|----------|---------|-------------|
| `/health` | GET | Server health check |
| `/api/test` | GET | API connectivity test |
| `/api/jira/projects` | GET | List Jira projects *(coming soon)* |
| `/api/automation/workflows` | GET | Automation workflows *(coming soon)* |
| `/api/ai/summarize` | POST | AI-powered summarization *(coming soon)* |

### Development URLs

- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:5000
- **API Health Check**: http://localhost:5000/health

---

## 📜 Code of Conduct

Please read our [Code of Conduct](./CODE_OF_CONDUCT.md) to understand the expected behavior in this community.


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Built with ❤️ by the Zenjira Team**

*Transforming development workflows, one sprint at a time.*

</div>
