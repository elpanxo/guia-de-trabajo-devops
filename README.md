# Proyecto DevOps - Pipeline CI/CD

## 📌 Descripción

Este repositorio forma parte de un laboratorio de DevOps donde se implementa un flujo completo de integración y despliegue continuo (CI/CD), junto con una arquitectura multinivel en AWS.

## 🌿 Estrategia de ramas

Se utilizó una estrategia basada en Feature Branches, donde cada funcionalidad se desarrolla en una rama independiente:

- `feature/frontend`: Contiene un archivo index.html con un "Hola Mundo".
- `feature/docker`: Contiene un Dockerfile para desplegar la aplicación usando nginx.
- `feature/docs`: Contiene la documentación del proyecto.

Cada rama es integrada a `main` mediante Pull Requests.

## 🚀 Tecnologías utilizadas

- Git y GitHub
- Docker
- GitHub Actions
- AWS (VPC, EC2)

## 🎯 Objetivo

Automatizar el ciclo de desarrollo, construcción y despliegue de una aplicación web simple siguiendo buenas prácticas DevOps.
