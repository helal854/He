# مشروع Trading Bot

## هيكل الملفات
```
project-root/
├── backend/app/
│   ├── main.py
│   ├── config.py
│   ├── models/
│   ├── schemas/
│   ├── routers/
│   ├── services/
│   └── utils/
├── frontend/
│   ├── public/
│   └── src/
│       ├── pages/
│       ├── components/
│       └── services/
├── infra/
│   ├── docker-compose.yml
│   └── k8s/
├── docs/
│   ├── Architecture.md
│   ├── API.md
│   └── Policies.md
├── scripts/
│   ├── backtest.py
│   └── load_test.js
└── README.md
```
## متطلبات التشغيل
- Python 3.8+
- Node.js 14+
- Docker & Docker-Compose
- Redis & PostgreSQL
## تقنيات البرمجة
- Backend: Python, FastAPI, SQLAlchemy, Celery
- Frontend: React, Tailwind CSS
- Infra: Docker, Prometheus, k6
