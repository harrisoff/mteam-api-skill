# POST /dmm/showcase/fetchList

**Resource:** [dmm](../resources/dmm.md)
**Operation ID:** `showcaseFetchList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | integer (int64) | Yes |  |
| `name` | query | string | Yes |  |
| `page` | query | integer (int32) | Yes |  |
| `pageSize` | query | integer (int32) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

