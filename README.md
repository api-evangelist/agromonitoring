# Agromonitoring (agromonitoring)

Agromonitoring is a technology company specializing in satellite-based agricultural monitoring. Using Sentinel-2 and Landsat imagery combined with weather and soil data, Agromonitoring provides vegetation index time series (NDVI, EVI, DSWI, LSWI), current weather, multi-day forecasts, and soil conditions for registered field polygons. The platform enables precision agriculture workflows including crop health assessment, irrigation optimization, yield prediction, and climate risk monitoring.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Agriculture
- Satellite Imagery
- Vegetation Indices
- Weather
- Precision Agriculture
- Remote Sensing

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-04-19

## APIs

### Agromonitoring

The Agromonitoring Agro API provides satellite imagery, vegetation index time series (NDVI, EVI, DSWI, LSWI), weather data, soil conditions, and UV index for registered agricultural field polygons. Enables precision agriculture workflows including crop health monitoring, irrigation decision support, and yield optimization.

**Human URL:** [https://agromonitoring.com/](https://agromonitoring.com/)

#### Tags

- Agriculture
- Satellite Imagery
- Vegetation Indices
- Weather
- Precision Agriculture

#### Properties

- [Documentation](https://agromonitoring.com/)
- [APIReference](https://agromonitoring.com/api/)
- [Authentication](https://agromonitoring.com/api/agro/#auth)
- [Pricing](https://agromonitoring.com/subscriptions)
- [OpenAPI](openapi/agromonitoring-openapi.yml)
- [JSONSchema: Polygon](json-schema/agromonitoring-polygon-schema.json)
- [JSONSchema: GeoJson](json-schema/agromonitoring-geojson-schema.json)
- [JSONSchema: SatelliteImage](json-schema/agromonitoring-satelliteimage-schema.json)
- [JSONSchema: NdviRecord](json-schema/agromonitoring-ndvirecord-schema.json)
- [JSONSchema: VegetationStats](json-schema/agromonitoring-vegetationstats-schema.json)
- [JSONSchema: WeatherData](json-schema/agromonitoring-weatherdata-schema.json)
- [JSONSchema: TemperatureRange](json-schema/agromonitoring-temperaturerange-schema.json)
- [JSONSchema: SoilData](json-schema/agromonitoring-soildata-schema.json)
- [JSONSchema: UvIndexData](json-schema/agromonitoring-uvindexdata-schema.json)
- [JSONSchema: PolygonCreateRequest](json-schema/agromonitoring-polygoncreaterequest-schema.json)
- [JSONSchema: ErrorResponse](json-schema/agromonitoring-errorresponse-schema.json)
- [JSONStructure: Polygon](json-structure/agromonitoring-polygon-structure.json)
- [JSONStructure: GeoJson](json-structure/agromonitoring-geojson-structure.json)
- [JSONStructure: SatelliteImage](json-structure/agromonitoring-satelliteimage-structure.json)
- [JSONStructure: NdviRecord](json-structure/agromonitoring-ndvirecord-structure.json)
- [JSONStructure: VegetationStats](json-structure/agromonitoring-vegetationstats-structure.json)
- [JSONStructure: WeatherData](json-structure/agromonitoring-weatherdata-structure.json)
- [JSONStructure: TemperatureRange](json-structure/agromonitoring-temperaturerange-structure.json)
- [JSONStructure: SoilData](json-structure/agromonitoring-soildata-structure.json)
- [JSONStructure: UvIndexData](json-structure/agromonitoring-uvindexdata-structure.json)
- [JSONStructure: PolygonCreateRequest](json-structure/agromonitoring-polygoncreaterequest-structure.json)
- [JSONStructure: ErrorResponse](json-structure/agromonitoring-errorresponse-structure.json)
- [Example: Polygon](examples/agromonitoring-polygon-example.json)
- [Example: GeoJson](examples/agromonitoring-geojson-example.json)
- [Example: SatelliteImage](examples/agromonitoring-satelliteimage-example.json)
- [Example: NdviRecord](examples/agromonitoring-ndvirecord-example.json)
- [Example: VegetationStats](examples/agromonitoring-vegetationstats-example.json)
- [Example: WeatherData](examples/agromonitoring-weatherdata-example.json)
- [Example: TemperatureRange](examples/agromonitoring-temperaturerange-example.json)
- [Example: SoilData](examples/agromonitoring-soildata-example.json)
- [Example: UvIndexData](examples/agromonitoring-uvindexdata-example.json)
- [Example: PolygonCreateRequest](examples/agromonitoring-polygoncreaterequest-example.json)
- [Example: ErrorResponse](examples/agromonitoring-errorresponse-example.json)

## Common Properties

- [Portal](https://agromonitoring.com/)
- [Documentation](https://agromonitoring.com/api/)
- [GettingStarted](https://agromonitoring.com/api/agro/#auth)
- [Pricing](https://agromonitoring.com/subscriptions)
- [FAQ](https://agromonitoring.com/faq/)
- [TermsOfService](https://agromonitoring.com/terms/)
- [PrivacyPolicy](https://agromonitoring.com/privacy/)
- [JSON-LD Context](json-ld/agromonitoring-context.jsonld)
- [SpectralRules](rules/agromonitoring-spectral-rules.yml)
- [Vocabulary](vocabulary/agromonitoring-vocabulary.yaml)
- [NaftikoCapability: API Definitions](capabilities/shared/agromonitoring-api.yaml)
- [NaftikoCapability: Crop Monitoring Workflow](capabilities/crop-monitoring.yaml)

## Features

- **Field Polygon Management** — Register, retrieve, and delete georeferenced agricultural field polygons using GeoJSON geometry
- **Satellite Imagery Search** — Search Sentinel-2 and Landsat satellite archives for cloud-free imagery over registered fields
- **Vegetation Index Time Series** — Access NDVI, EVI, EVI2, NRI, DSWI, and LSWI historical time series to track crop health and stress
- **Current Weather Data** — Real-time weather conditions including temperature, humidity, wind speed, pressure, and cloud cover
- **Weather Forecasting** — Multi-day weather forecasts to support irrigation scheduling and field operation planning
- **Soil Monitoring** — Soil temperature at surface and 10cm depth plus volumetric soil moisture content
- **UV Index Data** — Solar UV radiation index to assess sun exposure and radiation stress on crops

## Use Cases

- **Crop Health Monitoring** — Track vegetation index trends over the growing season to identify stress, disease, or nutrient deficiencies early
- **Irrigation Management** — Combine soil moisture, weather forecast, and NDVI data to optimize irrigation scheduling and reduce water usage
- **Yield Prediction** — Use satellite-derived vegetation indices across the growing season to build yield prediction models
- **Field Boundary Mapping** — Register precise field polygon boundaries for targeted data retrieval and zonal analysis
- **Precision Agriculture** — Apply variable-rate inputs using spatial variability data from satellite imagery and vegetation indices
- **Climate Risk Assessment** — Monitor weather extremes, drought, and soil conditions to assess climate-related agricultural risks

## Integrations

- **OpenWeatherMap** — Agromonitoring uses OpenWeatherMap weather infrastructure for current and forecast data
- **Sentinel-2** — European Space Agency Sentinel-2 satellite data is a primary imagery source
- **Landsat** — NASA/USGS Landsat imagery is available as an additional satellite data source

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
