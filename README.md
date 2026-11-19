
# DevOps Engineering Portfolio

A collection of hands-on projects focused on cloud infrastructure, Linux administration, application deployment, automation, CI/CD, containerisation, and infrastructure management.

This portfolio documents practical implementations, technical decisions, troubleshooting experiences, and lessons learned while developing my DevOps and cloud engineering capabilities.

## Projects

| Project | Technologies | Implementation | Repository |
|---|---|---|---|
| **Cloud Infrastructure & Java Application Deployment** | DigitalOcean, Ubuntu, Linux, SSH, Java, Gradle, SCP, Spring Boot | Provisioned an Ubuntu cloud server, configured SSH authentication and Linux user permissions, built and deployed a Java application, configured firewall access, and verified successful deployment. | [View Project](https://github.com/ChiomaScripts/Dev5-cloud-iaas) |
| **Artifact Repository Management & Java Artifact Publishing with Nexus** | DigitalOcean, Ubuntu, Nexus Repository Manager, Linux, Java, Gradle, Maven | Installed and configured Nexus on a cloud server, troubleshot resource limitations, implemented service and repository-level access controls, and published Java artifacts using Gradle and Maven. | [View Project](https://github.com/ChiomaScripts/Dev6-nexus-artifact-repository) |
| **Docker for Local Development — Python Girls That Code** | Docker, Python, FastAPI, MongoDB, Mongo Express, Docker Networking, WSL 2 | Developed and containerised a Python profile management application with CRUD functionality, built a custom Docker image, connected three containers through a user-defined Docker network, configured environment-based database connectivity, and verified application deployment and data persistence across services. | [View Project](https://github.com/ChiomaScripts/Dev7a-docker-python) |
| **Private Docker Registry with Sonatype Nexus** | Docker, Docker Desktop, Sonatype Nexus, DigitalOcean, Ubuntu, Linux, Docker Registry, Image Tagging, Registry Authentication | Provisioned and configured a private Docker hosted repository on a DigitalOcean Ubuntu server, implemented Docker registry authentication and publishing permissions, tagged and published an existing FastAPI application image, investigated repeated Docker push timeouts using Linux diagnostics and Nexus logs, and verified successful image publication through the registry digest and Nexus repository browser. | [View Project](https://github.com/ChiomaScripts/Dev7b-docker-nexus-registry) |
| **Docker Compose, Service Networking & Persistent MongoDB Data** | Docker Compose, Docker, Python, FastAPI, MongoDB, Mongo Express, Docker Volumes, Container Networking, Sonatype Nexus, Health Checks, Environment Variables | Orchestrated the existing Python Girls That Code FastAPI image from a private Nexus registry alongside MongoDB and Mongo Express using a declarative Docker Compose configuration. Implemented service-name-based networking, environment-file configuration, health-aware startup dependencies, container restart policies and persistent MongoDB storage using a Docker-managed named volume. Validated the three-service deployment and verified database persistence across container teardown and recreation. | [View Project](https://github.com/ChiomaScripts/Dev7c-docker-compose-volumes) |
| **Containerised Nexus Deployment on DigitalOcean** | DigitalOcean, Ubuntu, Docker Engine, Sonatype Nexus, Linux, SSH, Docker Volumes, Container Networking, Port Publishing | Deployed Sonatype Nexus Repository Manager as a Docker container on a DigitalOcean Ubuntu server, configured persistent Docker-managed storage, managed container lifecycle and host-to-container networking, and verified access to the cloud-hosted Nexus service. Extended earlier Nexus administration experience by containerising the repository manager itself rather than installing it directly on the host. | [View Project](https://github.com/ChiomaScripts/Dev7d-containerized-nexus-deployment) |
| **Private Amazon ECR Registry & Docker Compose Deployment on AWS Lightsail** | AWS ECR, AWS Lightsail, IAM, AWS CLI, Docker, Docker Compose, Ubuntu, Linux, SSH, SCP, Python, FastAPI, MongoDB, Mongo Express, Docker Volumes | Published an existing FastAPI Docker image to a private Amazon ECR repository using AWS CLI and IAM authentication, provisioned an Ubuntu Lightsail instance, installed Docker Engine and Compose, and authenticated the remote host to retrieve the private image. Transferred deployment configuration securely via SCP, launched a three-service Compose stack with MongoDB health checks and persistent storage, configured restricted inbound firewall access, and verified the application UI through the Lightsail public endpoint. | [View Project](https://github.com/ChiomaScripts/Dev7e-aws-ecr-lightsail-compose) |

## Engineering Focus

The projects in this portfolio are organised around the following engineering disciplines:

- **Cloud Infrastructure:** Provisioning, configuring, and managing cloud-hosted environments across DigitalOcean and AWS Lightsail, including compute resources, SSH access and network firewall configuration.
- **Linux & Systems Administration:** User management, SSH authentication, filesystem permissions, server configuration, package installation, service management and system-level troubleshooting.
- **Application Deployment:** Building, packaging, transferring, executing, publishing and verifying application artifacts across local and remote environments.
- **Containers & Networking:** Building Docker images, configuring container networking and service discovery, managing multi-container applications through Docker Compose, exposing services through host-to-container port publishing, and distributing container images through private registries.
- **Container Orchestration & Persistent Storage:** Defining reproducible multi-service application stacks, managing startup dependencies and container lifecycle policies, configuring application environments, and preserving database and repository data using Docker-managed volumes.
- **Artifact & Repository Management:** Configuring and administering Sonatype Nexus repositories, managing publishing permissions and registry authentication, publishing versioned application artifacts, and integrating with AWS-managed Amazon ECR.
- **Cloud Identity & Access Management:** Configuring AWS IAM identities, AWS CLI profiles and authenticated access to private ECR repositories, while applying network access restrictions and credential-handling practices.
- **DevOps Automation:** Developing repeatable processes, using declarative configuration to reduce repetitive manual commands, and improving consistency across application deployments.
- **CI/CD & Infrastructure as Code:** Building skills in automated delivery pipelines and declarative infrastructure management.
- **Observability & Reliability:** Exploring application monitoring, investigating operational failures, implementing container health checks, and improving service startup reliability.

## Project Documentation

Each project repository contains implementation details relevant to the work performed, including:

- Project objectives and technologies.
- Architecture or deployment workflows.
- Implementation steps, commands, and configuration details.
- Verification evidence, screenshots, and validation results where applicable.
- Troubleshooting investigations, observations, and lessons learned.
- Engineering considerations, potential improvements, and project reflections.
- Connections to previously completed engineering work.

Projects are added incrementally as their practical implementations are completed.

## Portfolio Status

**Active — Ongoing Development**

The portfolio currently contains **seven completed, documented DevOps engineering projects**, covering cloud-hosted application deployment, artifact repository management, Docker containerisation, self-hosted and AWS-managed private container registries, multi-container orchestration, persistent storage, and remote application deployment on AWS Lightsail.

The projects demonstrate a progression from Linux server administration and application deployment to container-based infrastructure, private image distribution, and cloud-hosted multi-service application delivery.

Additional projects will be added as I progress through hands-on DevOps engineering training and independent technical exercises.

## Background

This portfolio reflects my continued development in DevOps engineering, building on a foundation in production operations, application support, troubleshooting, and service reliability.

The focus is on gaining practical experience across the application delivery lifecycle, from infrastructure provisioning and deployment to artifact management, containerisation, automation, monitoring, and operational improvement.

The projects also demonstrate a progressive engineering approach, where previously developed applications, infrastructure and deployment artifacts are reused and extended to explore new technologies and operational practices.

---

## 🔗 Explore My Complete Engineering Portfolio

For a consolidated view of my professional engineering experience, DevOps implementations, Python development, applied AI and data analytics projects, visit my **[Engineering Portfolio](https://github.com/ChiomaScripts/Engineering-Portfolio)**.
