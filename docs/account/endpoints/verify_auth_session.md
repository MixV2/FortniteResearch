# Verify Auth Session
Verifies an existing authentication session. Used to make sure that an authentication session is still active.

## Request
| URL | Method |
| - | - |
| https://account-public-service-prod.ol.epicgames.com/account/api/oauth/verify | `GET` |

## Header
| Header | Value |
| - | - |
| Authorization | bearer {valid_access_token} |

# sample response 
```json
{
    "token": "5e8777d538294428b6824e8ae91d4e97",
    "session_id": "5e8777d538294428b6824e8ae91d4e97",
    "token_type": "bearer",
    "client_id": "98f7e42c2e3a4f86a74eb43fbb41ed39",
    "internal_client": true,
    "client_service": "prod-fn",
    "account_id": "d5f0d9ba072a4fbd91ce6b8236f249d4",
    "expires_in": 7180,
    "expires_at": "2024-10-28T01:17:18.917Z",
    "auth_method": "device_code",
    "display_name": "Tfue",
    "app": "prod-fn",
    "in_app_id": "0f7c792acc5d4d249d5802de77c23814",
    "product_id": "prod-fn",
    "application_id": "fghi4567FNFBKFz3E4TROb0bmPS8h1GW",
    "acr": "urn:epic:loa:aal1",
    "auth_time": "2024-10-27T23:17:19.062Z"
}
```
