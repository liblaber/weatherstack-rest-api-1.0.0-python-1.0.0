# AutocompleteOkResponse

**Properties**

| Name    | Type                          | Required | Description |
| :------ | :---------------------------- | :------- | :---------- |
| request | AutocompleteOkResponseRequest | ❌       |             |
| results | List[Results]                 | ❌       |             |

# AutocompleteOkResponseRequest

**Properties**

| Name    | Type  | Required | Description |
| :------ | :---- | :------- | :---------- |
| query   | str   | ❌       |             |
| results | float | ❌       |             |

# Results

**Properties**

| Name        | Type | Required | Description |
| :---------- | :--- | :------- | :---------- |
| country     | str  | ❌       |             |
| lat         | str  | ❌       |             |
| lon         | str  | ❌       |             |
| name        | str  | ❌       |             |
| region      | str  | ❌       |             |
| timezone_id | str  | ❌       |             |
| utc_offset  | str  | ❌       |             |

<!-- This file was generated by liblab | https://liblab.com/ -->
