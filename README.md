# RentFlow Full-Stack Project Structure

Starter repository structure for the RentFlow property-management platform.

## Main applications
- `frontend/` — React/Next-style web UI for Admin, Property Owner, and Tenant portals.
- `backend/` — Node.js REST API, authentication/RBAC, business logic, PostgreSQL access, payments, maintenance, and documents.
- `docs/` — requirements, architecture, API and database documentation.
- `infra/` — Docker, reverse proxy and cloud/IaC configuration.
- `.github/workflows/` — CI/CD pipelines.

## Suggested implementation order
1. Authentication + RBAC
2. Users/owners/tenants
3. Properties + units
4. Leases
5. Payments
6. Maintenance
7. Tenant/legal documents
8. Notifications + reports
9. Production deployment and observability
