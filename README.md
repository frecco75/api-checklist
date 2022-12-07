See:
* https://github.com/shieldfy/API-Security-Checklist
* https://github.com/yosriady/awesome-api-devtools

# API Checklist

* Documentation
- [ ] Design First approach
- [ ] OpenAPI Linter
- [ ] Documentation
- [ ] HATEOAS
- [ ] Backward compatibility contract check
- [ ] Consumer-Driven Contract testing / [Bi-directional](https://docs.pactflow.io/docs/bi-directional-contract-testing) (nice with design first)
- [ ] Versioning (SemVer)
* Contexts
- [ ] i18n / context headers
- [ ] Multi-tenancy
- [ ] Content negotiation
- [ ] Pagination / Filtering (RSQL)
* Security
- [ ] Authentication (OAuth2, OWASP)
- [ ] Scopes / Roles / Privileges
- [ ] CORS / CSRF
- [ ] HTTPS / TLS
- [ ] API Gateway
- [ ] API Management
* Resilience
- [ ] SLA / SLO / SLI
- [ ] Rate limiting / Throttling
- [ ] Circuit breaker
- [ ] Feature toggle

# Coding style

* Documentation
- [ ] Readme
- [ ] Code documentation
- [ ] Conventional Commit
- [ ] Generation of Release notes
* Design
- [ ] Hexagonal architecture
- [ ] Functional programming
- [ ] event-driven development
- [ ] event sourcing
- [ ] CQRS
* Practices
- [ ] ATDD
- [ ] xDD (TDD, BDD, DDD)
- [ ] Ubiquitous language
- [ ] Timeouts (connection, read, database transactions..)
- [ ] Git Flow
* Quality
- [ ] Code Analysis
- [ ] Linter
- [ ] git hooks
* Productivity
- [ ] version management (jabba, SDK man, nvm)
- [ ] wrapper (mvnw, gradlew)
- [ ] Bootstrapping (yeoman, jhipster, github templates...)
- [ ] Code generation (mapstruct, lombok, javapoet/kotlinpoet...)
- [ ] Mocking / Stubbing


# Tests

* Application scope
- [ ] Unit tests
- [ ] Component tests
- [ ] Acceptance tests
- [ ] Mutation tests
- [ ] A/B Tests
- [ ] Backward compatibility testing
- [ ] Fuzz tests
- [ ] Monkey tests
* Global Scope
- [ ] Smoke tests
- [ ] Sanity tests
- [ ] Integration tests
- [ ] Non regression tests
- [ ] E2E tests
- [ ] Chaos tests
* Performance & Security
- [ ] Penetration tests
- [ ] Performance tests
- [ ] Soak tests
- [ ] Load tests

# DATABASE

* NoSQL
- [ ] MongoDB
- [ ] Redis
* Synchronization
- [ ] Kafka connect / streams
- [ ] Debezium (CDC)
- [ ] Outbox pattern
- [ ] Database schema changes (liquibase)

# Front

* Design
- [ ] BEM approach
- [ ] Atomic Design
- [ ] Design System
- [ ] Storybook
* Application
- [ ] Micro-frontend
- [ ] SPA / PWA
- [ ] Static site generator (Hugo, gatsby..)
- [ ] SSR
- [ ] GraphQL

# Architecture

* Scalability
- [ ] reverse proxy (cloudflare)
- [ ] Message broker
- [ ] NoSQL
- [ ] Indexation
- [ ] serverless
- [ ] low code / no code
* Consistency
- [ ] SSO
- [ ] IAM / CIAM
- [ ] Single source of truth
- [ ] ELK
- [ ] Distributed transactions
- [ ] Bucket S3 / Cloud Storage
- [ ] RGPD

# Infra

- [ ] Conception as Code / Diagram as Code
- [ ] Infra as Code
- [ ] CI / CD
- [ ] Package management (nexus, artifactory, github packages..)
- [ ] GitOps / FinOps / DevSecOps / SRE
- [ ] Monitoring
- [ ] Tracing
- [ ] Profiling
- [ ] Canary Release
- [ ] Rolling Update
- [ ] Secrets management
- [ ] Terraform
- [ ] Helm chart

# Security

- [ ] Snyk
- [ ] Trivy
- [ ] Dependabot

# Tools to improve productivity

- [ ] Copilot
- [ ] OpenAI
- [ ] code with me
- [ ] Postman / Hoppscotch
