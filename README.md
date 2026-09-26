# Hi, I'm Mohamed Tarek

Senior software engineer. I build backends that stay up under load: Laravel and PHP on
the application side, PostgreSQL and MySQL underneath, Redis in between.

<!-- Edit me: one or two sentences on where you work and what you are doing now, e.g.
"Currently leading backend engineering at <company>, working on <what>." -->

## What I care about

- Correctness under concurrency: locks, idempotency, and the failure modes nobody tests for.
- Boring, well-measured infrastructure over clever abstractions.
- Packages that document their guarantees and prove them with tests.

## Featured

**[laravel-stampede-guard](https://github.com/MohamedTarek/laravel-stampede-guard)**
Cache stampede prevention for Laravel 6 to 13. Two macros on the cache repository: an
atomic-lock `remember()` and a probabilistic early-refresh `remember()` (XFetch) with the
refresh lock handed from the request to a queued job. Measured in its own test suite:
50 concurrent workers on a cold key, 1 computation instead of 50. PHPStan level 8,
97 tests, CI across 8 Laravel majors.

<!-- Edit me: add the article link when it is published, e.g.
Write-up: [Cache stampedes in Laravel: why locking isn't enough](https://...) -->

## Stack

PHP, Laravel, PostgreSQL, MySQL, Redis, Docker, GitHub Actions.
<!-- Edit me: add or remove as fits; keep it to one line. -->

## Reach me

- Website: [mohamed-tarek.com](https://www.mohamed-tarek.com)
- Email: mt.elafifi@gmail.com
<!-- Edit me: add LinkedIn and X if you use them:
- LinkedIn: https://www.linkedin.com/in/...
- X: https://x.com/...
-->
