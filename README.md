# MC Loyalty Rewards API

Mastercard Loyalty Rewards — points earning, redemption, partner offers, and reward catalog.

## Endpoints
| Method | Path | Description |
|--------|------|-------------|
| GET | /api/v1/members/{id}/balance | Get loyalty points balance |
| POST | /api/v1/members/{id}/earn | Earn points from transaction |
| POST | /api/v1/members/{id}/redeem | Redeem points for rewards |
| GET | /api/v1/rewards/catalog | Browse reward catalog |
| GET | /api/v1/partners | List partner merchants |
| GET | /health | Health check |

## Register in MSBX Portal
Use this URL to register this API in the Backstage catalog:
```
https://github.com/MSBXDemo/mc-loyalty-rewards-api/blob/main/catalog-info.yaml
```

## Owner
payments-engineering | MC Payments Network