# Axiom Auth

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/codegshinde/axiom-auth/go.yml)
![Go Version](https://img.shields.io/badge/Go-1.21.4+-00ADD8?logo=go&logoColor=white)
![License](https://img.shields.io/github/license/codegshinde/axiom-auth)
![Last Commit](https://img.shields.io/github/last-commit/codegshinde/axiom-auth)

**Axiom Auth** is a lightweight, production-ready authentication microservice written in Go.  
It is designed as a foundational building block for modern, distributed backend systems.

The project focuses on **clarity, security, and extensibility**, making it suitable for both
small services and larger microservice-based platforms.

---

## Why Axiom Auth

Most authentication services either become overly complex or tightly coupled to a specific
platform. Axiom Auth takes a pragmatic approach:

- Minimal surface area
- Explicit behavior
- Clean separation of concerns
- Infrastructure-friendly design

It is intended to be **composed**, not imposed.

---

## Features

- JWT-based authentication
- User and Admin identity management
- Secure password hashing using bcrypt
- Environment-driven configuration
- Clean, idiomatic Go codebase
- Designed for microservice architectures

---

## Non-Goals

To keep the project focused, Axiom Auth intentionally does **not** include:

- UI or frontend components
- Opinionated authorization policies
- Vendor-specific dependencies
- Session storage or stateful auth flows

These concerns are expected to be handled at the platform or gateway level.

---

## Requirements

- Go **1.21.4+**
- MongoDB (local or managed instance)

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/codegshinde/axiom-auth.git
cd axiom-auth
