# POST /bet/findBetgameList

**Resource:** [菠菜](../resources/.md)
**Operation ID:** `findBetgameList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `active` | query | enum: PENDING, LIVE, OVER... | Yes |  |
| `fix` | query | integer (int32) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

