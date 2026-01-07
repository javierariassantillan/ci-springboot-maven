[![CI Spring Boot](https://github.com/javierariassantillan/ci-springboot-maven/actions/workflows/ci.yml/badge.svg)](https://github.com/javierariassantillan/ci-springboot-maven/actions/workflows/ci.yml)

# CI Spring Boot con Maven y Docker

Proyecto de ejemplo con integración continua usando **GitHub Actions**.

## 🚀 Pipeline CI
En cada push a `main` se ejecuta:

- Build del proyecto con Maven
- Tests unitarios e integración
- Construcción del JAR
- Publicación del JAR como artifact
- Construcción de imagen Docker lista para deploy

## 🛠️ Tecnologías
- Java 17
- Spring Boot
- Maven
- Docker
- GitHub Actions

Docker Hub integrado 🚀
