# 8base Rate Limits

Source: https://www.8base.com/pricing

8base enforces monthly usage quotas rather than per-second or per-minute rate limits. Limits vary by plan tier.

## GraphQL API Call Limits (per month)

| Plan         | GraphQL API Calls | GraphQL Subscriptions |
|--------------|-------------------|-----------------------|
| Free         | 100,000           | 100,000               |
| Developer    | 1,000,000         | 1,000,000             |
| Professional | 5,000,000         | 5,000,000             |
| Enterprise   | Unlimited         | Unlimited             |

## Compute Limits

| Plan         | Serverless Computing | Bandwidth       |
|--------------|----------------------|-----------------|
| Free         | 1 GB-Hours           | 2 GB/month      |
| Developer    | 20 GB-Hours          | 50 GB/month     |
| Professional | 200 GB-Hours         | 500 GB/month    |
| Enterprise   | Unlimited            | Unlimited       |

## Storage Limits

| Plan         | Database Rows | File Storage |
|--------------|---------------|--------------|
| Free         | 2,500         | 0.5 GB       |
| Developer    | 500,000       | 50 GB        |
| Professional | 5,000,000     | 500 GB       |
| Enterprise   | Unlimited     | Unlimited    |

## Client App User Limits

| Plan         | Client App Users |
|--------------|------------------|
| Free         | 5                |
| Developer    | 1,000            |
| Professional | 10,000           |
| Enterprise   | Unlimited        |

## Overage Pricing

When monthly limits are exceeded on Developer and Professional plans, overage charges apply:

| Resource              | Developer Rate      | Professional Rate   |
|-----------------------|---------------------|---------------------|
| Database Rows         | $10 per 100K rows   | $6 per 100K rows    |
| File Storage          | $0.95/GB            | $0.75/GB            |
| Serverless Computing  | $0.50/GB-Hour       | $0.40/GB-Hour       |
| Bandwidth             | $0.35/GB            | $0.30/GB            |
| API/Subscription Calls| $10 per 100K calls  | $12 per 1M calls    |
| Client App Users      | $0.01 each          | $0.01 each          |

## Notes

- Per-second or per-minute rate limiting details are not publicly documented.
- The GraphQL API endpoint format is `https://api.8base.com/<WORKSPACE_ID>`.
- Free plan has no overage option — service stops at quota limits.
