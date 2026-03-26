# Hi, I'm Oded 👋

AWS & Distributed Systems Architect focused on event-driven systems, high-scale telemetry and IoT pipelines, and pragmatic engineering tradeoffs (scalability, failure modes, observability, and cost).

I enjoy building practical tooling and exploring how systems behave under real-world load, concurrency, and failure scenarios.

## Focus Areas

- Event-Driven Architectures (EDA)
- AWS IoT platforms and telemetry pipelines
- Serverless performance & cost optimization
- Distributed system reliability and observability

## Architecture Interests

- Distributed systems design
- System behavior under load and concurrency
- Observability and production diagnostics
- Performance engineering and reproducible load testing
- Failure-mode analysis in cloud systems

## Open Source Projects

Most of my public projects focus on **practical tooling for testing, investigating, and operating distributed systems in AWS environments**.

### [AWS Incident Investigator](https://github.com/kerenoded/aws-incident-investigator)

AWS-native incident investigation workflow built around **deterministic workers and bounded AI**.  
Uses Step Functions to orchestrate evidence collection across metrics, logs, and traces, while GenAI serves as an advisory layer to compare competing hypotheses, interpret cross-source evidence, and surface missing evidence.

### [AWS Fargate Workload Runner](https://github.com/kerenoded/aws-fargate-workload-runner)

Generic AWS workload generator built on **ECS Fargate** with pluggable scenarios (IoT, SQS).  
Designed for controlled load generation and analysis of system behavior under stress.

### [k6 Fargate Runner](https://github.com/kerenoded/k6-fargate-runner)

Repeatable **k6 load testing framework running on ECS Fargate**, generating traffic from a consistent cloud environment instead of developer laptops.

## Currently Exploring

- Load generation and reproducible performance testing environments
- System behavior under high concurrency and burst traffic
- Event-driven system reliability patterns

## Writing

### Featured articles (long-form)

- **[When a few noisy devices took down the system: lessons from a production investigation](https://www.linkedin.com/pulse/when-few-noisy-devices-took-down-system-lessons-from-production-oded-lomnf)**  
  A production incident investigation from an IoT canary OTA rollout that exposed how a small subset of noisy devices, hot database paths, app-triggered follow-up API calls, and retry behavior combined into system-wide contention.

- **[Turning Noisy AWS IoT Presence (connect/disconnect events) into Reliable Connectivity State](https://www.linkedin.com/pulse/turning-noisy-aws-iot-presence-connectdisconnect-events-oded-keren-qwegf)**  
  How to turn noisy IoT connect/disconnect streams into a bounded, reliable connectivity signal using rate limiting, back-pressure, and derived state instead of treating raw presence events as truth.

- **[How do you find the cost vs performance sweet spot of an AWS Lambda function?](https://www.linkedin.com/pulse/how-do-you-find-cost-vs-performance-sweet-spot-aws-lambda-oded-keren-gy4ef/)**  
  Exploring Lambda memory tuning impact on cost and latency, validated with AWS Lambda Power Tuning and controlled load tests.

- **[AWS IoT Services Deprecation: From Managed Pipelines to Modular Cloud Architectures](https://www.linkedin.com/pulse/aws-iot-services-deprecation-from-managed-pipelines-modular-keren-wqipf/)**  
  What the retirement of IoT Analytics and IoT Events signals about AWS’s direction for modern IoT architectures.

### Selected posts

#### Serverless / performance / cost

- **[Practical takeaways for reducing AWS Lambda cost](https://www.linkedin.com/posts/activity-7434115313325178880-duuB)**
- **[Going beyond Power Tuning: validating cost vs latency with controlled load tests (k6 on Fargate)](https://www.linkedin.com/posts/activity-7432464564836810752-iqHD)**
- **[How did we reduce AWS cloud costs by ~50%? Practical actions + tools](https://www.linkedin.com/posts/activity-7421489407251263490-cNgA)**

#### Architecture / networking / cost tradeoffs

- **[Private subnet connectivity: NAT vs Gateway Endpoint vs Interface Endpoint](https://www.linkedin.com/posts/activity-7436791678566391808-r5na)**

#### Observability / production readiness

- **[Most production incidents aren’t hard to fix — they’re hard to understand fast enough](https://www.linkedin.com/posts/activity-7425935295059099648-d8Zr)**  
  A monitoring maturity journey and lessons from improving incident response.


#### IoT / event-driven architecture

- **[Sometimes the best architecture improvement is removing an unnecessary path](https://www.linkedin.com/posts/activity-7441138163894534144-48j9?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAC_jasBvYjJFSEkCUOVkgkV0WULfzpgaE4)**  
  Simplifying a production IoT progress-update flow by replacing a heavier event-processing path with a direct IoT Rule → Device Shadow pattern, reducing latency, cost, and operational complexity.

- **[Load-test your EDA system without permanent infrastructure](https://www.linkedin.com/feed/update/urn:li:activity:7435209996797173760/)**

- **[Golden AWS IoT insights for reliability, scale, and cost-efficiency](https://www.linkedin.com/posts/activity-7416916197604220929-pNAr)**


#### Cloud strategy / delivery

- **[Migrating on-prem to AWS is a maturity journey](https://www.linkedin.com/posts/activity-7418966138795118592-8O6f)**  
  Business goals first, cloud as leverage.

- **[Analysis paralysis vs bias for action](https://www.linkedin.com/posts/activity-7423606103550345216-L-j-)**

#### Notes from the field

- **[Amazon AgentCore: production AI agents at scale (AWS Israel event takeaways)](https://www.linkedin.com/posts/activity-7428775902294986752-530e)**

## Connect

- **[LinkedIn](https://www.linkedin.com/in/odedkeren/)**