See:
* https://github.com/shieldfy/API-Security-Checklist
* https://github.com/yosriady/awesome-api-devtools

Cheat Sheets:
* https://googlecloudcheatsheet.withgoogle.com

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
- [ ] Sidecar pattern
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
- [ ] Strangler Fig pattern
- [ ] Bulkhead pattern
- [ ] Retry

# Coding style

* Documentation
- [ ] Readme
- [ ] Code documentation: plantUML, mermaid JS, [diagram-as-code](https://github.com/mingrammer/diagrams)
- [ ] Conventional Commit
- [ ] Generation of Release notes
* Design
- [ ] Domain centric architecture (hexagonal, onion, clean, domain-driven hexagon)
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
- [ ] Dependencies analysis (jdeps, dependabot, renovate)
- [ ] Linter
- [ ] git hooks
- [ ] frameworks and components up to date - check [end of life](https://endoflife.date)
- [ ] Backward compatibility / Binary compatibility
* Productivity
- [ ] version management (jabba, SDK man, nvm)
- [ ] wrapper (mvnw, gradlew)
- [ ] Bootstrapping (yeoman, jhipster, github templates...)
- [ ] Code generation (mapstruct, lombok, javapoet/kotlinpoet...)
- [ ] run.sh / install.sh or docker-compose
- [ ] .run and .env configurations
- [ ] Mocking / Stubbing: Wiremock, Mockserver, [Microcks](https://microcks.io/)


# Tests

* Application scope
- [ ] Unit tests
- [ ] Component tests
- [ ] Property based tests
- [ ] Acceptance tests
- [ ] Mutation tests
- [ ] A/B Tests
- [ ] Backward compatibility testing
- [ ] Fuzz tests
- [ ] Monkey tests
- [ ] Architecture tests
- [ ] [Golden Master](https://www.softfluent.fr/blog/tout-ce-quil-faut-savoir-sur-golden-master-testing/) - See [Approval tests](https://approvaltests.com)
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
- [ ] ITCSS
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
- [ ] CDN / reverse proxy (cloudflare)
- [ ] Message broker
- [ ] NoSQL
- [ ] Indexation
- [ ] serverless
- [ ] low code / no code
- [ ] Service discovery
- [ ] Configuration externalization
* Consistency
- [ ] SSO
- [ ] IAM / CIAM
- [ ] Single source of truth
- [ ] ELK
- [ ] Distributed transactions / Saga pattern / Two-Phase Commit
- [ ] Bucket S3 / Cloud Storage
- [ ] RGPD
- [ ] Event-driven architecture
* Documentation
- [ ] [C4 model](https://c4model.com)
- [ ] UML
- [ ] MERISE
- [ ] DAT

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

# Methods
- [ ] Fail & Learn
- [ ] Fake it until you make it

# Tools to improve productivity

- [ ] Copilot / OpenAI / AI assistant
- [ ] code with me
- [ ] Postman / Hoppscotch
- [ ] Code templates
