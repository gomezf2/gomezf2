## Hi there 👋
# Francis Gomez

**Platform & DevOps Engineer in the making — London, UK**

I found my way into platform engineering through a genuine love of Linux, automation, and the satisfaction of understanding how systems actually work. I installed Pop OS on my university laptop because I got tired of Windows, started learning CI/CD pipelines, and never looked back.

---

## What I'm building

### [ci-pipeline-demo](https://github.com/gomezf2/ci-pipeline-demo)
A multi-stage CI/CD pipeline built with GitHub Actions and Docker. Four discrete jobs: lint, test, security scan, build and push — ordered by cost so the cheapest checks run first and failures are immediately attributable. Trivy hard-fails on CRITICAL and HIGH vulnerabilities before anything reaches the registry.

The commit history reflects the real development process, including the debugging and iterations, because that's the part I actually enjoy.

---

## Stack

```
Linux · Docker · GitHub Actions · GHCR · Trivy · GCP · Python · Git
```

---

## Currently learning

- AWS Cloud Practitioner (in progress)
- Terraform
- Azure (AZ-900 on the roadmap)

---

## What's next for the pipeline

- Multi-stage Docker builds to reduce image size and shrink the Trivy scan surface
- A deployment stage to close the CD loop beyond build and push
- Infrastructure as Code with Terraform to provision the target environment

---

*Open to junior Platform Engineer, DevOps Engineer, and Cloud Engineer roles in London.*
<!--
**gomezf2/gomezf2** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
