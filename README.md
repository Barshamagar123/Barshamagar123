<!-- Header Section -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&duration=3000&pause=500&color=00D4FF&center=true&vCenter=true&width=500&lines=Full+Stack+Developer;MERN+Stack+Expert;Database+Architect;Problem+Solver;Lifelong+Learner" alt="Typing SVG" />
</div>

<!-- Profile Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=👋%20Namaste!&fontSize=60&fontAlignY=35&animation=twinkling" alt="Header" width="100%"/>
</div>

<h1 align="center">I'm Barsha Magar</h1>
<h3 align="center">Full Stack Developer | MERN Stack | Database Enthusiast</h3>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Barshamagar123&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Barshamagar123?label=Followers&style=social" alt="Followers" />
  <img src="https://img.shields.io/github/stars/Barshamagar123?label=Stars&style=social" alt="Stars" />
  <img src="https://img.shields.io/badge/Full%20Stack-Developer-blue?style=flat" alt="Full Stack Developer" />
</div>

<br/>

<!-- About Me Section -->
## 🚀 About Me

<!-- <img align="right" alt="Coding" width="400" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" /> -->

👋 Hi there! I'm **Barsha Magar**, a passionate Full Stack Developer with a love for building scalable web applications.

- 🔭 **Currently working on:** Building full-stack applications with MERN stack
- 🌱 **Currently learning:** Advanced Docker, Kubernetes, and Microservices
- 👯 **Looking to collaborate on:** Open Source Projects, Full Stack Applications
- 💬 **Ask me about:** MERN Stack, Databases (MongoDB, MySQL, PostgreSQL)
- 📫 **How to reach me:** [Email](mailto:your.email@gmail.com)
- ⚡ **Fun fact:** I can debug code faster than I can debug my life! 🐛

### 🛠️ My Tech Stack

#### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

#### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

#### Databases
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

#### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

<br/>

<!-- GitHub Stats -->
## 📊 GitHub Analytics

<div align="center">
  <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api?username=Barshamagar123&show_icons=true&count_private=true&hide_border=true&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9&bg_color=0d1117" alt="GitHub Stats" />
  <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Barshamagar123&layout=compact&hide_border=true&title_color=00d4ff&text_color=c9d1d9&bg_color=0d1117" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Barshamagar123&theme=dark&hide_border=true&stroke=00d4ff&ring=00d4ff&fire=00d4ff&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=00d4ff&sideLabels=c9d1d9&dates=c9d1d9" alt="GitHub Streak" />
</div>

<br/>

<!-- Contribution Graph -->
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Barshamagar123&bg_color=0d1117&color=00d4ff&line=00d4ff&point=c9d1d9&area=true&hide_border=true" alt="Contribution Graph" />
</div>

<br/>

<!-- Docker Configuration -->
## 🐳 Docker Setup for Full Stack Development

<details>
<summary><b>Click to expand Docker Configuration</b></summary>

### Docker Compose for MERN Stack + Databases

```yaml
version: '3.8'

services:
  # MongoDB Database
  mongodb:
    image: mongo:6.0
    container_name: mern-mongodb
    restart: always
    ports:
      - "27017:27017"
    environment:
      MONGO_INITDB_ROOT_USERNAME: admin
      MONGO_INITDB_ROOT_PASSWORD: secret
      MONGO_INITDB_DATABASE: myapp
    volumes:
      - mongodb_data:/data/db
    networks:
      - app-network

  # MySQL Database
  mysql:
    image: mysql:8.0
    container_name: mern-mysql
    restart: always
    ports:
      - "3306:3306"
    environment:
      MYSQL_ROOT_PASSWORD: secret
      MYSQL_DATABASE: myapp
      MYSQL_USER: admin
      MYSQL_PASSWORD: secret
    volumes:
      - mysql_data:/var/lib/mysql
    networks:
      - app-network

  # PostgreSQL Database
  postgres:
    image: postgres:15
    container_name: mern-postgres
    restart: always
    ports:
      - "5432:5432"
    environment:
      POSTGRES_USER: admin
      POSTGRES_PASSWORD: secret
      POSTGRES_DB: myapp
    volumes:
      - postgres_data:/var/lib/postgresql/data
    networks:
      - app-network

  # Redis Cache
  redis:
    image: redis:7.0-alpine
    container_name: mern-redis
    restart: always
    ports:
      - "6379:6379"
    volumes:
      - redis_data:/data
    networks:
      - app-network

  # Node.js Backend
  backend:
    build:
      context: ./backend
      dockerfile: Dockerfile
    container_name: mern-backend
    restart: always
    ports:
      - "5000:5000"
    environment:
      NODE_ENV: development
      PORT: 5000
      MONGO_URI: mongodb://admin:secret@mongodb:27017/myapp?authSource=admin
      MYSQL_URI: mysql://admin:secret@mysql:3306/myapp
      POSTGRES_URI: postgresql://admin:secret@postgres:5432/myapp
      REDIS_URL: redis://redis:6379
      JWT_SECRET: your_jwt_secret
    depends_on:
      - mongodb
      - mysql
      - postgres
      - redis
    volumes:
      - ./backend:/app
      - /app/node_modules
    networks:
      - app-network

  # React Frontend
  frontend:
    build:
      context: ./frontend
      dockerfile: Dockerfile
    container_name: mern-frontend
    restart: always
    ports:
      - "3000:3000"
    environment:
      REACT_APP_API_URL: http://localhost:5000/api
    depends_on:
      - backend
    volumes:
      - ./frontend:/app
      - /app/node_modules
    networks:
      - app-network

# Volumes for data persistence
volumes:
  mongodb_data:
  mysql_data:
  postgres_data:
  redis_data:

# Network
networks:
  app-network:
    driver: bridge