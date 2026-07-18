# Damola Adegbite

<div align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="400" alt="Coding Animation">
</div>

Backend developer building with Node.js and TypeScript.

[Portfolio](https://damola.me/)

## Published npm packages

I build developer tools that cut down boilerplate.

**[@dax-side/jwt-abstraction](https://www.npmjs.com/package/@dax-side/jwt-abstraction)** - JWT auth in 3 lines  
Handles access/refresh tokens, Express middleware, error types. 100% test coverage. Used in 3 production projects.  
[Docs](https://dax-side.github.io/jwt-abstraction-site) | [npm](https://www.npmjs.com/package/@dax-side/jwt-abstraction) | [GitHub](https://github.com/dax-side/jwt-abstraction)

**[Express Journey Mapper](https://github.com/dax-side/express-journey-mapper)** - Auto-generate OpenAPI docs  
Reads your Express routes and generates Swagger documentation. No manual yaml editing.  
[npm](https://www.npmjs.com/package/express-journey-mapper)

**[error-telex](https://www.npmjs.com/package/error-telex)** - TypeScript error tracking SDK  
Co-built during HNG internship. Sends error reports to Telex backend with automatic retry and filtering.  
[npm](https://www.npmjs.com/package/error-telex)

---

## What I work on

Backend systems: APIs, databases, authentication, real-time features, production deployment.

**Recent work:**
- B2B platform for liquor stores and vendors (live in production)
- Automated CI/CD pipeline with health checks and rollback
- Weather API service with intelligent caching
- Working on: Analytics platform with event tracking SDK

## Tech stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,typescript,javascript,python,nestjs,express,graphql,postgresql,mongodb,redis,prisma,docker,nginx,aws" />
</div>

**Backend:** Node.js, TypeScript, Express, NestJS, GraphQL (Apollo Server)  
**Databases:** PostgreSQL, MongoDB, Redis, Prisma ORM  
**DevOps:** GitHub Actions, PM2, Docker, Nginx, AWS EC2  
**Tools:** Railway, Postman, k6, Artillery

## Currently working on:
- Learning Go and working through the DevOps path on [Boot.dev](https://www.boot.dev/u/dax-side)

## Writing

I write about backend systems and building things that actually work.

- [How Would I Build a Payment System That Doesn't Lose Money](https://dev.to/dax-side/how-would-i-build-a-payment-system-that-doesnt-lose-money-16ap)
- [How Would I Build For Right Now](https://dev.to/dax-side/how-would-i-build-for-right-now-2fmm)
- [I built an MCP server that syncs GitHub into Notion and generates AI reports](https://dev.to/dax-side/i-built-an-mcp-server-that-syncs-github-into-notion-and-generates-ai-reports-5ao6)
- [I built a tool that shows developers what their backend costs the planet](https://dev.to/dax-side/i-built-a-tool-that-shows-developers-what-their-backend-costs-the-planet-jm1)

## Projects

**Nevala Production Deployment System**  
Built automated CI/CD pipeline with GitHub Actions after staging server crashed from missing .env variables. Implemented health checks, automatic rollback on failure, git stash for conflict prevention, and backup system (keeps 5 recent versions). Staging/production separation saved the main server when things broke.  
Tech: GitHub Actions, PM2, AWS EC2, Bash, Health Monitoring

**[E-commerce Microservices API](https://github.com/dax-side/ecommerce-microservices-api)**  
Scaled performance from 48 to 716 req/sec by adding Redis caching, MongoDB connection pooling, and proper indexing. Load tested with k6 at 200 concurrent users.  
Tech: Node.js, TypeScript, MongoDB, Redis, Docker, Nginx, Prometheus

**[Weather Forecast Service](https://github.com/dax-side/weather_forecast_service)**  
REST API with intelligent caching and rate limiting  
[Live site](https://weatherforecastservice-production.up.railway.app/)

**Heart of House Platform** (Client work - Backend)  
Built the backend for a B2B marketplace connecting liquor stores and vendors. Real-time messaging with Socket.io, inventory management, automated rewards system, AWS S3 for invoice processing.  
[Live site](https://platform.heartofhouse.io/) | [Sign up](https://platform.heartofhouse.io/auth/sign-up)  
*Node.js, TypeScript, Express, MongoDB, Socket.io, AWS S3/EC2, PM2*

**[CrossPay](https://cross-payment-five.vercel.app/)**  
Cross-border remittance app. Send GBP, settle in USDC on Polygon. Stripe integration for fiat deposits, WebSocket real-time transaction updates, flat 0.5% fee.  
[Live site](https://cross-payment-five.vercel.app/) | [GitHub](https://github.com/dax-side/cross_payment)  
*Node.js, TypeScript, PostgreSQL, Stripe, Polygon Amoy, Socket.io, Pxxl*

**[CollabEdit](https://collab-edit-pink.vercel.app/)**  
Built a real-time collaborative editor with a custom RGA-based CRDT no Yjs, no Automerge. Tombstone retention keeps late-arriving ops from breaking, and a per-document operation queue fixes paste scrambling across clients.  
[Live site](https://collab-edit-pink.vercel.app/) | [GitHub](https://github.com/dax-side/collab_edit)  
*Node.js, TypeScript, PostgreSQL, WebSocket, Prisma, React, Vite*

**[Swiftmeal](https://github.com/Swiftmealng/Swiftmealng)**  
Full-stack food delivery platform with real-time order tracking, rider management, and payment processing.  
[Live site](https://swiftmeal-frontend-production.up.railway.app/) | [API Docs](https://swiftmealng-production.up.railway.app/api-docs/)  
*Node.js/TypeScript backend, React frontend, PostgreSQL, WebSocket, Paystack integration*

---

## Get in touch

<div align="center">
  <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60">
</div>

Open to backend developer roles and interesting projects.

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:damolaadegbite77@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/damola-adegbite)

<br/>

<img src="https://komarev.com/ghpvc/?username=dax-side&label=Profile%20views&color=0e75b6&style=for-the-badge" />
