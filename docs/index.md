# BookStore API Documentation

Welcome to the official documentation for the **BookStore API** â€” a RESTful API for managing books, authors, orders, customers, categories, reviews, and inventory for an online bookstore platform.

## What is the BookStore API?

The BookStore API allows developers to build applications that interact with a fully featured online bookstore system. Whether you are building a mobile app, an e-commerce frontend, or an internal inventory tool, this API provides everything you need.

## Key Features

| Feature | Description |
|---|---|
| Books | Browse, search, create, and manage book listings |
| Authors | Manage author profiles linked to books |
| Orders | Place and track customer orders |
| Customers | Register and manage customer accounts |
| Categories | Organize books by genre and category |
| Reviews | Submit and retrieve customer book reviews |
| Inventory | Track and update stock levels |

## Base URL

All API requests are made to the following base URL:

```
https://api.bookstore.example.com/v1
```

## API Version

The current version of the BookStore API is **v1**. All endpoints are prefixed with `/v1/`.

## Request and Response Format

All request bodies must be in JSON format. All responses are returned as JSON.

```
Content-Type: application/json
Accept: application/json
```

## Authentication

The BookStore API uses API key authentication. Include your API key in every request:

```
Authorization: Bearer YOUR_API_KEY
```

See the [Authentication guide](getting-started/authentication/authentication.md) for details on generating and managing API keys.

## Quick Links

- [Quickstart Guide](getting-started/basics/quickstart.md)
- [Authentication](getting-started/authentication/authentication.md)
- [Books Endpoints](endpoints/books/list-books.md)
- [Orders Endpoints](endpoints/orders/list-orders.md)
- [Error Reference](getting-started/basics/errors.md)
- [OpenAPI Specification](openapi/specification/spec.md)

## OpenAPI Specification

The full OpenAPI 3.0 specification is available at:

```
https://api.bookstore.example.com/v1/openapi.json
```

You can import this into tools like Postman, Insomnia, or Swagger UI for interactive testing.

## Support

For questions and support, contact the developer team at `api-support@bookstore.example.com` or open an issue on the GitHub repository.

Last reviewed: October 2025.
