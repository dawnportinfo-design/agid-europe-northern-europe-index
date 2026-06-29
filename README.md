# AGID Northern Europe Index

AGID Northern Europe index for Europe country and territory repository coordination.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-europe-northern-europe-index`
- Stage: `wave-0-index`
- Data readiness: `index-ready`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, or private-key material.

## Scope

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and special
region display policy for Europe address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, private keys, large GIS extracts, map tiles, or
search indexes.

## Related Repositories

- `agid-country-gb` - United Kingdom (GB)
- `agid-country-ie` - Ireland (IE)
- `agid-country-no` - Norway (NO)
- `agid-country-se` - Sweden (SE)
- `agid-country-fi` - Finland (FI)
- `agid-country-dk` - Denmark (DK)
- `agid-country-is` - Iceland (IS)
- `agid-country-ax` - Åland Islands (AX)
- `agid-country-fo` - Faroe Islands (FO)
- `agid-country-gl` - Greenland (GL)
- `agid-country-ee` - Estonia (EE)
- `agid-country-lv` - Latvia (LV)
- `agid-country-lt` - Lithuania (LT)
- `agid-country-sj_sva` - Svalbard (SJ_SVA)
- `agid-country-sj_jan` - Jan Mayen (SJ_JAN)
- `agid-country-gg` - Guernsey (GG)
- `agid-country-je` - Jersey (JE)
- `agid-country-im` - Isle of Man (IM)

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, and
quality gate metadata. Large geography, hydrographic datasets, building
polygons, OSM/Overture extracts, and generated caches must stay in external
content-addressed packs.

## Overseas And Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Overseas-linked,
disputed, or special regions must carry explicit source, license, canonical
region, and display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.
