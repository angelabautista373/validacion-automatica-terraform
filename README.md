# Validación automática con Terraform

![Terraform Validate](https://github.com/angelabautista373/validacion-automatica-terraform/actions/workflows/terraform.yml/badge.svg)

Este proyecto automatiza la validación del código Terraform utilizando GitHub Actions.

Cada vez que se realiza un push al repositorio, se ejecuta automáticamente:

- terraform init
- terraform validate

Esto permite detectar errores en la configuración antes de desplegar infraestructura.
