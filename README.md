# Elwyn

[Elwyn](https://www.elwyn.org) is a Pennsylvania-headquartered nonprofit human
services organization founded in **1852** and, by its own description, "the
longest-running human services nonprofit of its kind in the nation." It serves
children and adults with intellectual and developmental disabilities, autism,
and behavioral health needs, employing approximately **4,000 staff** across
Pennsylvania, Delaware, New Jersey, and California.

## Mission and Scope

Elwyn was founded in 1852 when James Richards opened an initial classroom, and
was formally chartered in 1853 by Dr. Alfred Elwyn as "The Pennsylvania
Training School for Feeble-Minded Children." In 1857, Dorothea Dix helped
secure state funding and a 300-acre farm in Media, Pennsylvania, which remains
the organization's headquarters campus. In 1876, the first professional
organization for intellectual disabilities in the United States was founded at
Elwyn. Charles S. McLister has served as President and CEO since 2017.

The organization's guiding philosophy is captured in its statement: "We
continue to create opportunities where there once were none."

## Service Lines

Elwyn delivers six core service lines:

1. Adult Behavioral Health Services
2. Children's Behavioral Health Services
3. Crisis Services
4. Early Learning Services
5. Educational Services
6. Intellectual and Developmental Disabilities Services

## API and Developer Surface

Elwyn is a direct-service nonprofit, not a technology provider. The pipeline
crawl of [elwyn.org](https://www.elwyn.org) found:

- **0 public APIs**
- **No OpenAPI or AsyncAPI specifications**
- **No SDKs, CLI, or webhooks**
- **No developer portal**
- **No public open-data feed or status page**

Internal technology (EHR, case management, payroll, scheduling) is not exposed
through any public developer surface. This repository documents the
organization's mission and the absence of any public API surface; no
`openapi/`, `capabilities/`, `json-schema/`, `rules/`, or `examples/`
artifacts are generated because there is no underlying API to model.

## Files

- [`apis.yml`](apis.yml) — APIs.json profile documenting the organization,
  common web properties, and the empty API surface.

## Sources

- <https://www.elwyn.org>
- <https://www.elwyn.org/about-us/>
- <https://www.elwyn.org/our-history/>
- <https://www.elwyn.org/services/>
