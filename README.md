# SecurePKI
Cloud-native PKI and certificate management platform on AWS and Kubernetes with automated certificate lifecycle management and DevSecOps practices.
# Project Overview
SecurePKI is a cloud-native certificate management platform designed to automate the lifecycle of TLS certificates for applications running on Kubernetes.
The project combines cloud infrastructure, Kubernetes, PKI, automation and security practices to demonstrate a practical DevSecOps workflow.

## Objectives
The main objectives of SecurePKI are to:

- Automate TLS certificate issuance
- Automate certificate renewal
- Support certificate revocation
- Secure private keys and sensitive credentials
- Deploy the platform on AWS
- Manage infrastructure using Infrastructure as Code
- Automate deployments through CI/CD
- Integrate security controls into the software delivery lifecycle
- Monitor certificate and infrastructure health

## Planned Architecture
The platform will run on AWS using Amazon EKS as the Kubernetes platform.

## Planned Technologies
- AWS
- Terraform
- Kubernetes / Amazon EKS
- Docker
- HashiCorp Vault
- cert-manager
- GitHub Actions
- Python / FastAPI
- Prometheus
- Grafana
