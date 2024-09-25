# Rust Blueprint

A scalable and modular blueprint for building web applications with Rust. Inspired by [melkeydev/go-blueprint](https://github.com/melkeydev/go-blueprint) (in terms of tooling/templating), this project is designed to provide a solid starting point for new Rust projects with flexible framework, database, and pub/sub integration options.

## Frameworks

Choose one of the following Rust web frameworks:
- **Axum**
- **Rocket**

## Database

Multiple database options with ORM or pool-only modes:
- **Diesel (ORM)**
- **Diesel (pool only)**
- **SeaORM**
- **SQLx**

## Middlewares

Enhance your application with these middleware components:
- **Tenant middleware**
- **Authentication**
  - Okta integration
  - Social login (Google, GitHub, etc.)

## Caching

Leverage caching to optimize performance:
- **Redis**

## Pub/Sub

Real-time message brokers:
- **NATS**
- **AMQP**
- **Redis**

## Docker

Containerization support for different environments:
- **Local Development**
- **Production** (e.g., Distroless)

---

## Roadmap

### Milestone 1: Initial Setup
- [ ] Project scaffolding with **Axum** or **Rocket**
- [ ] Basic Docker setup for local development
- [ ] Integrate database choice: **Diesel**, **SeaORM**, or **SQLx**

### Milestone 2: Middleware & Authentication
- [ ] Implement tenant-based middleware
- [ ] Add **Okta** authentication
- [ ] Implement social login (Google, GitHub, etc.)

### Milestone 3: Caching and Pub/Sub
- [ ] Integrate **Redis** caching
- [ ] Add support for **NATS**, **AMQP**, or **Redis** pub/sub

### Milestone 4: Production Ready
- [ ] Optimize Docker setup for production (e.g., Distroless)
- [ ] Performance tuning and security hardening

### Milestone 5: Testing and Documentation
- [ ] Add unit and integration tests
- [ ] Create detailed documentation

---

## Contributing

We welcome contributions! Feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License.
