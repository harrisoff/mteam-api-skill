# POST /member/sendEmailCode

**Resource:** [用戶](../resources/.md)
**Operation ID:** `sendEmailCode`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone` | query | enum: AccountVerifiy, ForgotPwd, TwoStepSuspend... | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |

