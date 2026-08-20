# John Palmer, MSc.

**Genomics Software Developer · Bioinformatician · Scientific Software Engineer**

I build reliable software for public-health genomics: production Nextflow
workflows, Python services, validated analysis systems, data platforms, and
secure AWS infrastructure. My work sits at the boundary between biological
reasoning and the engineering required to make an analysis reproducible,
auditable, and useful in routine operations.

[Portfolio](https://jpalmer37.github.io) ·
[LinkedIn](https://linkedin.com/in/john-palmer-932542b6/)

## Selected systems

- **Influenza mutation surveillance** — Sole architect and principal developer
  of a production analysis platform spanning Python and Nextflow. Independent
  validation reached an all-SNV F1 of 0.9915 across 192 samples and all eight
  influenza segments.
- **Secure sequence submission on AWS** — Sole architect and developer of a
  serverless transfer service using short-lived identity, write-only tenant
  isolation, immutable uploads, confirm-before-expiry lifecycle controls, and
  durable PostgreSQL audit records.
- **Public-health workflow automation** — Led and contributed to validated,
  dependency-aware pathogen-genomics workflows, result aggregation, database
  integration, and unattended analysis on shared HPC infrastructure.

These systems include both solely authored work and shared organizational
codebases. Project descriptions identify my role explicitly; links to shared
work point to the maintained upstream repository.

## Public work

### Shared genomics projects

- [`BCCDC-PHL/fluviewer-nf`](https://github.com/BCCDC-PHL/fluviewer-nf) —
  influenza whole-genome analysis, clade assignment, genotyping, mutation
  reporting, provenance, and workflow validation.
- [`BCCDC-PHL/noro-typing-nf`](https://github.com/BCCDC-PHL/noro-typing-nf) —
  automated norovirus assembly, typing, and phylogenetic analysis.
- [`BCCDC-PHL/auto-hcv`](https://github.com/BCCDC-PHL/auto-hcv) — automated
  genomic analysis and operational file-transfer workflows for HCV data.

### Personal repositories

- [`pyslurm`](https://github.com/jpalmer37/pyslurm) — a typed Python interface
  for submitting and monitoring SLURM job arrays through Meta's `submitit`.
- [`agent-skills`](https://github.com/jpalmer37/agent-skills) — reusable agent
  skills for Nextflow, Python data work, visualization, and dashboards.

## Core stack

- **Scientific software:** Python, Nextflow DSL2, Bash, R, Biopython, pandas,
  Polars, scikit-learn
- **Workflow and HPC:** SLURM, `submitit`, Apptainer/Singularity, Docker, Conda,
  GitHub Actions
- **Data and services:** PostgreSQL, SQLite, SQLAlchemy, Alembic, FastAPI,
  Pydantic, React, TypeScript
- **Cloud:** AWS CDK, Lambda, S3, SQS, EventBridge, RDS, ECS Fargate, Cognito,
  IAM, CloudWatch

I am based in Toronto, Ontario, Canada.
