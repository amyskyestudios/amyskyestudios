# Amy Skye Studios 

**Senior Data Engineering | Analytics Engineering | Data Quality | Cloud, Lakehouse & AI-Assisted Modernization**

Amy Skye Studios is the independent data-engineering, analytics-engineering, and technical-learning portfolio of **Amy (Brian) Goodell**.

I build practical, documented projects that extend more than nine years of enterprise data-engineering experience into modern cloud and lakehouse platforms. My work combines ETL/ELT, SQL, Python, data quality, reconciliation, workflow automation, governance, lineage, source-to-target mapping, and production support with AWS, Snowflake, Databricks, PySpark, dbt, Airflow, Power BI, Git, GitHub, and AI/LLM-assisted engineering.

This portfolio focuses on building reliable and explainable data workflows—from ingestion and transformation through orchestration, validation, monitoring, documentation, and analytical delivery—while preserving the auditability and operational discipline required in enterprise and regulated environments.

---

## Featured Project

### Databricks Lakehouse & Access Modernization Lab

[View the complete project](https://github.com/amyskyestudios/databricks-gleif-lakehouse)

A completed portfolio lab containing:

- a GLEIF legal-entity medallion pipeline
- a representative Microsoft Access modernization pipeline
- Databricks Bronze, Silver, and Gold Delta tables
- trusted, quarantined, duplicate, and superseded-record handling
- source-to-outcome reconciliation controls
- Lakeflow Jobs orchestration and execution evidence
- Delta history and operational auditing
- Power BI semantic measures and reporting
- explicit DAX business logic
- Databricks-to-Power BI refresh validation

### Access Modernization Workflow

The representative modernization workflow translates Access-style reporting
patterns into governed cloud components:

- Access-style exports → Bronze source preservation
- chained transformation queries → Silver PySpark and Spark SQL logic
- exception queries → quarantine and audit tables
- reporting tables → Gold analytical outputs
- macros and scheduled process chains → Lakeflow Job dependencies
- manual control totals → automated reconciliation metrics
- Access and Excel reporting → Power BI measures and visuals

The workflow intentionally includes data-quality and business-grain scenarios
such as:

- multiple internal parties sharing one LEI
- missing and malformed master-data fields
- repeated monthly submissions
- latest-record selection
- superseded-record preservation
- reporting records without a trusted master-data match

### Power BI Reporting Layer

The completed Power BI report connects to the Databricks SQL warehouse through
OAuth and imports four governed Gold tables.

It includes:

- six named DAX KPI measures
- gross exposure by analyst
- party-level traceability
- eight Gold quality controls
- dashboard-to-Gold reconciliation
- successful refresh from Databricks

Validated reporting results include:

| Metric | Result |
|---|---:|
| Trusted parties | 5 |
| Total gross exposure | $4,610,000 |
| Total exceptions | 3 |
| High-risk exposure | $990,000 |
| Review-required parties | 3 |
| Reporting-ready percentage | 80% |

The detailed repository includes architecture notes, notebook source,
validation records, the Power BI report, and the final dashboard image.

---

## Additional Data Engineering Work

### AWS Data Engineering Lab

[View the AWS project](https://github.com/amyskyestudios/aws-data-engineering-lab)

Hands-on AWS data-engineering work focused on cloud services, ingestion,
storage, transformation, orchestration, and practical implementation notes.

### dbt, Airflow, and Data Quality

Portfolio work exploring:

- modular SQL transformations
- dependency-driven workflow orchestration
- repeatable testing
- data-quality controls
- lineage and operational observability

### Snowflake and LLM Engineering

Ongoing refinement areas include:

- Snowflake architecture and analytical workflows
- governed cloud data platforms
- LLM application patterns
- retrieval, evaluation, and responsible automation

---

## Enterprise Foundation

My modernization work is grounded in experience supporting enterprise
Microsoft Access, VBA, SQL, ETL, and reporting workflows.

That experience includes:

- chained Access queries, forms, macros, and VBA procedures
- large operational datasets
- scheduled reporting and snapshot processes
- multi-tab Excel deliverables
- reconciliation and control totals
- production troubleshooting
- manual monitoring and exception handling
- migration of legacy logic into SQL and modern workflow tools

The goal is not to dismiss legacy systems. Those systems often contain years
of valuable business logic.

A successful modernization effort identifies and preserves that logic while
improving:

- scale
- governance
- traceability
- reuse
- testing
- observability
- downstream analytical access

---

## Technology Focus

### Data Platforms and Storage

- Databricks
- Delta Lake
- AWS
- Snowflake
- Microsoft Access

### Transformation and Engineering

- Python
- pandas
- PySpark
- Spark SQL
- SQL
- VBA
- dbt

### Orchestration and Operations

- Lakeflow Jobs
- Apache Airflow
- reconciliation controls
- quarantine and audit patterns
- workflow monitoring

### Analytics and Reporting

- Power BI Desktop
- DAX
- Excel
- reporting marts
- operational and executive reporting

### Development Practices

- Git
- GitHub
- documented validation
- business-grain analysis
- source-to-target reconciliation
- implementation runbooks

---

## Project Philosophy

I build representative, honest prototypes that demonstrate how my existing
enterprise experience maps into modern platforms.

The strongest data solution is not simply the one with the newest technology.
It is the one that:

- understands the business grain
- preserves source lineage
- makes exceptions visible
- reconciles its outputs
- separates trusted and questionable records
- supports repeatable execution
- produces usable downstream data
- can be clearly explained and maintained

---

## Documentation Philosophy

GitHub serves as a searchable professional reference library for:

- architecture decisions
- implementation details
- validation evidence
- troubleshooting notes
- technology responsibilities
- lessons learned
- concise project summaries

The goal is to preserve not only what was built, but why each design decision
was made and what the resulting data represents.

---

## Current Flight Plan

Current areas of continued development include:

- expanding AWS data-engineering implementations
- refining dbt and Airflow workflows
- deepening Snowflake project coverage
- adding automated data-quality thresholds
- exploring deployment and environment automation
- expanding LLM engineering and evaluation modules

---

## Project Links

- [Databricks Lakehouse & Access Modernization Lab](https://github.com/amyskyestudios/databricks-gleif-lakehouse)
- [AWS Data Engineering Lab](https://github.com/amyskyestudios/aws-data-engineering-lab)

_Last updated: July 2026_
