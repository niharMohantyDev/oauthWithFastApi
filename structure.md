project-root/
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   │
│   ├── core/
│   │   ├── config.py
│   │   └── security.py
│   │
│   ├── models/
│   │   ├── base.py
│   │   ├── schemas.py
│   │   └── db_models.py
│   │
│   ├── api/
│   │   ├── __init__.py
│   │   ├── v1/
│   │   │   ├── __init__.py
│   │   │   ├── endpoints/
│   │   │   │   ├── items.py
│   │   │   │   ├── users.py
│   │   │   │   └── ...
│   │   │   └── api.py
│   │
│   ├── services/
│   │   ├── item_service.py
│   │   └── user_service.py
│   │
│   ├── dependencies.py
│   │
│   ├── database/
│   │   ├── __init__.py
│   │   └── session.py
│   │
│   └── utils/
│       ├── logger.py
│       └── helpers.py
│
├── tests/
│   ├── unit/
│   ├── integration/
│   └── conftest.py
│
├── alembic/
│   ├── versions/
│   └── env.py
│
├── static/
├── templates/
│
├── requirements/
│   ├── base.txt
│   ├── dev.txt
│   └── prod.txt
│
├── .env
├── .gitignore
├── Dockerfile
├── docker-compose.yml
└── README.md
