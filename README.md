# Hi, I'm Ilia Roshchin 🦊

Python backend developer focused on web APIs, database-driven applications and deployed backend services.

I work with Django and FastAPI, PostgreSQL, background tasks, caching, testing and containerized deployment. My projects include both backend development from scratch and migration of an existing application between backend stacks while preserving its API and data.

My main language is Python. Some repositories also contain frontend code because I work on full-stack product projects and backend–frontend integration.

## 🛠 Skills and technologies

### Backend

<p>
  <img src="https://img.shields.io/badge/Python-3.12+-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-5.x-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Django_REST_Framework-API-ff1709?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-API-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-ORM-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-validation-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-authentication-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Asyncio-async_IO-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

### Databases, caching and messaging

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-database-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-caching-FF4438?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-message_broker-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-background_tasks-37814A?style=flat-square&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/Alembic-migrations-6BA81E?style=flat-square" />
  <img src="https://img.shields.io/badge/SQLite-database-003B57?style=flat-square&logo=sqlite&logoColor=white" />
</p>

### Testing

<p>
  <img src="https://img.shields.io/badge/Pytest-tests-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Unittest-standard_library-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

### DevOps & deployment

<p>
  <img src="https://img.shields.io/badge/Docker-containers-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker_Compose-multi--container_apps-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-reverse_proxy-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Gunicorn-WSGI-499848?style=flat-square&logo=gunicorn&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-server-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Bash-scripts-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-version_control-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-CI/CD-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-basics-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
</p>

### Frontend basics

<p>
  <img src="https://img.shields.io/badge/HTML-markup-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-styling-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-basics-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-integration-61DAFB?style=flat-square&logo=react&logoColor=black" />
</p>

## 🚀 Featured projects

### Formaslov

Web application for working with qualitative research texts: uploading materials, annotating text fragments, organizing labels and exporting results.

**My focus:** backend architecture, API development, database design, background processing, deployment and frontend–backend integration.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

- Migrated the main API from Django/DRF to FastAPI while preserving existing data and API behavior
- Implemented async SQLAlchemy-based data access and Alembic migrations
- Added Redis caching for frequently requested user data
- Added RabbitMQ and Celery for background processing
- Implemented batch ZIP imports for `.txt` and `.docx` materials
- Implemented background exports with status tracking and file download
- Deployed the FastAPI runtime with PostgreSQL, Redis, RabbitMQ, Celery, Docker and Nginx

<p>
  <a href="https://forma-slov.ru">Live demo</a>
  ·
  <a href="https://github.com/IhuliR/formaslov">Repository</a>
</p>

### TeamLab

Independent product project developed by a small team: a platform for finding teammates and forming teams for pet, educational and non-commercial projects.

**My role:** Team Lead / Backend Developer  
**Team:** 1 designer, 3 frontend developers, and me  
**Focus:** backend architecture, domain modeling, REST API design and implementation, and coordination with frontend and design

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/DRF-ff1709?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
</p>

- Designed backend data models for users, projects, roles, skills and memberships
- Designed and implemented the REST API with Django REST Framework
- Implemented authentication, permissions and project membership workflows
- Maintain the API contract and backend integration with the frontend
- Coordinate technical and product decisions across backend, frontend and design

The core backend is implemented; the project is currently focused on frontend integration and further product development.

<p>
  <a href="https://github.com/IhuliR/teamlab_backend">Backend repository</a>
  ·
  <a href="https://github.com/distinkt-dd/TeamLab-Frontend">Frontend repository</a>
</p>

## What I'm looking for

I'm looking for a Python Backend Developer role focused on Django or FastAPI, REST APIs, PostgreSQL and backend services deployed in production.

I'm especially interested in API development, database-backed applications, background processing and backend infrastructure.

## Contacts

- GitHub: @IhuliR
- Telegram: @ihulir
- Email: [neo-ily81@yandex.ru](mailto:neo-ily81@yandex.ru)
