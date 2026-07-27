# Hi, I'm Miriam 👋🏾

**Senior Platform & DevSecOps Engineer** building secure, observable and boringly reliable cloud-native platforms.

I work across Kubernetes, infrastructure as code, secure delivery, developer platforms and production operations, with a strong focus on making systems understandable, repeatable and safe to run.

I like building things that don't just work on a laptop, but can be **explained, tested, deployed, monitored, secured and handed over** without everyone needing to form a prayer circle around the terminal. 🙏🏾💻

> **The dream is boring production. The drama can stay in the group chat.** 😌

---

## 👩🏾‍💻 What I Do

My work sits across **Platform Engineering, DevSecOps and Cloud Engineering**, particularly:

* ☸️ Kubernetes platforms and containerised workloads
* 🔐 DevSecOps, secure delivery and policy-as-code
* 🧱 Infrastructure as Code and reusable platform components
* 🚀 CI/CD, GitOps and deployment automation
* 🌩️ Cloud infrastructure across AWS, Azure and GCP
* 📈 Observability, logging, metrics and distributed tracing
* 🧰 Developer experience and internal platform tooling
* 🧯 Production readiness, resilience and operational maturity

I care about systems that are:

```text
secure
observable
testable
documented
maintainable
automated
boringly reliable
```

Tools matter.

Engineering judgement matters more.

---

## 🏗️ Flagship Engineering Project: bfstore

### Borough Furniture Store

[**bfstore**](https://github.com/mantrobuslawal/bfstore) is a production-shaped cloud-native engineering case study built around a fictional ecommerce company selling developer-themed furniture and homeware.

Yes, this means there are Gopher cushions. Obviously. 🐹

The shop is fictional. The engineering problems aren't.

I'm using bfstore to demonstrate how I approach an end-to-end system across:

* application and service architecture
* API and event contracts
* data ownership and service boundaries
* Kubernetes and platform engineering
* infrastructure and cloud foundations
* CI/CD and GitOps
* DevSecOps and software supply-chain controls
* observability and production operations
* resilience and failure handling
* developer experience
* architecture decisions and technical documentation

The goal isn't simply to build an application.

It's to make the engineering thinking visible: **the decisions, trade-offs, constraints and operational consequences behind the code.**

Detailed architecture, implementation notes and design decisions live in the project repositories and on [Cloud Sandbox](https://cloud.doublewords.net/).

---

## 🗺️ The bfstore Engineering Ecosystem

bfstore is deliberately split across repositories that reflect different engineering responsibilities.

| Repository                                                                                       | Focus                                                                  |
| ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- |
| [**bfstore**](https://github.com/mantrobuslawal/bfstore)                                         | Application architecture, services, contracts and domain design        |
| [**bfstore-platform-infra**](https://github.com/mantrobuslawal/bfstore-platform-infra)           | Cloud foundations, Kubernetes infrastructure and platform provisioning |
| [**bfstore-platform-gitops**](https://github.com/mantrobuslawal/bfstore-platform-gitops)         | GitOps configuration, environments and application delivery            |
| [**bfstore-security-governance**](https://github.com/mantrobuslawal/bfstore-security-governance) | DevSecOps, policy-as-code and software supply-chain controls           |
| [**bfstore-iac-modules**](https://github.com/mantrobuslawal/bfstore-iac-modules)                 | Reusable Infrastructure as Code modules                                |
| [**bfstore-developer-platform**](https://github.com/mantrobuslawal/bfstore-developer-platform)   | Developer experience, golden paths and platform tooling                |

The separation is intentional.

Application code, cloud foundations, deployment state, security policy and developer-platform concerns have different responsibilities, ownership boundaries and lifecycles.

I want the repository structure to reflect that rather than putting the entire universe into one enormous `platform-stuff` directory and hoping for the best.

---

## 🧰 Core Engineering Toolkit

I work with a broad cloud-native stack, but these are some of the technologies that show up regularly in my work and projects.

**Platform & Cloud**
`Kubernetes` · `Linux` · `Docker` · `AWS` · `Azure` · `GCP`

**Infrastructure & Delivery**
`Terraform / OpenTofu` · `GitHub Actions` · `GitOps` · `Ansible`

**Applications & Data**
`Go` · `gRPC` · `Protobuf` · `Kafka` · `MySQL`

**Observability & Operations**
`OpenTelemetry` · `Prometheus` · `Grafana`

I prefer choosing technology because it solves a concrete problem, not because somebody drew it on a CNCF landscape and I got excited.

Although, admittedly, that has happened.

---

## 📚 How I Approach Engineering

I like to understand the system before I start throwing YAML at it.

That usually means thinking through:

```text
requirements
service boundaries
data ownership
API and event contracts
failure modes
security boundaries
testing strategy
deployment model
observability
operational ownership
```

Then I build.

That might sound formal, but it prevents surprise architecture from appearing halfway through a project wearing a fake moustache. 🥸

I'm particularly interested in the questions that appear **between** technologies:

* Who owns this data?
* What happens when this dependency fails?
* Where does this request go?
* How is this service authenticated?
* What happens during a partial failure?
* Can we deploy this safely?
* Can someone other than the person who built it operate it?
* What evidence tells us the system is healthy?
* Who gets paged at 2am, and will the logs actually help them?

`kubectl apply -f vibes.yaml` is not an operating model.

---

## 🧪 Engineering Principles

I value:

* clear ownership and boundaries
* secure defaults
* useful documentation
* honest engineering trade-offs
* observable systems
* repeatable automation
* testing beyond the happy path
* practical architecture
* production readiness

I'm considerably less enthusiastic about:

* mystery YAML
* shared databases wearing microservice costumes
* deployment scripts nobody has tested
* logs that say `something went wrong`
* dashboards nobody understands
* "temporary" hacks with permanent residency

Complexity sometimes earns its place.

It should still have to explain itself.

---

## 🔬 Areas I'm Going Deeper Into

Engineering doesn't have a finished state, so I deliberately keep strengthening the fundamentals underneath the tools I use.

Current rabbit holes include:

* ☸️ Kubernetes internals and platform architecture
* 🌐 Linux networking and container networking
* 🔐 Kubernetes security and policy-as-code
* 📈 OpenTelemetry and distributed systems observability
* 🛡️ software supply-chain security

I'm interested in understanding **why systems behave the way they do**, not just memorising the command that makes the error disappear.

---

## ✍🏾 Cloud Sandbox

I write longer-form technical notes and document the engineering behind bfstore at:

### [cloud.doublewords.net](https://cloud.doublewords.net/)

**Cloud Sandbox** is my technical field journal for platform engineering, DevSecOps, Kubernetes, cloud infrastructure and production-shaped software design.

It's where I have more room to explain the decisions that don't fit neatly into a commit message.

---

## 📫 Connect

I'm always happy to talk about:

**Platform Engineering · DevSecOps · Kubernetes · Cloud Infrastructure · Secure Delivery · Developer Platforms · Observability · Senior Contract Engineering**

🌐 [Cloud Sandbox](https://cloud.doublewords.net/)
💼 [LinkedIn](https://www.linkedin.com/in/mariam-antrobus-dev/)
🐙 [GitHub](https://github.com/mantrobuslawal)
✉️ [Contact](https://cloud.doublewords.net/contact/)

---

## 🐹 Current Motto

> **Build it properly.**
> **Document the trade-offs.**
> **Make the logs useful.**
> **Keep the Gopher stylish.**
