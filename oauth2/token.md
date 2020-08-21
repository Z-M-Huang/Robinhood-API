# /oauth2/token/

## Request POST:

```
{
  "grant_type": "password",
  "scope": "internal",
  "client_id": "c82SH0WZOsabOXGP2sxqcj34FxkvfnWRZBKlBjFS",
  "expires_in": 86400,
  "username": "xxxx@example.com",
  "password": "securePassword"
}
```

grant_type: "password", "sms", "email"

## Response:

```
{
  "access_token": "xxxxxxx",
  "expires_in": 1000907,
  "token_type": "Bearer",
  "scope": "internal",
  "refresh_token": "xxxxxxxx",
  "mfa_code": null,
  "backup_code": null
}
```
