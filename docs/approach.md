---
layout: default
title: Approach
nav_order: 2
---

# Approach

DataRight+ approaches specification groupings in a specific way:
1. **Information Security**: Define the underlying security patterns adopted by the ecosystem often relying on other specifications such as those released by the [FAPI Working Group]. Include specifications related to ecosystem trust establishment.
2. **Actions**: Focus on specific actions with specific outcomes. Typically traverse the boundaries between authentication, authorisation and resource server. May be broad reaching in terms of resource access or very fine-grained.
3. **Data Resource Sets**: Sets of resource server endpoints, usually accessible using course grained permissions, containing large sets of attributes for consumption
4. **Ecosystem Sets**: These specifications are intended to be apex specifications which bind together a variety of specifications across groupings to form an ecosystem deployment. Through the use of ecosystem sets it is possible to bring together various capabilities to result in a functional end-to-end ecosystem while facilitating the gradual enhancement of features through underlying specification development.

In addition, we maintain information documents, notably the DataRight+ Rosetta Stone and generalised API specifications.

## Format

All specifications developed by DataRight+ are in [IETF] RFC format. For API specifications we utilise [Redocly] to publish in [OpenAPI v3.0.3 Specification].


---

[FAPI Working Group]: https://openid.net/wg/fapi/
[Redocly]: https://redocly.com/
[OpenAPI v3.0.3 Specification]: https://spec.openapis.org/oas/v3.0.3
[IETF]: https://www.ietf.org/