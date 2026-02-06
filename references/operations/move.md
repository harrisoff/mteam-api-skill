# POST /msg/move

**Resource:** [站內信](../resources/.md)
**Operation ID:** `move`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `boxId` | query | integer (int64) | Yes |  |
| `msgIds` | query | integer[] | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

