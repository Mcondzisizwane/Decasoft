# Security Checklist

Use this checklist before tesyt4 is treated as production-ready.

- [ ] No secrets are committed.
- [ ] `.env` files are ignored by Git.
- [ ] Input validation has been considered.
- [ ] Authentication and authorization have been reviewed.
- [ ] Payment workflows are validated server-side where relevant.
- [ ] Audit trails are considered for financial, customer, employee, and operational records.
- [ ] Error messages do not leak sensitive details.
- [ ] Dependencies are reviewed before production use.
- [ ] Provider documentation is verified before production use.
