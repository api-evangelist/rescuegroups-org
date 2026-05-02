# RescueGroups.org

RescueGroups.org provides the only updatable HTTP/JSON API for adoptable pet data, offering comprehensive search across animals, organizations, breeds, species, colors, and patterns with geodistance filtering. The API supports both public read-only access via API key and authenticated write access via bearer token, enabling rescue organizations to manage and share pet adoption data in real time.

**URL:** [https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/apis.yml)

## Tags

Animals, Pet Adoption, Rescue, Animal Welfare

## APIs

### RescueGroups.org API

The RescueGroups.org REST API v5 provides access to adoptable pet data including animals, organizations, breeds, species, colors, and patterns. Supports advanced search with geodistance filtering, pagination, and relationship inclusion.

- **Base URL:** https://api.rescuegroups.org/v5
- **Authentication:** API Key (public) / Bearer Token (private/write)
- **Human URL:** [https://rescuegroups.org/services/adoptable-pet-data-api/](https://rescuegroups.org/services/adoptable-pet-data-api/)

#### Properties

- [Documentation](https://userguide.rescuegroups.org/spaces/APIDG/pages/24053254/v5)
- [OpenAPI](openapi/rescuegroups-org-openapi.yml)
- [PostmanCollection](https://documenter.getpostman.com/view/60615/SWT5j1e4)
- [JSONSchema - Animal](json-schema/rescuegroups-org-animal-schema.json)
- [JSONSchema - Organization](json-schema/rescuegroups-org-organization-schema.json)
- [JSONStructure - Animal](json-structure/rescuegroups-org-animal-structure.json)
- [JSONLDContext](json-ld/rescuegroups-org-context.jsonld)
- [SpectralRules](rules/rescuegroups-org-rules.yml)
- [Capabilities](capabilities/pet-adoption-search.yaml)
- [Vocabulary](vocabulary/rescuegroups-org-vocabulary.yml)

## Capabilities

- [pet-adoption-search.yaml](capabilities/pet-adoption-search.yaml) — Pet adoption search and rescue organization discovery (REST + MCP, 10 tools)
- [shared/rescuegroups-org.yaml](capabilities/shared/rescuegroups-org.yaml) — Shared per-API definition

## Common Properties

- [Website](https://rescuegroups.org/)
- [Documentation](https://userguide.rescuegroups.org/spaces/APIDG/pages/8192120/API+Developers+Guide+Home)
- [PostmanCollection](https://documenter.getpostman.com/view/60615/SWT5j1e4)
- [CommunityForum](https://groups.google.com/a/rescuegroups.org/g/apidev)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
