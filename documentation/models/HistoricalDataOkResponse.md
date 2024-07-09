# HistoricalDataOkResponse

**Properties**

| Name       | Type                             | Required | Description |
| :--------- | :------------------------------- | :------- | :---------- |
| current    | HistoricalDataOkResponseCurrent  | ❌       |             |
| historical | Historical                       | ❌       |             |
| location   | HistoricalDataOkResponseLocation | ❌       |             |
| request    | HistoricalDataOkResponseRequest  | ❌       |             |

# HistoricalDataOkResponseCurrent

**Properties**

| Name                 | Type      | Required | Description |
| :------------------- | :-------- | :------- | :---------- |
| cloudcover           | float     | ❌       |             |
| feelslike            | float     | ❌       |             |
| humidity             | float     | ❌       |             |
| is_day               | str       | ❌       |             |
| observation_time     | str       | ❌       |             |
| precip               | float     | ❌       |             |
| pressure             | float     | ❌       |             |
| temperature          | float     | ❌       |             |
| uv_index             | float     | ❌       |             |
| visibility           | float     | ❌       |             |
| weather_code         | float     | ❌       |             |
| weather_descriptions | List[str] | ❌       |             |
| weather_icons        | List[str] | ❌       |             |
| wind_degree          | float     | ❌       |             |
| wind_dir             | str       | ❌       |             |
| wind_speed           | float     | ❌       |             |

# Historical

**Properties**

| Name         | Type         | Required | Description |
| :----------- | :----------- | :------- | :---------- |
| \_2015_01_21 | \_2015_01_21 | ❌       |             |
| \_2015_01_22 | \_2015_01_22 | ❌       |             |
| \_2015_01_23 | \_2015_01_23 | ❌       |             |
| \_2015_01_24 | \_2015_01_24 | ❌       |             |
| \_2015_01_25 | \_2015_01_25 | ❌       |             |

# \_2015_01_21

**Properties**

| Name       | Type              | Required | Description |
| :--------- | :---------------- | :------- | :---------- |
| astro      | \_2015_01_21Astro | ❌       |             |
| avgtemp    | float             | ❌       |             |
| date\_     | str               | ❌       |             |
| date_epoch | float             | ❌       |             |
| hourly     | List[Hourly]      | ❌       |             |
| maxtemp    | float             | ❌       |             |
| mintemp    | float             | ❌       |             |
| sunhour    | float             | ❌       |             |
| totalsnow  | float             | ❌       |             |
| uv_index   | float             | ❌       |             |

# \_2015_01_21Astro

**Properties**

| Name              | Type  | Required | Description |
| :---------------- | :---- | :------- | :---------- |
| moon_illumination | float | ❌       |             |
| moon_phase        | str   | ❌       |             |
| moonrise          | str   | ❌       |             |
| moonset           | str   | ❌       |             |
| sunrise           | str   | ❌       |             |
| sunset            | str   | ❌       |             |

# Hourly

**Properties**

| Name                 | Type      | Required | Description |
| :------------------- | :-------- | :------- | :---------- |
| chanceoffog          | float     | ❌       |             |
| chanceoffrost        | float     | ❌       |             |
| chanceofhightemp     | float     | ❌       |             |
| chanceofovercast     | float     | ❌       |             |
| chanceofrain         | float     | ❌       |             |
| chanceofremdry       | float     | ❌       |             |
| chanceofsnow         | float     | ❌       |             |
| chanceofsunshine     | float     | ❌       |             |
| chanceofthunder      | float     | ❌       |             |
| chanceofwindy        | float     | ❌       |             |
| cloudcover           | float     | ❌       |             |
| dewpoint             | float     | ❌       |             |
| feelslike            | float     | ❌       |             |
| heatindex            | float     | ❌       |             |
| humidity             | float     | ❌       |             |
| precip               | float     | ❌       |             |
| pressure             | float     | ❌       |             |
| temperature          | float     | ❌       |             |
| time                 | str       | ❌       |             |
| uv_index             | float     | ❌       |             |
| visibility           | float     | ❌       |             |
| weather_code         | float     | ❌       |             |
| weather_descriptions | List[str] | ❌       |             |
| weather_icons        | List[str] | ❌       |             |
| wind_degree          | float     | ❌       |             |
| wind_dir             | str       | ❌       |             |
| wind_speed           | float     | ❌       |             |
| windchill            | float     | ❌       |             |
| windgust             | float     | ❌       |             |

# \_2015_01_22

**Properties**

