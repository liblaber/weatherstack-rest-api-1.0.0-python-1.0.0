# Weatherstack Python SDK 1.0.0

Welcome to the Weatherstack SDK documentation. This guide will help you get started with integrating and using the Weatherstack SDK in your project.

## Versions

- API version: `1.0.0`
- SDK version: `1.0.0`

## About the API

REST API service for current weather information, 11-year historical data as well as accurate 14-day weather forecasts.

## Table of Contents

- [Setup & Configuration](#setup--configuration)
  - [Supported Language Versions](#supported-language-versions)
  - [Installation](#installation)
- [Using Union Types](#using-union-types)
- [Services](#services)
- [Models](#models)
- [License](#license)

## Setup & Configuration

### Supported Language Versions

This SDK is compatible with the following versions: `Python >= 3.7`

### Installation

To get started with the SDK, we recommend installing using `pip`:

```bash
pip install weatherstack
```

## Using Union Types

Union types allow you to specify that a variable can have more than one type. This is particularly useful when a function can accept multiple types of inputs. The Union type hint is used for this purpose.

### Example Function with Union Types

You can call service method with an instance of `TypeA`, `TypeB`, or a dictionary that can be converted to an instance of either type.

```python
# Model Definition
ParamType = Union[TypeA, TypeB]

# Service Method
def service_method(param: ParamType):
...

## Usage
type_a = TypeA(key="value")
type_b = TypeB(key="value")

sdk.service.service_method(type_a)
sdk.service.service_method(type_b)
sdk.service.service_method({"key": "value"})
```

You cannot create an instance of a `Union` type itself. Instead, pass an instance of one of the types in the `Union`, or a dictionary that can be converted to one of those types.

## Services

The SDK provides various services to interact with the API.

<details> 
<summary>Below is a list of all available services with links to their detailed documentation:</summary>

| Name                                                                                             |
| :----------------------------------------------------------------------------------------------- |
| [CurrentService](documentation/services/CurrentService.md)                                       |
| [HistoricalService](documentation/services/HistoricalService.md)                                 |
| [ForecastService](documentation/services/ForecastService.md)                                     |
| [AutocompleteLocationLookupService](documentation/services/AutocompleteLocationLookupService.md) |

</details>

## Models

The SDK includes several models that represent the data structures used in API requests and responses. These models help in organizing and managing the data efficiently.

<details> 
<summary>Below is a list of all available models with links to their detailed documentation:</summary>

| Name                                                                                              | Description |
| :------------------------------------------------------------------------------------------------ | :---------- |
| [CurrentLocationOkResponse](documentation/models/CurrentLocationOkResponse.md)                    |             |
| [HistoricalDataOkResponse](documentation/models/HistoricalDataOkResponse.md)                      |             |
| [ForecastDataOkResponse](documentation/models/ForecastDataOkResponse.md)                          |             |
| [AutocompleteOkResponse](documentation/models/AutocompleteOkResponse.md)                          |             |
| [CurrentLocationOkResponse_1](documentation/models/CurrentLocationOkResponse1.md)                 |             |
| [CurrentLocationOkResponse_2](documentation/models/CurrentLocationOkResponse2.md)                 |             |
| [CurrentLocationOkResponse_3](documentation/models/CurrentLocationOkResponse3.md)                 |             |
| [CurrentLocationOkResponse_1Current](documentation/models/CurrentLocationOkResponse1Current.md)   |             |
| [CurrentLocationOkResponse_1Location](documentation/models/CurrentLocationOkResponse1Location.md) |             |
| [CurrentLocationOkResponse_1Request](documentation/models/CurrentLocationOkResponse1Request.md)   |             |
| [CurrentLocationOkResponse_2Current](documentation/models/CurrentLocationOkResponse2Current.md)   |             |
| [CurrentLocationOkResponse_2Location](documentation/models/CurrentLocationOkResponse2Location.md) |             |
| [CurrentLocationOkResponse_2Request](documentation/models/CurrentLocationOkResponse2Request.md)   |             |
| [CurrentLocationOkResponse_3Current](documentation/models/CurrentLocationOkResponse3Current.md)   |             |
| [CurrentLocationOkResponse_3Location](documentation/models/CurrentLocationOkResponse3Location.md) |             |
| [CurrentLocationOkResponse_3Request](documentation/models/CurrentLocationOkResponse3Request.md)   |             |
| [HistoricalDataOkResponseCurrent](documentation/models/HistoricalDataOkResponseCurrent.md)        |             |
| [Historical](documentation/models/Historical.md)                                                  |             |
| [HistoricalDataOkResponseLocation](documentation/models/HistoricalDataOkResponseLocation.md)      |             |
| [HistoricalDataOkResponseRequest](documentation/models/HistoricalDataOkResponseRequest.md)        |             |
| [\_2015_01_21](documentation/models/_2015_01_21.md)                                               |             |
| [\_2015_01_22](documentation/models/_2015_01_22.md)                                               |             |
| [\_2015_01_23](documentation/models/_2015_01_23.md)                                               |             |
| [\_2015_01_24](documentation/models/_2015_01_24.md)                                               |             |
| [\_2015_01_25](documentation/models/_2015_01_25.md)                                               |             |
| [\_2015_01_21Astro](documentation/models/_2015_01_21Astro.md)                                     |             |
| [Hourly](documentation/models/Hourly.md)                                                          |             |
| [\_2015_01_22Astro](documentation/models/_2015_01_22Astro.md)                                     |             |
| [\_2015_01_23Astro](documentation/models/_2015_01_23Astro.md)                                     |             |
| [\_2015_01_24Astro](documentation/models/_2015_01_24Astro.md)                                     |             |
| [\_2015_01_25Astro](documentation/models/_2015_01_25Astro.md)                                     |             |
| [ForecastDataOkResponseCurrent](documentation/models/ForecastDataOkResponseCurrent.md)            |             |
| [Forecast](documentation/models/Forecast.md)                                                      |             |
| [ForecastDataOkResponseLocation](documentation/models/ForecastDataOkResponseLocation.md)          |             |
| [ForecastDataOkResponseRequest](documentation/models/ForecastDataOkResponseRequest.md)            |             |
| [\_2024_03_18](documentation/models/_2024_03_18.md)                                               |             |
| [\_2024_03_19](documentation/models/_2024_03_19.md)                                               |             |
| [\_2024_03_20](documentation/models/_2024_03_20.md)                                               |             |
| [\_2024_03_21](documentation/models/_2024_03_21.md)                                               |             |
| [\_2024_03_22](documentation/models/_2024_03_22.md)                                               |             |
| [\_2024_03_23](documentation/models/_2024_03_23.md)                                               |             |
| [\_2024_03_24](documentation/models/_2024_03_24.md)                                               |             |
| [\_2024_03_18Astro](documentation/models/_2024_03_18Astro.md)                                     |             |
| [\_2024_03_19Astro](documentation/models/_2024_03_19Astro.md)                                     |             |
| [\_2024_03_20Astro](documentation/models/_2024_03_20Astro.md)                                     |             |
| [\_2024_03_21Astro](documentation/models/_2024_03_21Astro.md)                                     |             |
| [\_2024_03_22Astro](documentation/models/_2024_03_22Astro.md)                                     |             |
| [\_2024_03_23Astro](documentation/models/_2024_03_23Astro.md)                                     |             |
| [\_2024_03_24Astro](documentation/models/_2024_03_24Astro.md)                                     |             |
| [AutocompleteOkResponseRequest](documentation/models/AutocompleteOkResponseRequest.md)            |             |
| [Results](documentation/models/Results.md)                                                        |             |

</details>

## License

This SDK is licensed under the MIT License.

See the [LICENSE](LICENSE) file for more details.

<!-- This file was generated by liblab | https://liblab.com/ -->
