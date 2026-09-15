# SKV Mirror Policy

Purpose: upstream discovery source for SKV External Resource Infrastructure.

```yaml
purpose: upstream_discovery_source
canonical_upstream: public-apis/public-apis
origin_repository: skn2000-arch/public-apis
product_logic_allowed: false
registry_logic_allowed: false
verification_logic_allowed: false
routing_logic_allowed: false
```

## Rules

1. Preserve upstream history and license.
2. Keep SKV-specific modifications minimal.
3. Do not add Registry, Verifier, Router, or Adapter product logic here.
4. Record imported entries in SKV Resource Discovery with source repository and source commit SHA.
5. Treat this repository as replaceable discovery input, never as the SKV source of truth.

Canonical SKV registry: `skn2000-arch/SKV-ExternalResourceRegistry`.
