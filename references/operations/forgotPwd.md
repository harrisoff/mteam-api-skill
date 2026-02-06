# POST /member/forgotPwd

**Resource:** [用戶](../resources/.md)
**Operation ID:** `forgotPwd`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email` | query | string | Yes |  |
| `captchaId` | query | string | Yes |  |
| `captcha` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

