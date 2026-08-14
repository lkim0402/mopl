# Mopl (Everyone's Playlist)

[![codecov](https://codecov.io/gh/sb04-mopl-team2/sb04-mopl-team2/graph/badge.svg?token=F3N6H5J7OG)](https://codecov.io/gh/sb04-mopl-team2/sb04-mopl-team2)

# Table of Contents

1. [Project Overview](#project-overview)
2. [Team Members](#team-members)
3. [Tech Stack](#tech-stack)
4. [System Architecture](#system-architecture)
5. [Execution Guide](#execution-guide)
6. [Key Features](#key-features)
   - [Content Management](#content-management)
   - [Playlist](#playlist)
   - [Social Features](#social-features)
   - [Real-time Features](#real-time-features)
   - [User Management](#user-management)
   - [Admin Features](#admin-features)
   - [Key API Endpoints](#key-api-endpoints)

# 🌟 Project Overview: Mopl (Everyone's Playlist)

**A global content rating platform designed for high-volume traffic**

Mopl is a content curation platform where users can rate various content such as movies, dramas, and sports, as well as create and share playlists based on their own criteria. Through social features such as real-time watch parties, playlist subscriptions, follows, and DMs, users can share the joy of watching content with others.

**Your unique taste gathers to become everyone's taste!** ✨

## 📅 Project Information

- **Project Period**: 2025.11.10 ~ 2025.12.18
- **Team Composition**: 6 Members (Backend Development)

## 📖 User Guide

First time using Mopl? Check out the detailed user guide and feature descriptions!

👉 **[📚 Go to Notion User Guide](https://www.notion.so/2caabb8e46aa801b8a32d0d5bf720ef6?source=copy_link)**

## 🔗 Related Links

| Category | Link |
| :--------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 🌐 **Deployment Site** | [mopl.site](https://mopl.site/) |
| 🎨 **Portfolio** | [Canva Portfolio](https://www.canva.com/design/DAG4SpC2BEE/cT2MvW3Pjw7MOGCn3yvaxA/edit?utm_content=DAG4SpC2BEE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) |
| 📋 **Team Notion** | [Team Notion Page](https://www.notion.so/2-2a7abb8e46aa80cca898f383e61fd72a?source=copy_link) |
| 📝 **Requirements Doc** | [Google Sheets](https://docs.google.com/spreadsheets/d/1Tc-qkTBSyD8mJEasUHanuor_W_N4QPC8wnyZyZwcfec/edit?usp=sharing) |

# 👥 Team Members

A team composed of 6 backend developers. Each member developed assigned key features and collaborated to complete the project.

| Myeongjae Oh | Minsu Kim | Eunseo Moon | Ijun Kim | Jihyun Lee | Yongjin Kwon |
|:-----------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------:|
| <a href="https://github.com/Oh-Myeongjae"><img src="https://avatars.githubusercontent.com/u/74406343?v=4" width="100px" alt="Myeongjae Oh's GitHub Profile"></a> | <a href="https://github.com/NanHangBok"><img src="https://avatars.githubusercontent.com/u/105554085?v=4" width="100px" alt="Minsu Kim's GitHub Profile"></a> | <a href="https://github.com/kosy00"><img src="https://avatars.githubusercontent.com/u/191211966?v=4" width="100px" alt="Eunseo Moon's GitHub Profile"></a> | <a href="https://github.com/lkim0402"><img src="https://avatars.githubusercontent.com/u/93887188?v=4" width="100px" alt="Ijun Kim's GitHub Profile"></a> | <a href="https://github.com/devlee1011"><img src="https://avatars.githubusercontent.com/u/138750938?v=4" width="100px" alt="Jihyun Lee's GitHub Profile"></a> | <a href="https://github.com/chaoskyj1120"><img src="https://avatars.githubusercontent.com/u/211930549?v=4" width="100px" alt="Yongjin Kwon's GitHub Profile"></a> |
| Content Collection & Management <br/>Batch Processing Implementation | User Management - Security | DM Management <br/>Playlist Management | Real-time Watch Party<br/> Chat Messages<br/>OpenSearch | Profile Management <br/> (Follow API) <br/>CI/CD Setup | Notification Management<br/>Review Management |
| [📝 Personal Retrospective](https://www.notion.so/2a9abb8e46aa803fa908c1b1f21a783d?source=copy_link) | [📝 Personal Retrospective](https://www.notion.so/2a9abb8e46aa803d9af2fd0a875039ca?source=copy_link) | [📝 Personal Retrospective](https://www.notion.so/2a9abb8e46aa80f3a60bf05b871befd7?source=copy_link) | [📝 Personal Retrospective](https://www.notion.so/2a9abb8e46aa80438c99ea389051a741?source=copy_link) | [📝 Personal Retrospective](https://www.notion.so/2a9abb8e46aa80ef9f24f4fb3d24d151?source=copy_link) | [📝 Personal Retrospective](https://www.notion.so/2a9abb8e46aa80ebb939f4111a65ae37?source=copy_link) |

# 🛠 Tech Stack

| Category | Stacks |
| :--------------------- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Backend** | ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/spring_boot-%236DB33F.svg?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![QueryDSL](https://img.shields.io/badge/QueryDSL-007396?style=flat-square&logo=java&logoColor=white) ![Spring Batch](https://img.shields.io/badge/Spring%20Batch-6DB33F?style=flat-square&logo=spring&logoColor=white) |
| **Messaging** | ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Confluent](https://img.shields.io/badge/Confluent%20Cloud-E2231A?style=flat-square&logo=confluent&logoColor=white) |
| **Database & Storage** | ![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white) ![Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white) ![H2](https://img.shields.io/badge/H2%20Database-003B57?style=flat-square&logo=h2&logoColor=white) ![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![Amazon OpenSearch](https://img.shields.io/badge/Amazon%20OpenSearch-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![Amazon ElastiCache](https://img.shields.io/badge/Amazon%20ElastiCache-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) |
| **Infra & Deployment** | ![AWS](https://img.shields.io/badge/AWS-%23232F3E.svg?style=flat-square&logo=amazon-aws&logoColor=white) ![Amazon ECS](https://img.shields.io/badge/Amazon%20ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white) ![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![Amazon ElasticIP](https://img.shields.io/badge/Amazon%20ElasticIP-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![Amazon ECR](https://img.shields.io/badge/Amazon%20ECR-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=Cloudflare&logoColor=white) ![Amazon EventBridge](https://img.shields.io/badge/Amazon%20EventBridge-FF4F8B?style=flat-square&logo=amazoneventbridge&logoColor=white) |
| **Testing** | ![Mockito](https://img.shields.io/badge/Mockito-788BD2?style=flat-square&logo=java&logoColor=white) ![Jacoco](https://img.shields.io/badge/Jacoco-EA2D2E?style=flat-square&logo=jacoco&logoColor=white) |
| **Auth & API** | ![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=JSON%20web%20tokens) ![OAuth2](https://img.shields.io/badge/OAuth2-3D3D3D?style=flat-square&logo=oauth&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=flat-square&logo=swagger&logoColor=white) ![TMDb API](https://img.shields.io/badge/-TMDb%20API-01B4E4?style=flat-square&logo=themoviedatabase&logoColor=white) ![TheSportsDB](https://img.shields.io/badge/-TheSportsDB-0c7475?style=flat-square&logo=thesportsdb&logoColor=white) |
| **Tools** | ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat-square&logo=github&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=flat-square&logo=discord&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=flat-square&logo=notion&logoColor=white) |

# 🏗 System Architecture

> System Architecture Diagram
![System Architecture Diagram](docs/images/system-architecture-diagram.png)

The current project architecture is structured as follows:

- **Backend**: Spring Boot-based RESTful API server
- **Database**: PostgreSQL (RDS) + Redis (Caching)
- **Search**: OpenSearch (Content Search)
- **Storage**: Amazon S3 (Image Storage)
- **Messaging**: Confluent Cloud, Apache Kafka (Asynchronous Event Processing)
- **Deployment**: AWS ECS(Fargate), ECR + Docker, AWS EventBridge + Lambda(Scheduling), Cloudflare
- **CI/CD**: GitHub Actions
- **External API**: OAuth2(Google, Kakao), TMDb API, TheSportsDB(Content Metadata Collection)

# 🚀 Execution Guide

Here are the minimal steps to quickly launch the local development environment.

## 1) Prerequisites

- Java 17+
- Docker Desktop (Including Docker Compose)
- Git

## 2) Environment Variables (.env)

Create a `.env` file in the project root directory and fill in the values below.

```env
# DB
POSTGRESQL_DATASOURCE_URL=jdbc:postgresql://localhost:5432/mopl
POSTGRESQL_DATASOURCE_USERNAME=your_username
POSTGRESQL_DATASOURCE_PASSWORD=your_password

# Redis
REDIS_HOST=localhost
REDIS_PORT=6379

# JWT
JWT_KEY=your-secret-key-min-256-bits
ACCESS_TOKEN_EXPIRATION_MINUTES=30
REFRESH_TOKEN_EXPIRATION_MINUTES=1440

# TMDB
TMDB_API_TOKEN=your-tmdb-token
TMDB_BASE_URL=[https://api.themoviedb.org/3](https://api.themoviedb.org/3)
