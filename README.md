# Stack Exchange

Stack Exchange is a network of question-and-answer websites on topics in diverse fields, each site covering a specific topic, where questions, answers, and users are subject to a reputation award process. The network includes over 170 communities including Stack Overflow (programming), Server Fault (system administration), Super User (computing), and many others. The Stack Exchange API v2.3 provides programmatic access to questions, answers, comments, users, tags, badges, and search across all sites in the network.

## Tags

Answers, Code, Community, Developer Tools, Knowledge Base, Q&A, Questions, Stack Exchange

## APIs

### Stack Exchange API

The Stack Exchange API v2.3 provides programmatic access to the Stack Exchange network of Q&A sites. It supports reading and writing questions, answers, comments, tags, users, and badges across all network sites including Stack Overflow. Authentication is via OAuth 2.0 with support for both read and write access. All responses are JSON-encoded and support GZIP compression and field-level filtering.

**Human URL:** [https://api.stackexchange.com/](https://api.stackexchange.com/)

**Base URL:** [https://api.stackexchange.com/2.3](https://api.stackexchange.com/2.3)

#### Properties

- [Documentation](https://api.stackexchange.com/docs)
- [Terms of Service](https://stackexchange.com/legal/api-terms-of-use)
- [Rate Limits](https://api.stackexchange.com/docs/throttle)
- [Sign Up](http://stackapps.com/apps/oauth/register)
- [OpenAPI](openapi/stack-exchange-openapi.yml)

## Common Properties

- [Authentication](https://api.stackexchange.com/docs/authentication)
- [Blog](https://stackoverflow.blog/)
- [Terms of Service](https://stackexchange.com/legal/api-terms-of-use)
- [Rate Limits](https://api.stackexchange.com/docs/throttle)
- [Sign Up](http://stackapps.com/apps/oauth/register)
- [Applications](http://stackapps.com/apps/oauth)
- [JSON-LD](json-ld/stack-exchange-context.jsonld)
- [JSON Schema](json-schema/stack-exchange-question-schema.json)
- [Vocabulary](vocabulary/stack-exchange-vocabulary.yml)
- [Spectral Rules](rules/stack-exchange-rules.yml)

## Capabilities

### Shared Definitions (`capabilities/shared/`)

| File | Description |
|------|-------------|
| [stack-exchange-api.yaml](capabilities/shared/stack-exchange-api.yaml) | Stack Exchange API — questions, search, advanced search, users, tags, and network sites (7 operations) |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [knowledge-discovery.yaml](capabilities/knowledge-discovery.yaml) | Stack Exchange Knowledge Discovery — unified workflow for searching questions, finding experts, browsing tags, and exploring the network (7 REST paths, 8 MCP tools) |
