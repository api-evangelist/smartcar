# Smartcar

Smartcar is a connected vehicle platform that provides a standardized REST API for accessing vehicle data and sending commands to connected cars across multiple OEM vehicle brands through a single integration.

## Overview

The Smartcar Vehicles API enables developers to:

- Read vehicle telemetry: battery level, odometer, location, fuel, engine oil, and diagnostic codes
- Issue vehicle commands: lock/unlock doors, start/stop charging, set charge limit, set navigation destination
- Manage vehicle connections via OAuth 2.0 authorization
- Support both EV and ICE vehicles from dozens of OEMs including Tesla, Ford, BMW, and Honda

## APIs

| API | Description |
|-----|-------------|
| [Smartcar Vehicles API](https://smartcar.com/docs/api/) | Standardized access to connected vehicle data and commands |

## Developer Resources

- **Documentation**: [smartcar.com/docs/api](https://smartcar.com/docs/api/)
- **API Reference**: [smartcar.com/docs/api-reference](https://smartcar.com/docs/api-reference/intro)
- **GitHub**: [github.com/smartcar](https://github.com/smartcar)
- **Postman Collection**: [Smartcar API on Postman](https://www.postman.com/smartcar/smartcar-api/documentation/fqmwehs/smartcar-api)

## Artifacts

### OpenAPI Specifications
- [Smartcar Vehicles API](openapi/smartcar-vehicles-openapi.yml) — Full OpenAPI spec for vehicle data and commands

### Spectral Rules
- [Smartcar Rules](rules/smartcar-rules.yml) — Spectral ruleset enforcing Smartcar API conventions

### Capabilities
- [Connected Vehicle Management](capabilities/connected-vehicle-management.yaml) — Unified workflow for vehicle telemetry, charging, security, and navigation

### JSON Schema
- [Vehicle Schema](json-schema/smartcar-vehicle-schema.json) — Schema for connected vehicle entities
- [Battery Schema](json-schema/smartcar-battery-schema.json) — Schema for EV battery status

### JSON Structure
- [Vehicles API Structure](json-structure/smartcar-vehicles-structure.json) — Hierarchical resource structure documentation

### JSON-LD
- [Smartcar Context](json-ld/smartcar-context.jsonld) — Linked data context mapping vehicle concepts to schema.org

### Examples
- [Get Vehicle](examples/smartcar-get-vehicle-example.json) — Example request/response for vehicle attributes
- [Get Battery Level](examples/smartcar-get-battery-level-example.json) — Example EV battery status retrieval
- [Lock Vehicle](examples/smartcar-lock-vehicle-example.json) — Example lock command

### Vocabulary
- [Smartcar Vocabulary](vocabulary/smartcar-vocabulary.yml) — Connected vehicle domain terminology

## Tags

Automotive, Connected Vehicles, IoT, Mobility, Fleet Management, EV Management, Telematics
