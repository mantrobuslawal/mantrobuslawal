# Hi, I'm Miriam 👋🏾

**Platform & DevSecOps Engineer** building secure, observable cloud-native platforms with Kubernetes, Go, Terraform, CI/CD, and production-grade automation.

I’m focused on building the kind of systems that do not just work on a laptop, but can be explained, tested, deployed, monitored, secured, and handed over without everyone needing to form a prayer circle around the terminal. 🙏🏾💻

---

## 👩🏾‍💻 What I’m About

I’m building towards senior Platform Engineering, DevSecOps, Kubernetes Platform Engineering, and Cloud Engineering contract roles.

My work focuses on:

- ☸️ Kubernetes platform engineering
- 🔐 DevSecOps and secure delivery
- 🌩️ Multi-cloud infrastructure and automation across AWS, GCP, and Azure
- 🧱 Infrastructure as Code
- ⚡ Serverless and Function as a Service patterns
- 🚀 CI/CD pipelines
- 📈 Observability, logging, tracing, and metrics
- 🧪 Testing strategy for distributed systems
- 🧰 Developer experience and internal platform tooling
- 🧯 Production readiness, resilience, and operational maturity

I care about building systems that are:

```text
secure
observable
testable
documented
maintainable
automated
boringly reliable
```

The dream is boring production. The drama can stay in the group chat. 😌

---

## 🏗️ Current Flagship Project: bfstore

### Borough Furniture Store

**bfstore** stands for **Borough Furniture Store**.

Borough Furniture Store is a fictional cloud-native ecommerce platform for developer-themed furniture and homeware.

The backstory: Borough started out selling speciality Golang-themed homeware to Go enthusiasts — because obviously every engineer needs a tasteful Gopher cushion. 🐹✨

It then expanded into programming-language mascot-themed and computer-science-inspired homeware.

Example products include:

- 🐹 Gopher desk lamps
- 🛋️ Gopher cushion sets
- 🧵 Rob Pike wall tapestries
- 🔐 Rivest super-secure lockboxes
- 🧭 Dijkstra pathfinding rugs
- 🐍 Python plush beanbags
- 🦀 Rust crab coat hooks
- ☸️ Kubernetes helm bookends
- 🕰️ Turing machine wall clocks
- 🐞 Grace Hopper debugging blankets

Because nothing says “distributed systems engineer” like a well-observed microservice and a cryptography-themed lockbox in the hallway.

---

## 🧠 What bfstore Demonstrates

bfstore is designed as a serious portfolio project wrapped in a memorable product story.

It demonstrates:

- 🧩 Microservice architecture
- 📜 Architecture Decision Records
- 📡 gRPC service communication
- 📨 Kafka event-driven design
- 🐬 MySQL service-owned databases
- 🔎 Search and denormalised projections
- 📦 Contract-first Protobuf design
- 🧪 Unit, integration, contract, and end-to-end testing
- 📊 OpenTelemetry-based observability
- 🛡️ Secure service design
- ☸️ Kubernetes deployment thinking
- 🏗️ Infrastructure and platform engineering practices
- 🧯 Resilience, retries, idempotency, and DLQ strategy
- 📚 Client-facing documentation

The goal is not just to build an app.

The goal is to show how I think through architecture, trade-offs, delivery, operations, and reliability.

---

## 🛒 bfstore Architecture Snapshot

The first implementation focuses on a complete checkout vertical slice:

```text
Browse product
→ Add product to basket
→ Checkout
→ Reserve stock
→ Authorise payment
→ Create shipment
→ Create order
→ Publish OrderCreated
→ Send notification
```

Core services include:

```text
api-gateway
catalog-service
basket-service
inventory-service
order-service
payment-service
shipping-service
notification-service
search-service
recommendation-service
review-service
auth-service
customer-service
```

Communication model:

```text
gRPC = commands and queries that need an immediate response
Kafka = facts that have already happened
```

Examples:

```text
ReserveStock is a gRPC command.
StockReserved is a Kafka event.

AuthorisePayment is a gRPC command.
PaymentAuthorised is a Kafka event.

CreateOrder is a gRPC command.
OrderCreated is a Kafka event.
```

---

## 🧺 Product Catalogue Design

Borough Furniture Store sells varied products, so the catalogue needs to support different product types without becoming a cursed spreadsheet with 400 nullable columns. 😭

