# 8base GraphQL API

The 8base GraphQL API provides auto-generated queries, mutations, and subscriptions for every data table in a workspace. Each workspace gets a unique endpoint and receives full CRUD operations out of the box, including filtering, sorting, cursor-based pagination, soft delete/restore, and relational queries. The API also includes built-in system tables (Users, Files, Roles, Permissions, Settings, ApiTokens, EnvironmentVariables, TeamMembers, AuthenticationProfiles) and can be extended with custom serverless resolver functions.

Authentication is via a Bearer JWT token passed in the `Authorization` header. Tokens are obtained through 8base authentication profiles (Auth0, Cognito, or native) or via API tokens generated in the workspace console. Introspection can be toggled on or off per workspace.

**Endpoint:** https://api.8base.com/{workspaceId}

**Documentation:** https://docs.8base.com/backend/graphql-api/

**References:**

- Documentation: https://docs.8base.com/backend/graphql-api/
- Queries: https://docs.8base.com/backend/graphql-api/queries/
- Mutations: https://docs.8base.com/backend/graphql-api/mutations/
- Subscriptions: https://docs.8base.com/backend/graphql-api/subscriptions/
- API Explorer: https://docs.8base.com/backend/console/api-explorer/
- Advanced Introspection: https://docs.8base.com/backend/console/advanced-introspection/
- GettingStarted: https://docs.8base.com/backend/graphql-api/
- GitHub: https://github.com/8base/sdk
