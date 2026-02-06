# POST /seek/take

**Resource:** [求種](../resources/.md)
**Operation ID:** `take`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `seekId` | query | integer (int64) | Yes |  |
| `takeIds` | query | integer[] | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

