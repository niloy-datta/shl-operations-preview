# SHL Operations — public static design tour

This GitHub Pages repository hosts **visual-only, read-only previews** from [shl-operations](https://github.com/niloy-datta/shl-operations). It does **not** host the actual ERP or provide user authentication, API servers, PostgreSQL, customer records, invoicing or shipping transactions.

## Public demos

- [Enterprise Experience](https://niloy-datta.github.io/shl-operations-preview/enterprise.html) — extended conceptual module tour.
- [Classic Operations preview](https://niloy-datta.github.io/shl-operations-preview/) — legacy static visual interface.

## GitHub Actions deployment

The [Pages workflow](.github/workflows/pages.yml) validates static HTML/CSS/JS and publishes only the `site/` directory on pushes to the `main` branch. Pull requests run validation without publishing. No production secrets or private data belong in this repository.

This repository is **public**, as is the source development repository at the time of this change. They must not be treated as approved infrastructure for real SHL records. Deploying the actual Next.js + Java/Spring Boot + PostgreSQL ERP requires independent private infrastructure and the security gates documented in the main repository.
