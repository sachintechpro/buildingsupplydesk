# BuildingSupplyDesk

A standalone B2B building-materials distributor demo for contractors, builders and homeowners.

## Included workflows
- Building materials catalog with unit-aware pricing: piece, sheet, bundle, bag, box and roll
- Illustrative contractor pricing
- Sample Chatsworth branch inventory
- Material order requests for branch pickup or jobsite delivery
- Project quote requests
- Admin workspace for orders, quotes and inventory
- SQLite persistence and JSON API
- Responsive storefront and health endpoint

## Run locally
Install dependencies with `pip install -r requirements.txt`, then run `python app.py`. Open http://localhost:5000.

All products, customers, stock and requests are fictional sample data. No real payments, supplier integrations or carrier bookings are connected.

## Render
Build command: `pip install -r requirements.txt`
Start command: `gunicorn app:app`
Health check: `/health`
