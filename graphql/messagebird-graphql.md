# MessageBird GraphQL API

MessageBird (now Bird) is a communications platform for SMS, WhatsApp, email, voice, and push notifications. The API covers messaging, conversations, contacts, flows, channels, voice calls, and omnichannel customer communications.

**Endpoint:** No native GraphQL endpoint — conceptual schema derived from MessageBird REST API
**Documentation:** https://developers.messagebird.com/api/

- Reference: https://developers.messagebird.com/api/
- Schema: https://github.com/api-evangelist/messagebird

---

## Probe record (2026-09-17)

Re-probed as part of the enrichment pass. Bird publishes **no GraphQL endpoint**:

| URL | Status |
|---|---|
| https://bird.com/graphql | 404 |
| https://platform.bird.com/graphql | 404 |

`messagebird-schema.graphql` in this directory is a **derived conceptual model** of the REST
surface, not a schema the provider serves. The 18 `type: GraphQL` pointers that previously sat
in `apis.yml` were removed on 2026-09-17: a `GraphQL` pointer asserts a served GraphQL API, and
this one is not served. The real machine-readable contract is
`openapi/messagebird-bird-api-openapi.yml` (OpenAPI 3.1, 277 operations, harvested verbatim from
https://bird.com/openapi.json).