| Name       | Type              | Required | Description |
| :--------- | :---------------- | :------- | :---------- |
| astro      | \_2015_01_22Astro | ❌       |             |
| avgtemp    | float             | ❌       |             |
| date\_     | str               | ❌       |             |
| date_epoch | float             | ❌       |             |
| maxtemp    | float             | ❌       |             |
| mintemp    | float             | ❌       |             |
| sunhour    | float             | ❌       |             |
| totalsnow  | float             | ❌       |             |
| uv_index   | float             | ❌       |             |

# \_2015_01_22Astro

**Properties**

| Name              | Type  | Required | Description |
| :---------------- | :---- | :------- | :---------- |
| moon_illumination | float | ❌       |             |
| moon_phase        | str   | ❌       |             |
| moonrise          | str   | ❌       |             |
| moonset           | str   | ❌       |             |
| sunrise           | str   | ❌       |             |
| sunset            | str   | ❌       |             |

# \_2015_01_23

**Properties**

| Name       | Type              | Required | Description |
| :--------- | :---------------- | :------- | :---------- |
| astro      | \_2015_01_23Astro | ❌       |             |
| avgtemp    | float             | ❌       |             |
| date\_     | str               | ❌       |             |
| date_epoch | float             | ❌       |             |
| maxtemp    | float             | ❌       |             |
| mintemp    | float             | ❌       |             |
| sunhour    | float             | ❌       |             |
| totalsnow  | float             | ❌       |             |
| uv_index   | float             | ❌       |             |

# \_2015_01_23Astro

**Properties**

| Name              | Type  | Required | Description |
| :---------------- | :---- | :------- | :---------- |
| moon_illumination | float | ❌       |             |
| moon_phase        | str   | ❌       |             |
| moonrise          | str   | ❌       |             |
| moonset           | str   | ❌       |             |
| sunrise           | str   | ❌       |             |
| sunset            | str   | ❌       |             |

# \_2015_01_24

**Properties**

| Name       | Type              | Required | Description |
| :--------- | :---------------- | :------- | :---------- |
| astro      | \_2015_01_24Astro | ❌       |             |
| avgtemp    | float             | ❌       |             |
| date\_     | str               | ❌       |             |
| date_epoch | float             | ❌       |             |
| maxtemp    | float             | ❌       |             |
| mintemp    | float             | ❌       |             |
| sunhour    | float             | ❌       |             |
| totalsnow  | float             | ❌       |             |
| uv_index   | float             | ❌       |             |

# \_2015_01_24Astro

**Properties**

| Name              | Type  | Required | Description |
| :---------------- | :---- | :------- | :---------- |
| moon_illumination | float | ❌       |             |
| moon_phase        | str   | ❌       |             |
| moonrise          | str   | ❌       |             |
| moonset           | str   | ❌       |             |
| sunrise           | str   | ❌       |             |
| sunset            | str   | ❌       |             |

# \_2015_01_25

**Properties**

| Name       | Type              | Required | Description |
| :--------- | :---------------- | :------- | :---------- |
| astro      | \_2015_01_25Astro | ❌       |             |
| avgtemp    | float             | ❌       |             |
| date\_     | str               | ❌       |             |
| date_epoch | float             | ❌       |             |
| maxtemp    | float             | ❌       |             |
| mintemp    | float             | ❌       |             |
| sunhour    | float             | ❌       |             |
| totalsnow  | float             | ❌       |             |
| uv_index   | float             | ❌       |             |

# \_2015_01_25Astro

**Properties**

| Name              | Type  | Required | Description |
| :---------------- | :---- | :------- | :---------- |
| moon_illumination | float | ❌       |             |
| moon_phase        | str   | ❌       |             |
| moonrise          | str   | ❌       |             |
| moonset           | str   | ❌       |             |
| sunrise           | str   | ❌       |             |
| sunset            | str   | ❌       |             |

# HistoricalDataOkResponseLocation

**Properties**

| Name            | Type  | Required | Description |
| :-------------- | :---- | :------- | :---------- |
| country         | str   | ❌       |             |
| lat             | str   | ❌       |             |
| localtime       | str   | ❌       |             |
| localtime_epoch | float | ❌       |             |
| lon             | str   | ❌       |             |
| name            | str   | ❌       |             |
| region          | str   | ❌       |             |
| timezone_id     | str   | ❌       |             |
| utc_offset      | str   | ❌       |             |

# HistoricalDataOkResponseRequest

**Properties**

| Name     | Type | Required | Description |
| :------- | :--- | :------- | :---------- |
| language | str  | ❌       |             |
| query    | str  | ❌       |             |
| type\_   | str  | ❌       |             |
| unit     | str  | ❌       |             |

<!-- This file was generated by liblab | https://liblab.com/ -->
