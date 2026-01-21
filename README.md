About Me

I’m a Full-Stack Developer passionate about engineering solutions that handle complex data while preserving a seamless user experience.

Highlights

Built and delivered FastMeds — a healthcare inventory platform with Role-Based Access Control and secure data flows.

Built Chillr — a commercial event platform that handled high-volume traffic and boosted sales by 18% after release.

Strong fundamentals from MERN / Next.js to C++ and cryptographic protocols.

500+ algorithmic challenges solved — I use competitive programming to keep my problem-solving sharp.

Focus: building scalable, secure, and maintainable systems on cloud infrastructure.

Featured Projects
FastMeds — Healthcare Inventory Platform

Repo: ./fastmeds • Tech: Next.js, Node.js, MongoDB, RBAC, Redis, Docker, AWS
What it does

Secure inventory and order management for healthcare providers.

Role-based access control (Admin / Pharmacist / Viewer).

Real-time stock levels and low-stock alerts.

Impact

Improved stock accuracy and reduced out-of-stock incidents.

Designed for HIPAA-sensitive data flows (where applicable).

Quick highlights

Authentication & RBAC, fine-grained permissions.

Background jobs for batch reconciliation.

Dockerized, CI pipeline, AWS deployment example.

Chillr — Commercial Event Platform

Repo: ./chillr • Tech: React / Next.js, Express, PostgreSQL, Kubernetes (EKS/GKE), CDN, Load balancer
What it does

Event discovery, ticketing, and vendor dashboards.

Designed to handle bursty, high-volume traffic patterns.

Analytics dashboard for organizers.

Impact

Successfully handled large event spikes and reduced page latency.

Helped increase sales by ~18% through conversion optimization.

Quick highlights

Scalable architecture (Kubernetes + autoscaling).

Caching (CDN + in-memory caches) and graceful degradation under load.

A/B experimentation on checkout flow.

Skills & Technologies

Frontend

Next.js, React, TypeScript, HTML5, CSS3, TailwindCSS

Backend

Node.js, Express, REST & GraphQL, WebSockets

Systems & Languages

C++, algorithms & data structures, cryptography basics

Databases & Storage

PostgreSQL, MongoDB, Redis, S3

Cloud & DevOps

AWS (EC2, ECS/EKS, S3, RDS), Docker, Kubernetes, CI/CD

Security

Authentication, Role-Based Access Control (RBAC), secure key handling, TLS

Other

Testing (Jest, Mocha), Linting, Observability (Prometheus, Grafana), Monitoring & Logging

Open Source & Repositories (suggested structure)
/README.md                 # this file
/fastmeds/                 # production app (Next.js)
  /README.md               # run & deploy instructions
  /src
  /infra                   # IaC / deployment configs
/chillr/
  /README.md
  /src
/algorithms/               # competitive programming solutions (C++)
  /README.md
  /solutions
/scripts/                  # useful scripts & tools
/docs/                     # architecture diagrams, RFCs


Suggested README contents for each project

Project purpose & TL;DR

Architecture diagram (image)

Tech stack

Local setup (commands)

Run & test

Deployment notes

Roadmap & contribution guide

Competitive Programming

500+ algorithmic problems solved (practice across Codeforces / LeetCode / SPOJ / HackerRank).

Strengths: graph algorithms, number theory, advanced data structures, optimization.

Repositories idea: algorithms/graphs, algorithms/number-theory, algorithms/dp

How to Run / Get Started
Example: running a Next.js project (FastMeds)
# clone repo
git clone https://github.com/your-username/fastmeds.git
cd fastmeds

# install
npm install

# env (example)
cp .env.example .env
# edit .env (DB connection, AUTH secret, etc.)

# run locally
npm run dev
# build
npm run build
# start
npm run start

Example: running Chillr (backend)
cd chillr/server
npm install
# configure DB
# start server
npm run dev


(Include Docker / docker-compose instructions per project for easy local testing.)

What I’m Currently Working On

Harden cryptographic flows for user data protection.

Contributing tools & helper libraries to streamline deploying Next.js apps to Kubernetes.

Expanding my open source algorithms repo with well-documented C++ solutions.

Contact

LinkedIn: Your LinkedIn

Email: your.email@example.com

GitHub: github.com/your-username
