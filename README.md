# Awesome-Web-Analytics

### Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Web-Analytics

## Top Web Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Website Traffic Measurement, Product Analytics, Privacy-First Tracking & Cookieless Insights*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Web Analytics**. These systems measure visits, events, funnels, and user behavior—from classic pageview stats to full product analytics—while increasingly emphasizing privacy and data ownership.



**Examples** include Google Analytics, Adobe Analytics, Matomo Cloud, Mixpanel, Amplitude, Heap, Fathom Analytics, Plausible, Simple Analytics, Woopra, and **Umami** (`umami-software/umami`)—simple, fast, privacy-focused website analytics.



**Open-source emphasis**: Privacy-oriented web analytics is rich in open source. **Matomo**, **Umami**, **Plausible**, **PostHog**, **Open Web Analytics**, and **Countly** enable self-hosted measurement. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Google Analytics, Adobe Analytics](https://analytics.google.com/)**  

  Enterprise-scale web and marketing analytics platforms—deep integrations with ad ecosystems and large reporting suites.



- **[Mixpanel, Amplitude, Heap](https://mixpanel.com/)**  

  Product analytics platforms focused on events, funnels, retention, and user paths for digital products.



- **[Matomo Cloud, Plausible Cloud, Fathom, Simple Analytics](https://matomo.org/)**  

  Privacy-friendly hosted analytics—lighter scripts, fewer cookies, and GDPR-oriented positioning.



- **[Woopra and other behavioral analytics](https://www.woopra.com/)**  

  Additional customer journey and real-time analytics services.



- **[Other commercial web analytics platforms](https://www.amplitude.com/)**  

  Marketing attribution and experience analytics suites.



## Open-Source GitHub Projects



### Privacy-First & Website Analytics



- **[Umami](https://github.com/umami-software/umami)**  

  Simple, fast, privacy-focused open website analytics—lightweight script, self-hostable, and cookieless-friendly.



- **[Matomo](https://github.com/matomo-org/matomo)**  

  Leading full-featured open analytics platform—on-premise Google Analytics alternative with goals, heatmaps (plugins), and ownership of raw data.



- **[Plausible Analytics](https://github.com/plausible/analytics)**  

  Open lightweight, privacy-first web analytics—simple dashboard, no cookies by default, and easy self-hosting.



- **[Open Web Analytics (OWA)](https://github.com/Open-Web-Analytics/Open-Web-Analytics)**  

  Open self-hosted web analytics with heatmaps, session tracking, and traditional reporting.



- **[GoatCounter](https://github.com/arp242/goatcounter)**  

  Open simple web statistics—privacy-aware and suitable for personal and small sites.



- **[Ackee](https://github.com/electerious/Ackee)**  

  Open self-hosted analytics tool focused on privacy and a clean Node.js stack.



### Product Analytics & Event Platforms



- **[PostHog](https://github.com/PostHog/posthog)**  

  Open-source product analytics—events, funnels, session replay, feature flags, and experiments; strong self-host option.



- **[Countly](https://github.com/Countly/countly-server)**  

  Open product analytics platform for web and mobile—self-hosted or enterprise editions.



- **[RudderStack](https://github.com/rudderlabs/rudder-server)**  

  Open customer data pipeline—collect events and route to warehouses and analytics tools (warehouse-first analytics).



- **[Snowplow](https://github.com/snowplow/snowplow)**  

  Open behavioral data pipeline—high-quality event collection into your own data lake/warehouse.



- **[GoAccess](https://github.com/allinurl/goaccess)**  

  Open real-time web log analyzer—terminal and HTML reports from server logs without client-side scripts.



### Additional Strong Open-Source Options



- **Simple privacy web stats**: Umami or Plausible.

- **Full GA-style suite**: Matomo.

- **Product analytics**: PostHog or Countly.

- **Warehouse-native**: Snowplow or RudderStack + BI.

- **Log-based**: GoAccess for server-side only measurement.

- **Composable stacks**: Open tracker → your DB/warehouse → dashboard; or Matomo/Umami all-in-one.

- Commercial platforms still lead for ad-ecosystem integration, massive scale defaults, and turnkey marketing reports.



**Frameworks for building custom systems**:  

**Umami** / **Plausible** / **Matomo** for website analytics you own; **PostHog** for product analytics and replay; **Snowplow** / **RudderStack** when the warehouse is the system of record.  

Fully open web analytics stacks are production-ready and widely used for GDPR-sensitive deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Analytics involves personal data. Honor consent, privacy policy disclosures, and regulations (GDPR, ePrivacy, CCPA). Prefer privacy-by-design trackers and data minimization. Self-hosting shifts compliance responsibility to you.

- Open-source analytics offer data ownership and transparency. Commercial platforms shift infrastructure and support to the vendor. Neither replaces ethical measurement practices and clear user notice.



---



**Made for marketers, product teams, and privacy-conscious site operators.**  

Let's expand open web analytics while recognizing the scale and ecosystem integrations that leading commercial analytics platforms deliver.
