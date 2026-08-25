# Damola Adegbite

<div align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="400" alt="Coding Animation">
</div>

Backend & DevOps Engineer building with Node.js, TypeScript, and Go.

[Portfolio](https://damola.me/)

## Published npm packages

I build developer tools that cut down boilerplate.

**[@dax-side/jwt-abstraction](https://www.npmjs.com/package/@dax-side/jwt-abstraction)** - JWT auth in 3 lines  
Adds login tokens to an Express app in three lines instead of writing the auth flow from scratch. It manages access and refresh tokens, handles the middleware, and throws proper error types when something's wrong. Fully tested, running in three production apps.  
[Docs](https://dax-side.github.io/jwt-abstraction-site) | [npm](https://www.npmjs.com/package/@dax-side/jwt-abstraction) | [GitHub](https://github.com/dax-side/jwt-abstraction)

**[Express Journey Mapper](https://github.com/dax-side/express-journey-mapper)** - Auto-generate OpenAPI docs  
Scans an Express app's routes and writes the API documentation for you. No sitting down to hand-write a yaml file after every change.  
[npm](https://www.npmjs.com/package/express-journey-mapper)

**[error-telex](https://www.npmjs.com/package/error-telex)** - TypeScript error tracking SDK  
Catches errors in a TypeScript app and forwards them to a backend, with retries and filtering built in so you're not flooded with duplicate reports. Co-built during my HNG internship.  
[npm](https://www.npmjs.com/package/error-telex)

---

## What I work on

I build the systems behind an app: the APIs, the database, how users log in, how data updates in real time, and how the whole thing gets shipped and kept running.

**Recent work:**
- A B2B platform connecting liquor stores and vendors, currently live
- A deploy pipeline that checks the app is healthy before switching traffic to it, and rolls back automatically if it isn't
- A weather API that caches results so it isn't hitting the same forecast provider on every request

## Tech stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,typescript,javascript,python,go,nestjs,express,graphql,postgresql,mongodb,redis,prisma,docker,kubernetes,linux,nginx,aws" />
</div>

**Backend:** Node.js, TypeScript, Go, Express, NestJS, GraphQL (Apollo Server)  
**Databases:** PostgreSQL, MongoDB, Redis, Prisma ORM  
**devops:** Docker, Kubernetes (admission control), GitHub Actions, PM2, Nginx, AWS (EC2, RDS, S3, ECS, IAM, VPC, subnetting, internet gateways), Linux  
**Tools:** Git, Postman, MongoDB Compass, TablePlus, k6, Artillery

## Currently working on

- A command-line tool in Go that searches your files by name, even when you misspell what you're looking for. [local-file-search](https://github.com/dax-side/local-file-search)
- Running real deployments on Kubernetes and AWS, past what the [Boot.dev](https://www.boot.dev/u/dax-side) course covers

## Writing

I write about backend systems and building things that actually work.

- [How Would I Build a Payment System That Doesn't Lose Money](https://dev.to/dax-side/how-would-i-build-a-payment-system-that-doesnt-lose-money-16ap)
- [How Would I Build For Right Now](https://dev.to/dax-side/how-would-i-build-for-right-now-2fmm)
- [I built an MCP server that syncs GitHub into Notion and generates AI reports](https://dev.to/dax-side/i-built-an-mcp-server-that-syncs-github-into-notion-and-generates-ai-reports-5ao6)
- [I built a tool that shows developers what their backend costs the planet](https://dev.to/dax-side/i-built-a-tool-that-shows-developers-what-their-backend-costs-the-planet-jm1)

## Projects
**[CollabEdit](https://collab-edit-pink.vercel.app/)**  
A real-time editor where multiple people can type into the same document at once without overwriting each other. I built the conflict resolution myself instead of using an existing library like Yjs or Automerge. Deleted text sticks around as a hidden marker for a while so an edit that arrives late doesn't corrupt the document, and each document processes changes through its own queue so pasting text doesn't get scrambled across different people's screens.  
[Live site](https://collab-edit-pink.vercel.app/) | [GitHub](https://github.com/dax-side/collab_edit)  
Tech: Node.js, TypeScript, PostgreSQL, WebSocket, Prisma, React, Vite

**[CrossPay](https://cross-payment-five.vercel.app/)**  
Send money in GBP, and the person on the other end receives it as USDC on Polygon. Deposits come in through Stripe, transaction status updates live on screen instead of needing a refresh, and the fee is a flat 0.5%.  
[Live site](https://cross-payment-five.vercel.app/) | [GitHub](https://github.com/dax-side/cross_payment)  
Tech: Node.js, TypeScript, PostgreSQL, Stripe, Polygon Amoy, Socket.io, Pxxl


**[E-commerce Microservices API](https://github.com/dax-side/ecommerce-microservices-api)**  
Took an API from 48 requests a second to 716 by caching frequent lookups, reusing database connections instead of opening new ones each time, and adding proper indexes so queries stop scanning the whole table. Load tested at 200 concurrent users.  
Tech: Node.js, TypeScript, MongoDB, Redis, Docker, Nginx, Prometheus


---

## Get in touch

Open to backend and devops roles, and interesting projects.

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:damolaadegbite77@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/damola-adegbite)

<br/>

<img src="https://komarev.com/ghpvc/?username=dax-side&label=Profile%20views&color=0e75b6&style=for-the-badge" />
