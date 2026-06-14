# 8base FinOps

Source: https://www.8base.com/pricing

## Cost Model

8base uses a per-project, subscription-based pricing model. Each project provisioned receives its own computing, storage, database, and GraphQL engine resources. You pay per project, enabling separate production-grade and development-grade environments billed independently.

## Plan Costs

| Plan         | Cost                                      |
|--------------|-------------------------------------------|
| Free         | $0/month                                  |
| Developer    | $25/month                                 |
| Professional | $50/developer/month (min. 3 developers)   |
| Enterprise   | $75/developer/month (min. 10 developers)  |

## Minimum Monthly Spend

| Plan         | Minimum Monthly Cost |
|--------------|----------------------|
| Free         | $0                   |
| Developer    | $25                  |
| Professional | $150 (3 developers)  |
| Enterprise   | $750 (10 developers) |

## Key Cost Drivers

- **GraphQL API Calls:** High-traffic applications on Developer/Professional plans should watch monthly API call counts; overages are $10–$12 per 100K–1M calls.
- **Serverless Computing:** GB-Hours consumed by custom functions are a primary variable cost; overages range from $0.40–$0.50/GB-Hour.
- **Database Rows:** Applications with large datasets should plan for overage costs of $6–$10 per 100K additional rows.
- **Bandwidth:** Data-intensive apps should monitor monthly egress; overages are $0.30–$0.35/GB.
- **File Storage:** Media-heavy applications should track storage usage; overages are $0.75–$0.95/GB.
- **Client App Users:** User-facing applications should factor in per-user costs at $0.01/user beyond tier limits.

## Cost Optimization Recommendations

- Use the Free plan for prototyping and proof-of-concept work before committing to paid tiers.
- Separate production and development projects to control compute and API costs independently.
- Monitor monthly API call counts closely on Developer plan ($25/month base with $10/100K overage) — high-traffic apps can see costs escalate quickly.
- Leverage the Professional plan's lower overage rates for production workloads with predictable but high volume.
- Negotiate enterprise contracts with invoice-based billing for large team deployments.
- Consider agency pricing (https://www.8base.com/pricing-agencies) for multi-client project portfolios.

## Compliance Add-on Costs

- HIPAA, GDPR, and SOC2 compliance are available as add-ons on Developer and Professional plans (pricing not publicly listed).
- On Enterprise, compliance is included in the base rate.

## SLA Costs

- 99.5% uptime SLA available as an add-on on Professional plan (pricing not publicly listed).
- 99.999% uptime SLA is included in the Enterprise plan.

## Payment

- Monthly subscription via credit/debit card (Amex, Visa, Mastercard, Discover).
- Invoice-based billing available for Enterprise contracts.