Examples:

```text
curtains need drop, width, lining, heading type
bed frames need bed size, frame material, storage type
rugs need shape, pile height, weave, material
lamps need bulb type, wattage, fitting type
lockboxes need lock type, security rating, dimensions
```

The design uses:

```text
Catalogue Service = governed product source of truth
MySQL = relational core catalogue data
category-scoped attributes = flexible product characteristics
Search Service = denormalised browse/search projection
```

This separates:

```text
product governance from search performance
source of truth from projection
write model from read model
```

And most importantly:

```text
No giant product table of doom.
No mystery JSON blob apocalypse.
```

---

## 🧰 Technologies I’m Working With

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Platform & Cloud

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=for-the-badge&logo=serverless&logoColor=white)
![Function as a Service](https://img.shields.io/badge/Function_as_a_Service-6C63FF?style=for-the-badge)

### Infrastructure & Delivery

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

### Backend & Data

![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protocol_Buffers-4285F4?style=for-the-badge)

### Observability & Security

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## 🧭 What I’m Currently Learning Deeply

I’m currently strengthening my skills in:

- ☸️ Kubernetes internals and platform engineering
- 🔐 Kubernetes security and policy-as-code
- 🌐 Linux networking for containers and cloud
- ⚡ Serverless and Function as a Service across cloud providers
- 🧱 Terraform module design
- 📡 gRPC and Protobuf service design
- 📨 Kafka event-driven architecture
- 📈 Observability with OpenTelemetry
- 🧪 Performance, stress, soak, and resilience testing
- 🛡️ Supply chain security and secure CI/CD

I like understanding systems from the ground up.

Not just:

```text
kubectl apply -f vibes.yaml
```

but:

```text
why did this break,
where did the packet go,
what owns this data,
what happens when this dependency fails,
and who is getting paged at 2am?
```

---

## 📚 How I Work

I like to start with:

```text
requirements
service boundaries
data ownership
API contracts
event contracts
database design
testing strategy
deployment model
operational runbooks
```

Then I build.

That may sound formal, but it prevents “surprise architecture” from appearing halfway through the project wearing a fake moustache. 🥸

---

## 🧪 Engineering Values

I value:

- Clear service ownership
- Good documentation
- Honest trade-offs
- Secure defaults
- Repeatable automation
- Observable systems
- Testing beyond the happy path
- Practical architecture
- Small vertical slices
- Production readiness

I do not value:

- Mystery YAML
- Shared databases pretending to be microservices
- Untested deployment scripts
- Logs that say `something went wrong`
- Dashboards nobody understands
- “Temporary” hacks with permanent residency

---

## 🛠️ Featured Project Roadmap

For bfstore, I’m working through stages:

### Stage 1 — Documentation and Architecture ✅

- Requirements
- Service boundaries
- Domain model
- ADRs
- API design
- Event design
- Data ownership
- Testing strategy

### Stage 2 — Contract Foundation 🚧

- Buf configuration
- Protobuf contracts
- gRPC service definitions
- Shared common messages
- API versioning

### Stage 3 — Local Development Platform 🚧

- Docker Compose
- MySQL
- Kafka
- Service skeletons
- Makefile workflow
- Local seed data

### Stage 4 — First Vertical Slice 🚧

- Product listing
- Basket management
- Checkout
- Stock reservation
- Payment authorisation
- Shipment creation
- Order creation
- Notification event consumption

### Stage 5 — Platform Engineering Evidence 🔜

- Kubernetes manifests
- GitOps structure
- CI/CD pipelines
- Observability stack
- Security controls
- Resilience testing
- Runbooks

---

## 🌱 A Little Personality

I like systems that are:

```text
well documented
well tested
well observed
and not held together by one shell script named final-final-real-prod.sh
```

I’m building this portfolio carefully because I want my work to show:

```text
technical depth
clarity of thought
engineering judgement
client-readiness
and a small amount of chaos-neutralising humour
```

---

## 📫 Connect

I’m open to conversations around:

- Platform Engineering
- DevSecOps
- Kubernetes
- Cloud Infrastructure
- Serverless and Function as a Service
- Microservices
- Secure Delivery
- Observability
- Contractor-focused engineering portfolios

---

## 🐹 Current Motto

> Build it properly.  
> Document the trade-offs.  
> Make the logs useful.  
> Keep the Gopher stylish.  

