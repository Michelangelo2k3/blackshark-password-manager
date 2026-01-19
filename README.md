# 🦈 BlackShark Password Manager

> Gestor de contraseñas seguro con backend Spring Boot y app Android

## 🗒️️Descripción

BlackShark es un gestor de contraseñas personal que permite almacenar credenciales de forma segura utilizando cifrado AES-256. El proyecto consta de dos partes:

- **Backend API REST** (este repositorio): Servidor desarrollado con Java y Spring Boot.
- **App Android** (próximamente): Cliente móvil para gestionar las contraseñas.

## 🎯 Objetivos del proyecto

Este es un proyecto de aprendizaje con los siguientes objetivos:

- [ ] Mejorar base de Java y Spring boot.
- [ ] Entender arquitectura de software (capas, MVC).
- [ ] Crear una API REST COMPLETA.
- [ ] Desarrollar una app Android que consuma la API.
- [ ] Hacer uso de buenas prácticas para futuros proyectos.

## 🛠 Stack Tecnológico

| Componente | Tecnología |
|------------|------------|
| Lenguaje | Java 17 |
| Framework | Spring Boot 3.5.9 |
| Base de datos | H2 (desarrollo) → PostgreSQL (producción) |
| Build | Maven |
| Seguridad | AES-256, JWT |
| IDE | IntelliJ IDEA |


## 🚀 Cómo ejecutar

```bash
# Clonar repositorio
git clone https://github.com/Michelangelo2k3/blackshark-password-manager.git
cd blackshark-password-manager

# Ejecutar la aplicación
./mvnw spring-boot:run

# Consola H2 (desarrollo)
http://localhost:8080/h2-console
```

## 📁 Estructura del proyecto

```
src/main/java/com/miguel/passmanager/
├── controller/   # Endpoints REST
├── service/      # Lógica de negocio
├── repository/   # Acceso a BD
└── model/        # Entidades JPA
```

## 📖 Documentación

- [Arquitectura del Backend](docs/architecture/backend.md)

## 📋 Estado del proyecto

- [x] Estructura inicial
- [ ] Modelo Password
- [ ] CRUD básico
- [ ] Cifrado AES-256
- [ ] Autenticación JWT
- [ ] App Android

---
*Desarrollado por Miguel Ángel Cámara Martínez*
