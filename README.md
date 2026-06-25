# Bytebase (bytebase)

Bytebase is a database DevOps and CI/CD platform - the GitOps-style control plane for schema change, migration, and access management across MySQL, PostgreSQL, and many other engines. Every action in the web console is backed by a documented API exposed as both Connect/gRPC and RESTful HTTP (gRPC transcoding), authenticated with a service-account Bearer token. Bytebase ships as free, self-hostable open source (OSS) with paid Pro and Enterprise tiers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bytebase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bytebase/refs/heads/main/apis.yml)

## Tags

- Database
- DevOps
- Schema Migration
- CI/CD
- DevSecOps

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Bytebase Instances API

Register, list, update, and sync the database instances (and their data sources) that Bytebase manages, plus list the databases discovered on each instance.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Instances
- Data Sources
- Database Servers

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytebase Databases API

Read and update databases, fetch live schema and metadata, list changelogs, diff schemas, and trigger synchronization for databases tracked by Bytebase.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Databases
- Schema
- Metadata

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytebase Projects API

Create, list, update, and delete projects - the organizational units that group databases, members, and database-change workflows in Bytebase.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Projects
- Organization
- Governance

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytebase Issues / Migrations API

Create and track schema-change and data-change issues (the migration review unit in Bytebase), drive approval flows (approve, reject, request), and manage issue comments. Plans organize the proposed changes behind an issue.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Issues
- Migrations
- Schema Change
- Approvals

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytebase Rollouts API

Execute the plan behind an issue by creating and managing rollouts and their tasks - run, skip, or cancel tasks across stages and inspect task-run logs.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Rollouts
- Deployment
- Tasks

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytebase Sheets API

Create and retrieve sheets - the SQL statements / scripts that back plan specs, migrations, and ad-hoc work in a project.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Sheets
- SQL
- Scripts

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytebase Users / Roles API

Manage user accounts (including service accounts), custom roles, and user groups that drive role-based access control across the Bytebase workspace.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Users
- Roles
- Groups
- IAM

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bytebase Webhooks API

Add, update, remove, and test project webhooks that push Bytebase events (issue and rollout activity) to Slack, Discord, Teams, Lark, DingTalk, WeCom, or a custom endpoint.

- **Human URL:** [https://docs.bytebase.com/integrations/api/overview](https://docs.bytebase.com/integrations/api/overview)
- **Base URL:** `https://demo.bytebase.com/v1`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [API Reference](https://api.bytebase.com/)
- [OpenAPI](openapi/bytebase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bytebase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bytebase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/bytebase)
- [LinkedIn](https://www.linkedin.com/company/bytebase)
- [Website](https://www.bytebase.com)
- [Documentation](https://docs.bytebase.com/integrations/api/overview)
- [Plans](plans/bytebase-plans-pricing.yml)
- [Rate Limits](rate-limits/bytebase-rate-limits.yml)
- [Fin Ops](finops/bytebase-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
