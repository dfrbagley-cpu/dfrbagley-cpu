# David Bagley

I work at the intersection of hospital operations, healthcare analytics, data governance and product design. I translate ambiguous healthcare reporting and workflow problems into governed definitions, reusable data processes and decision-ready tools.

My responsibilities include problem framing, healthcare-domain modelling, product scope and prioritization, requirements, acceptance criteria, UX decisions and validation. I use AI-assisted development to accelerate implementation while retaining responsibility for the healthcare-domain decisions, product direction and validation.

## Professional context

In my healthcare decision-support work, I have designed the end-to-end reporting architecture for four reporting systems—from workflow, clinical-documentation and data-capture design through governed definitions, R-based analytical logic, recurring reporting and decision-ready outputs. I define the fields, derived-data requirements, business rules, outputs and validation criteria. Epic analysts and other technical teams configure the underlying platforms from those specifications; I develop the analytical and reporting logic and validate the results.

I work across clinical, administrative, management and technical teams through planning, testing, training and ongoing improvement. My professional analytics work is primarily in R, with Python used selectively and SQL supporting data access and transformation.

## Featured work

### [Health Data Edge Cases](https://github.com/dfrbagley-cpu/health-data-edge-cases)

[Live demonstration](https://dfrbagley-cpu.github.io/health-data-edge-cases/)

A synthetic, implementation-neutral contract suite showing how plausible healthcare results can become incorrect when source versions, mappings, statuses, relationships or event grain are inconsistent. It covers five failure modes and 72 executable expectations, with portable SQL verified in SQLite and DuckDB through a Python harness, an independent base-R cross-check and a versioned contract catalogue.

### [Healthcare Reporting Toolkit](https://github.com/dfrbagley-cpu/healthcare-reporting-toolkit)

[Live demonstration](https://dfrbagley-cpu.github.io/healthcare-reporting-toolkit/)

Four local-first browser analysis workflows plus a Receipt Inspector for hospital decision-support and analytics teams. The toolkit uses no remote storage or telemetry, includes a browser-tested 100,000-row extract-audit path, produces versioned analysis receipts with deterministic calculation digests and includes automated accessibility checks.

Together, the projects demonstrate a small trusted-data lifecycle: synthetic source records are validated against explicit rules, transformed into tested metrics and quality signals, published in a versioned catalogue, consumed by a downstream tool pinned to a specific catalogue release, and documented in versioned receipts with deterministic calculation digests.

## Portfolio boundaries

All public portfolio work was developed independently of my employer using synthetic data. It contains no patient information, employer data, licensed reporting standards or proprietary vendor schemas. These projects demonstrate product and technical reasoning; they are not clinical software, official reporting standards or hospital production deployments.
