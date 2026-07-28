# 📦 SmartStock

> Sistema inteligente de gestión de inventarios desarrollado con **Java 21**, **Spring Boot 3.5** y **PostgreSQL**.

SmartStock es una aplicación backend diseñada para pequeñas y medianas empresas que necesitan administrar su inventario de forma eficiente. El proyecto sigue una arquitectura por capas, principios SOLID y buenas prácticas de desarrollo para ofrecer un código limpio, escalable y mantenible.

---

## 🚀 Tecnologías

| Tecnología | Versión |
|------------|----------|
| Java | 21 |
| Spring Boot | 3.5 |
| Maven | 3.x |
| PostgreSQL | 17+ |
| Spring Data JPA | ✔ |
| Hibernate | ✔ |
| Lombok | ✔ |
| Bean Validation | ✔ |
| Git | ✔ |
| GitHub | ✔ |

---

## 📂 Arquitectura

El proyecto sigue una arquitectura por capas para facilitar el mantenimiento y la escalabilidad.

```text
src/main/java/com/smartstock

├── authentication
├── category
├── common
├── config
├── exception
├── inventory
├── product
├── purchase
├── report
├── sale
├── security
├── supplier
├── user
└── util
```

Cada módulo contiene:

```text
controller/
dto/
entity/
mapper/
repository/
service/
    └── impl/
```

---

# ✨ Características

## 👤 Usuarios

- Registro
- Inicio de sesión
- Roles
- Administración de usuarios

## 📦 Productos

- CRUD de productos
- Código de barras
- Stock mínimo
- Precio de compra
- Precio de venta
- Categorías
- Proveedores

## 🏷 Categorías

- Crear
- Editar
- Eliminar
- Consultar

## 🚚 Proveedores

- CRUD completo

## 📈 Inventario

- Entradas
- Salidas
- Historial
- Movimientos

## 🛒 Compras

- Registro de compras
- Actualización automática del stock

## 💰 Ventas

- Registro de ventas
- Descuento automático del inventario

## 📊 Dashboard

- Total de productos
- Productos con bajo stock
- Ventas del día
- Compras del mes
- Productos más vendidos

## 📑 Reportes

- Inventario
- Compras
- Ventas
- Productos agotados

---

# 🛠 Instalación

## Clonar el repositorio

```bash
git clone https://github.com/LauraDaheq/SmartStock.git
```

Entrar al proyecto

```bash
cd SmartStock
```

Compilar

```bash
mvn clean install
```

Ejecutar

```bash
mvn spring-boot:run
```

---

# 🗄 Base de datos

Motor:

- PostgreSQL

Base de datos:

```text
smartstock
```

---

# 📌 Estado del proyecto

Actualmente se encuentra en desarrollo.

### ✔ Completado

- Arquitectura base
- Configuración de Maven
- Spring Boot
- PostgreSQL
- Estructura modular
- Configuración inicial

### 🚧 En desarrollo

- Módulo User
- Autenticación
- Categorías
- Productos
- Inventario
- Compras
- Ventas

### 📅 Próximamente

- Spring Security
- JWT
- Swagger/OpenAPI
- Dashboard
- Reportes
- Docker
- Pruebas unitarias
- CI/CD

---

# 📋 Roadmap

- [x] Configuración del proyecto
- [x] Maven
- [x] Spring Boot
- [x] PostgreSQL
- [ ] Usuarios
- [ ] Categorías
- [ ] Proveedores
- [ ] Productos
- [ ] Inventario
- [ ] Compras
- [ ] Ventas
- [ ] Dashboard
- [ ] Reportes
- [ ] Spring Security
- [ ] JWT
- [ ] Swagger
- [ ] Docker
- [ ] Tests
- [ ] CI/CD

---

# 🎯 Objetivos del proyecto

- Aplicar arquitectura por capas.
- Implementar principios SOLID.
- Seguir buenas prácticas de Clean Code.
- Construir una API REST profesional.
- Desarrollar un proyecto de portafolio con estándares de la industria.

---

# 👩‍💻 Autora

**Laura Hernández**

Electronic Engineer

Universidad Nacional de Colombia

GitHub:

https://github.com/LauraDaheq

---

# ⭐ Si este proyecto te resulta interesante

¡No olvides dejar una estrella en el repositorio!
