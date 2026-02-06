# POST /offer/vote

**Resource:** [種子候選](../resources/.md)
**Operation ID:** `vote`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `torrentId` | query | integer (int64) | Yes |  |
| `vote` | query | enum: yeah, against | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

