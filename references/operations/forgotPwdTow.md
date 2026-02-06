# POST /member/forgotPwdTow

**Resource:** [用戶](../resources/.md)
**Operation ID:** `forgotPwdTow`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email` | query | string | Yes |  |
| `captcha` | query | string | Yes |  |
| `newPassword` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

