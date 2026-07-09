---
title: TMT InventoryPro Backend
emoji: 📦
colorFrom: blue
colorTo: indigo
sdk: docker
pinned: false
license: mit
---

# TMT InventoryPro Backend

FastAPI backend for the Inventory Management System.

## Features

- JWT Authentication
- Product, Category, Supplier Management
- Stock IN/OUT Transactions
- Dashboard Analytics
- Reports Generation

## API Documentation

Once deployed, visit `/docs` for interactive API documentation.

## Environment Variables

Set these in the Space settings:

```
DATABASE_URL=sqlite:///./inventory.db
JWT_SECRET=your-secret-key-here
```

## Deployment

This Space uses Docker. The backend runs on port 7860.
