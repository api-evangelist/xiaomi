# Xiaomi

Xiaomi is a multinational technology company headquartered in Beijing, China, that designs, develops, and sells consumer electronics, smart home devices, and related software services. Xiaomi provides developer APIs for account authentication, cloud storage, and AI language models.

**Website:** [https://www.mi.com](https://www.mi.com)  
**Developer Portal:** [https://dev.mi.com](https://dev.mi.com)  
**GitHub:** [https://github.com/XiaoMi](https://github.com/XiaoMi)

## APIs

### Xiaomi Open API
OAuth 2.0 based API for accessing Xiaomi user account data including profile, contact information, friend lists, and identity verification.
- **Documentation:** [https://dev.mi.com/docs/passport/en/open-api/](https://dev.mi.com/docs/passport/en/open-api/)
- **OpenAPI Spec:** [openapi/xiaomi-open-api-openapi.yml](openapi/xiaomi-open-api-openapi.yml)

### Xiaomi Galaxy FDS API
Cloud object storage REST API for managing buckets and objects with multipart upload, ACL, and CDN capabilities.
- **Documentation:** [https://docs.api.xiaomi.com/en/fds/](https://docs.api.xiaomi.com/en/fds/)
- **OpenAPI Spec:** [openapi/xiaomi-galaxy-fds-openapi.yml](openapi/xiaomi-galaxy-fds-openapi.yml)

### Xiaomi MiMo AI API
OpenAI-compatible API for Xiaomi's MiMo large language models including reasoning, coding, multimodal, and TTS variants.
- **Documentation:** [https://platform.xiaomimimo.com/docs/api/chat/openai-api](https://platform.xiaomimimo.com/docs/api/chat/openai-api)
- **OpenAPI Spec:** [openapi/xiaomi-mimo-api-openapi.yml](openapi/xiaomi-mimo-api-openapi.yml)

## Capabilities

### Shared Definitions
- [capabilities/shared/xiaomi-open-api.yaml](capabilities/shared/xiaomi-open-api.yaml) — User identity and OAuth operations
- [capabilities/shared/xiaomi-galaxy-fds.yaml](capabilities/shared/xiaomi-galaxy-fds.yaml) — Cloud object storage operations
- [capabilities/shared/xiaomi-mimo-api.yaml](capabilities/shared/xiaomi-mimo-api.yaml) — MiMo AI model operations

### Workflow Capabilities
- [capabilities/cloud-storage.yaml](capabilities/cloud-storage.yaml) — Cloud storage with user authentication (6 tools)
- [capabilities/ai-language-models.yaml](capabilities/ai-language-models.yaml) — MiMo AI language model integration (2 tools)

## Schemas
- [json-schema/xiaomi-user-profile-schema.json](json-schema/xiaomi-user-profile-schema.json) — User profile schema
- [json-schema/xiaomi-chat-completion-schema.json](json-schema/xiaomi-chat-completion-schema.json) — Chat completion schema

## JSON Structures
- [json-structure/xiaomi-user-profile-structure.json](json-structure/xiaomi-user-profile-structure.json) — User profile structure documentation

## JSON-LD
- [json-ld/xiaomi-context.jsonld](json-ld/xiaomi-context.jsonld) — Linked data context

## Examples
- [examples/xiaomi-get-user-profile-example.json](examples/xiaomi-get-user-profile-example.json) — Get user profile request/response
- [examples/xiaomi-create-chat-completion-example.json](examples/xiaomi-create-chat-completion-example.json) — Create chat completion request/response

## Rules
- [rules/xiaomi-rules.yml](rules/xiaomi-rules.yml) — Spectral ruleset for Xiaomi API conventions

## Vocabulary
- [vocabulary/xiaomi-vocabulary.yml](vocabulary/xiaomi-vocabulary.yml) — Xiaomi API domain vocabulary

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
