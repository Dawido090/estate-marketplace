🔗 [Kanban board](https://github.com/users/SzymkowskiDev/projects/10/views/1)

# Estate Marketplace
Lessons learned from Workforce Data Platform, we start with:
- sourced data
- docker setup
- relational database (filled with data)
- key-value database (filled with data)

We focus on:
- REST API development
- Django app development


## 🔗 Related Projects
* First edition: [Workfroce Data Platform](https://github.com/SzymkowskiDev/workforce-data-platform)


## 🏛️ Architecture
![architecture](https://github.com/SzymkowskiDev/estate-marketplace/blob/main/assets/arch.png?raw=true)


## 📋 Requirements
- Docker (so, WSL2 too)


## 🚀 How to run
Description.


## 📅 Development schedule

- 13/05/2023: Introductory meeting & Start of Sprint 1
- 27/05/2023: Sprint 1 review
- 10/06/2023: Sprint 2 review
- 24/06/2023: Sprint 3 review & Demo Day

**Pre-development: System Architecture**

- [ ] Docker setup
- [ ] Postgres setup
- [ ] Redis setup
- [ ] Django skeleton
- [ ] FastAPI skeleton

**REST API development - Microservices (FastAPI)**

- [ ] `auth` Authentication
- [ ] `buyers_client` CRUD operations on Buyers table
- [ ] `sellers_client` CRUD operations on Sellers table
- [ ] `analytics_client` Produces statistics from Offers table

**Web app development (Django)**

- [ ] Authentication
- [ ] Seller panel makes requests to `buyers_client`
- [ ] Buyer panel makes requests to `sellers_client` and `buyers_client`
- [ ] Admin panel - views all data
- [ ] Analytics panel


## 🗃️ Data
Entity Relationship Diagram
![erd](https://github.com/SzymkowskiDev/estate-marketplace/blob/main/assets/erd.PNG?raw=true)


## 🎓 Learning Materials
* How to install `docker` for Windows [docs.docker.com](https://docs.docker.com/desktop/install/windows-install/)
* `Postgres` documentation [postgresql.org](https://www.postgresql.org/)
* `psycopg2` documentation [psycopg.org](https://www.psycopg.org/docs/)
* `Redis` documentation [redis.io](https://redis.io/)
* How to use `redis` with Python [realpython.com](https://realpython.com/python-redis/)
* `FastAPI` documentation [fastapi.tiangolo.com](https://fastapi.tiangolo.com/)
* `Django` documentation [djangoproject.com](https://www.djangoproject.com/)


## 👨‍💻 Contributing
- a
- b
- c
- d
- e
- f
- g

![logo](https://github.com/SzymkowskiDev/estate-marketplace/blob/main/assets/logo.png?raw=true)

## 📄 License
[MIT License](https://choosealicense.com/licenses/mit/) ©️ 2019-2020 [Kamil Szymkowski](https://github.com/SzymkowskiDev "Get in touch!")

[![](https://img.shields.io/badge/license-MIT-green?style=plastic)](https://choosealicense.com/licenses/mit/)
