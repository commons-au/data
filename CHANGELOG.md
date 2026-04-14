# Changelog

All notable changes to this dataset will be documented in this file.

## [Unreleased]

### Added
- SA GP Plus Locations (8 records)
- SA Private Hospitals (50 records)
- GeoJSON zip fetch support in pipeline

### Changed
- Total records: 24,440 to 24,498

## [v1.0.0] - 2026-04-14

First release of the Open Australian Services Archive (OASA).

### Data
- 24,440 support services across all 8 states and territories
- 25 sources: 24 government open data + OpenStreetMap
- Formats: CSV, JSON, SQLite

### Sources Connected
- Federal: Emergency Relief Provider Outlets, Employment Services, Judicial Courts
- VIC: Melbourne Free Services, Casey Food Relief/Libraries/Maternal Health, Ballarat Food/Community Centres/Kindergartens/Early Learning, Neighbourhood Houses
- QLD: Gov Service Counters, Housing Centres, Housing Finder, BreastScreen, Victim Support, Dispute Resolution, DCCSDS Contacts, Youth Justice, Hep C Centres
- SA: Community Directory, Child and Family Health
- TAS: Service Tasmania Shops
- OSM: Social Facilities, Community Centres, NGOs, Charities

### Quality
- 84% complete (location + contact info)
- 15% partial
- Less than 1% minimal

### Infrastructure
- Automated pipeline (oa-sa/pipeline) for government CKAN data
- Separate OSM pipeline (oa-sa/osm) via Geofabrik extract
- Auto-build workflow in data repo
- Zenodo DOI: 10.5281/zenodo.19564281
