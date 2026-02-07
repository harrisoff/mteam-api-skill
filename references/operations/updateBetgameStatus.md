# POST /bet/updateBetgameStatus

**Resource:** [菠菜](../resources/菠菜.md)
**Operation ID:** `updateBetgameStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `gameId` | query | integer (int64) | Yes |  |
| `active` | query | enum: PENDING, LIVE, OVER... | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

