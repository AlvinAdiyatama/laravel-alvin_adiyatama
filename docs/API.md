# API Documentation

## Login

### Endpoint

POST /login

### Request

| Parameter | Tipe |
|-----------|------|
| email | string |
| password | string |

### Response

```json
{
    "success": true,
    "message": "Login berhasil"
}
```

---

## Logout

### Endpoint

POST /logout

### Response

```json
{
    "success": true,
    "message": "Logout berhasil"
}
```
