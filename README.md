# David Bagley

**Clinical & operational analytics · Healthcare decision support · Data quality & reporting architecture**

I help healthcare leaders turn operational questions into reliable information and practical tools. My work connects people on the front lines, managers, directors and technical teams—from understanding the problem and shaping the workflow to building the reporting logic and getting the solution into use.

## Healthcare decision support

I have designed end-to-end reporting architecture for four systems, connecting workflows, clinical documentation and data capture with business rules, derived-data requirements, validation and recurring reports. I also write the analytical logic and build, manage and maintain the resulting pipelines and tools. My professional analytics work is primarily in **R**, with Python used selectively and SQL supporting data access and transformation.

Alongside that hands-on work, I advise managers and directors on decision support, program management and implementation. I contribute to quality and operations committees, an ethics advisory committee, working groups and project steering committees, and work across clinical, administrative and technical teams through planning, testing, training and ongoing improvement.

## Public tools you can try

### [Healthcare Reporting Toolkit](https://github.com/dfrbagley-cpu/healthcare-reporting-toolkit)

**[Try the Extract Change Auditor](https://dfrbagley-cpu.github.io/healthcare-reporting-toolkit/#auditor)** · [Explore all tools](https://dfrbagley-cpu.github.io/healthcare-reporting-toolkit/)

Catch changes between CSV extracts, define reporting periods, explore waitlist capacity and check reporting results. Four browser analysis workflows plus a Receipt Inspector run locally without accounts, uploads or telemetry. Evidence includes a browser-tested 100,000-row extract-audit path, versioned analysis receipts with deterministic calculation digests and automated accessibility checks.

### [Health Data Edge Cases](https://github.com/dfrbagley-cpu/health-data-edge-cases)

**[Explore the validation report](https://dfrbagley-cpu.github.io/health-data-edge-cases/)** · [Try a deliberate reporting mismatch](https://dfrbagley-cpu.github.io/healthcare-reporting-toolkit/#validate)

Test reporting logic against five synthetic failure modes and 72 executable expectations. The suite makes errors involving duplicate versions, conflicting statuses, missing mappings, reporting periods and join inflation inspectable. Portable SQL is verified in SQLite and DuckDB through a Python harness and independently cross-checked in base R.

The projects work together: the edge-case suite publishes a versioned contract catalogue, and the toolkit checks results against a pinned copy and exports reviewable analysis receipts. The repositories include product case studies, reproducible examples and contribution guidance.

I define the problems, healthcare-domain rules, scope, requirements, acceptance criteria and user experience, and validate the results. I use AI-assisted development to accelerate implementation while retaining responsibility for product direction, domain decisions and validation.

## Portfolio boundaries

These public projects were developed independently of my employer using synthetic data. They contain no patient information, employer data, licensed reporting standards or proprietary vendor schemas. They demonstrate product and technical reasoning and are separate from the hospital work described above; they are not hospital production deployments, clinical software or official reporting standards.
