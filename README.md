<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5f,100:0f172a&height=140&section=header&text=&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=2800&pause=1200&color=38BDF8&center=true&vCenter=true&width=960&lines=Swastik+Gupta;Software+%26+Full+Stack+Developer;Cloud+%26+AWS+Enthusiast;Competitive+Programmer+%7C+Tech+Mentor" alt="Typing SVG" />

<br/>

<p>
  <img src="https://img.shields.io/badge/B.Tech_IT-KIET_Group_of_Institutions-0EA5E9?style=flat-square&logo=graduation-cap&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/CGPA-9.03_/_10-10B981?style=flat-square"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Ghaziabad,_India-6366F1?style=flat-square&logo=googlemaps&logoColor=white"/>
</p>

<p>
  <a href="https://linkedin.com/in/swastikg" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:swastikgupta403@gmail.com">
    <img src="https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/swastkkk" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<img src="https://img.shields.io/github/followers/swastkkk?style=flat-square&color=6366F1&label=Followers"/>
&nbsp;
<img src="https://img.shields.io/github/stars/swastkkk?style=flat-square&color=38BDF8&label=Stars"/>

</div>

<br/>

---

## About

I'm a **Software Engineer** in the making, currently pursuing a B.Tech in Information Technology at KIET Group of Institutions, Ghaziabad — holding a **9.03 CGPA**.

I like building things that have to survive real load: concurrent key-value stores, event-driven pipelines processing thousands of events per minute, and cloud-native systems on AWS designed with cost and scale in mind. My work spans distributed systems fundamentals (consistent hashing, thread-safe caching, concurrency) and production cloud engineering (Kinesis, Lambda, Athena, serverless architectures).

I back this up with **300+ solved DSA & CP problems** across LeetCode and CodeChef, and I mentor 20+ students in DSA and full-stack web development as part of my community work with Google Developers Group.

**Open to:** Software Engineering Internships · Backend / Distributed Systems Roles · Cloud & AWS Engineering Roles

---

## Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=java,python,cpp,c,javascript&theme=dark"/>
</p>

### Web Technologies

<p>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb&theme=dark"/>
</p>

### Cloud & DevOps

<p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,docker,git,github,linux&theme=dark"/>
</p>

### Tools

<p>
  <img src="https://skillicons.dev/icons?i=vscode,postman&theme=dark"/>
</p>

---

## Core Expertise

| Domain | Focus Areas |
|---|---|
| **Data Structures & Algorithms** | Graphs (BFS/DFS, Dijkstra), Trees, DP, Heaps, Segment Trees, Binary Search, Sliding Window |
| **Web Development** | React, Node.js, Express.js, MongoDB, REST APIs — MERN Stack |
| **Cloud & AWS** | EC2, S3, Lambda, Kinesis, Athena, API Gateway, CloudFormation, IAM, VPC |
| **SQL** | Joins, CTEs, Window Functions, Subqueries |
| **Distributed Systems** | Concurrency, multi-threading, synchronization, consistent hashing, event-driven architecture |
| **System Design** | OOP, cloud-native deployment, architecture documentation |

---

## Featured Projects

<details>
<summary><b>Distributed Key-Value Store — In-Memory Store with Consistent Hashing</b></summary>

<br/>

> Distributed, thread-safe in-memory KV store built in Java, designed to handle high-concurrency read/write workloads.

