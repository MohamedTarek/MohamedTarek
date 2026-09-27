# Hi, I'm Mohamed Tarek

Engineering Lead and Senior Backend Engineer with 12+ years in software engineering, 6+ of them
designing distributed systems and leading engineering teams. I build backends that stay up under
load: Laravel, Node.js and Go on the application side, PostgreSQL and MySQL underneath, Redis and
RabbitMQ in between.

Currently leading the engineering team at Batsync, a software house in Cairo.

## Now: Engineering Lead at Batsync (Jan 2026 to present)

- Lead the engineering team (planning, code review, delivery) across Ad Guardians, Lott AG and
  Franchise AG, and maintain and extend their legacy PerfexCRM (PHP) platforms.
- Introduced CI/CD with Woodpecker: lint, PHPUnit, automated staging deploys with migrations,
  deploy results posted to ClickUp.
- Dockerized the apps (web, DB, Redis, queue workers) for all environments.
- Stripe billing: multi-subscription checkout, consolidated invoicing, upgrades, proration,
  wallet-to-Stripe migration.
- Moved Meta spend sync and location-fee jobs to RabbitMQ with partner-sharded queues.
- REST API v2 (auth, wallet, ad accounts) with a 57-test PHPUnit suite.
- AI tooling: built a ClickUp MCP server (TypeScript); led delivery of the Lott AG CRM MCP server
  for safe AI querying of CRM data.
- Also: Telegram group automation, AI brand-theme generation, a Laravel AI ad-compliance pipeline
  and a Playwright lead scraper.

## Featured

**[laravel-stampede-guard](https://github.com/MohamedTarek/laravel-stampede-guard)**
Cache stampede prevention for Laravel 6 to 13. Two macros on the cache repository: an
atomic-lock `remember()` and a probabilistic early-refresh `remember()` (XFetch) with the
refresh lock handed from the request to a queued job. Measured in its own test suite:
50 concurrent workers on a cold key, 1 computation instead of 50. PHPStan level 8,
97 tests, CI across 8 Laravel majors.

## How I lead

- **Standards first.** CI/CD and code review from day one. Every repo my team touches follows
  the same rules: environment-tagged PR titles, typed branch names, a technical design task
  before any feature, and a review-then-QA gate before anything reaches production.
- **Ownership over tasks.** Every engineer develops deep expertise in their domain while
  contributing across the codebase. When something breaks in their area, they're the go-to person.
- **Production mindset.** If it can't be monitored or scaled, it shouldn't ship. Every
  architectural decision considers production impact and growth from day one.
- **Mentor through code.** Every PR is a teaching moment. I grow engineers through review,
  not lectures.

## Before Batsync

- **MoneyMoon SA (fintech), 2024 to 2026.** Extracted the Offers and Investments module into a
  microservice with Camunda BPMN, owned B2B bank and payment gateway integrations and the backend
  CI/CD pipeline, built the push notification system (FCM and Huawei PushKit).
- **Suiiz App, 2023 to 2024.** Built and managed the engineering team from the ground up as
  Engineering Manager. Cut cloud infrastructure costs by 90% while improving performance by 20%,
  and ran a zero-downtime, zero-data-loss cloud migration with blue-green deploys.
- **Baramoda, 2019 to 2022.** Technical Lead over 5 products on AWS: Agrinable (agriculture),
  Environeur (Egypt's first online environmental waste management platform), HRMS, Operations
  and CRM.
- **Cloumerce, 2018 to present.** Co-founded and solo-architected a multi-tenant SaaS e-commerce
  operations platform used by Egyptian merchants, 8 years in production.

## What I care about

- Correctness under concurrency: locks, idempotency, and the failure modes nobody tests for.
- Boring, well-measured infrastructure over clever abstractions.
- Packages that document their guarantees and prove them with tests.

## Stack

PHP, Laravel, Node.js, Go, PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch, RabbitMQ, Docker,
Kubernetes, AWS, CI/CD (Jenkins, ArgoCD, Woodpecker).

## Reach me

- Website: [mohamed-tarek.com](https://mohamed-tarek.com)
- LinkedIn: [linkedin.com/in/mt-elafifi](https://www.linkedin.com/in/mt-elafifi)
- Email: mt.elafifi@gmail.com
