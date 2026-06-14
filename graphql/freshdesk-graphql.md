# Freshdesk GraphQL API

Freshdesk is a customer support and helpdesk platform developed by Freshworks. It provides a REST API (v2) as its primary programmatic interface. Freshdesk does not offer a native public GraphQL endpoint — all official API access is provided through the versioned REST API. The schema in `freshdesk-schema.graphql` is a conceptual data model derived from the Freshdesk REST API surface, provided for catalog enrichment, SDL tooling, code generation, and mock server use.

**Endpoint:** No native endpoint - conceptual schema

**Documentation:** https://developers.freshdesk.com/api/

## References

- Freshdesk REST API Docs: https://developers.freshdesk.com/api/
- Freshworks GitHub: https://github.com/freshworks
- Base URL: `https://yourdomain.freshdesk.com/api/v2`
- Authentication: API key (HTTP Basic — key as username, any string as password)
- Freshdesk Developer Portal: https://developers.freshdesk.com/