| Attribute | Detail |
|---|---|
| **Stack** | Java · Concurrency · Consistent Hashing |
| **Scale** | 10K+ concurrent read/write operations |
| **Performance** | 40% lower p99 read latency vs. single-threaded baseline |
| **Cache Efficiency** | 35% reduction in cache miss rate under 50K req/min simulated load |
| **Repository** | [github.com/swastkkk/Distributed-Key-Value-Store](https://github.com/swastkkk/Distributed-Key-Value-Store) |

**What it does:** Implements a consistent hashing ring with virtual nodes for even key distribution, `ReentrantReadWriteLock` for thread-safe synchronization, and an O(1) LRU eviction cache (doubly linked list + HashMap). Uses a thread-pool executor for non-blocking TCP request handling, benchmarked with a custom latency profiler and documented with full architecture and data-flow diagrams.

</details>

<details>
<summary><b>Real-Time Stock Alert Engine — Event-Driven Price Monitoring System</b></summary>

<br/>

> Large-scale event-processing system for real-time stock price alerts, built with heaps and graph algorithms.

| Attribute | Detail |
|---|---|
| **Stack** | Python · React · GCP Cloud Run · Heaps · Graphs |
| **Scale** | 5K+ real-time price events/min across 200+ tickers |
| **Accuracy** | 28% reduction in false alert rate |
| **Deployment** | GCP Cloud Run with auto-scaling |
| **Repository** | [github.com/swastkkk/Real-Time-Stock-Alert-Engine](https://github.com/swastkkk/Real-Time-Stock-Alert-Engine) |

**What it does:** Uses a min-heap priority queue for O(log n) threshold detection and BFS-based ticker-correlation graphs to track relationships across tickers. Applies sliding-window moving averages for signal smoothing and binary search for O(log n) historical price lookups, deployed with cloud-native, event-driven architecture principles.

</details>

<details>
<summary><b>Real-Time E-Commerce Analytics Pipeline — Serverless AWS Data Pipeline</b></summary>

<br/>

> Production-style serverless, event-driven analytics pipeline built entirely on core AWS services.

| Attribute | Detail |
|---|---|
| **Stack** | AWS Kinesis · Lambda · S3 · Athena · IAM · AWS CLI |
| **Architecture** | Kinesis (ingestion) → Lambda (processing) → S3 (data lake) → Athena (SQL analytics) |
| **Write-up** | Documented on Medium with full architecture diagrams |
| **Cost Awareness** | Infrastructure decommissioned post-completion to optimize AWS spend |
| **Medium Blog** | [https://medium.com/@_swastikg/Real-time-e-commerce-analytics-pipeline-on-aws](https://medium.com/@_swastikg/building-a-real-time-e-commerce-analytics-pipeline-on-aws-20bcc2bc49ab?sharedUserId=_swastikg) |

**What it does:** Ingests high-throughput e-commerce events via Kinesis Data Streams, processes and validates them with Lambda into clean JSON stored in an S3 data lake, and enables serverless SQL analytics through Athena — delivering product-category and device-wise behavior insights with zero database management overhead. AWS CLI was used to simulate production-level event ingestion; API Gateway integration, S3 date-partitioning, and QuickSight visualization are proposed next steps.

</details>

<details>
<summary><b>Click2Biz — Full-Stack Business Platform</b></summary>

<br/>

> Live, production MERN-stack platform for small businesses, co-founded and built end-to-end.

| Attribute | Detail |
|---|---|
| **Stack** | MERN (MongoDB, Express.js, React, Node.js) · REST APIs · Cloud Deployment |
| **Live URL** | [click2biz.in](https://click2biz.in) |
| **Status** | Actively serving real customers |
| **Repository** | https://github.com/aviralMadhvan24/Click2Biz |

**What it does:** A service-oriented RESTful backend built with Node.js, Express.js, MongoDB, and Mongoose ODM, covering the full lifecycle from requirements gathering to cloud deployment. Includes environment configuration, deployment pipeline management, and infrastructure troubleshooting — with features iterated directly from real customer feedback.

</details>

---

## Leadership & Community

### Tech Mentor & Event Organiser — Google Developers Group & Kinesis Technical Society
`Sep 2024 – Present` · KIET Group of Institutions, Ghaziabad

- Mentored 20+ students in DSA (Java) and Web Development (React, Node.js), structuring algorithmic learning paths aligned with competitive programming practice and guiding capstone group projects
- Core organising team member for **Dataverse**, a national-level hackathon with 400+ participating teams — coordinated large-scale logistics and communication

---

## Certifications

<div align="center">

**Amazon Web Services**

[![AWS Cloud Practitioner](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/ecc89c9d-8af7-4644-8afe-2efb07198492/public_url)
&nbsp;
[![AWS AI Practitioner](https://img.shields.io/badge/AWS-AI_Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/fd462a27-0b74-4651-be3d-93bf6017be8c/public_url)
&nbsp;
[![AWS CloudOps Engineer](https://img.shields.io/badge/AWS-CloudOps_Engineer-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/be9f18a9-8bae-4c77-924e-40483e562fb0/public_url)
&nbsp;
[![AWS Data Engineer](https://img.shields.io/badge/AWS-Data_Engineer-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/6307ebce-3b5e-42fe-9cd0-22cad989795b/public_url)

<br/>

**Google Cloud**

[![Google Cloud Study Jams](https://img.shields.io/badge/Google_Cloud-Study_Jams-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://www.skills.google/public_profiles/46848622-f0a5-4359-a6ab-fb86271c2343)

</div>

---

## Competitive Programming

<div align="center">

<a href="https://leetcode.com/u/swastikkk/" target="_blank">
  <img src="https://img.shields.io/badge/LeetCode-Max_Rating_1490-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>
&nbsp;
<a href="https://codechef.com/users/swastikkkk" target="_blank">
  <img src="https://img.shields.io/badge/CodeChef-Max_Rating_1296-5B4638?style=for-the-badge&logo=codechef&logoColor=white"/>
</a>

</div>

<div align="center">

**300+ DSA & CP problems solved** across LeetCode and CodeChef

Core strengths: Graphs · Trees · Dynamic Programming · Heaps · Segment Trees · Hash Maps · Two Pointers · Sliding Window · Binary Search · SQL (Joins, CTEs, Window Functions, Subqueries)

</div>

---

## GitHub Analytics

<div align="center">

<a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=swastkkk&theme=dark" alt="GitHub Streak" /></a>

&nbsp;
</div>

## Contribution Activity

<div align="center">

[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=swastkkk&bg_color=000000&color=8b949e&line=26a641&point=8b949e&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## Current Focus

```yaml
Learning:
  - Data Structures & Algorithm
  - Distributed Systems & Consensus Algorithms
  - Advanced System Design
  - Cloud Engineering on AWS (Athena, Kinesis, Lambda)
 

Building:
  - Production-grade distributed systems in Java
  - Serverless, event-driven data pipelines on AWS
  - Full-stack platforms serving real users

Exploring:
  - Consistent hashing & consensus protocols (Raft, Paxos)
  - Large-scale event-driven architectures
  - AWS ecosystem depth (VPC design, cost optimization, IAM)

Open To:
  - Software Engineering Internships
  - Backend / Distributed Systems roles
  - Cloud & AWS Engineering roles
```

---

## Connect

<div align="center">

<a href="mailto:swastikgupta403@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-swastikgupta403@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/swastikg" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Swastik_Gupta-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/swastkkk" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-swastkkk-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
&nbsp;
<a href="https://click2biz.in" target="_blank">
  <img src="https://img.shields.io/badge/Live_Project-Click2Biz-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

</div>

<br/>

<div align="center">

*Building resilient systems at the intersection of distributed computing, cloud infrastructure, and full-stack engineering.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a5f,100:0f172a&height=120&section=footer" width="100%"/>

</div>
