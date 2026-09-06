# Swift E-Commerce - API Quickstart

## Setup
```bash
docker-compose up -d
# API: http://localhost:8000
# Frontend: http://localhost:3000
```

## Endpoints
| Method | Endpoint | Description | Auth |
|--------|----------|-------------|------|
| GET | /api/products | List products | No |
| GET | /api/products/:id | Product detail | No |
| POST | /api/cart/add | Add to cart | Yes |
| GET | /api/cart | View cart | Yes |
| POST | /api/orders | Place order | Yes |
| GET | /api/orders | Order history | Yes |

## Search & Filter
```
GET /api/products?search=laptop&category=electronics&min_price=100&sort=-price
```