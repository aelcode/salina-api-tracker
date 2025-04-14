# Salina API Endpoints

This document tracks all endpoints available in the Salina API staging environment. The information is organized by resource category.

Last updated: 2025-04-14

## Authentication Endpoints

| Endpoint | Method | Description | Status | Notes | Last Tested | Auth Required |
|----------|--------|-------------|--------|-------|-------------|---------------|
| `/auth/login` | POST | User login | Unknown | | - | No |
| `/auth/logout` | POST | User logout | Unknown | | - | Yes |
| `/auth/token` | POST | Get new access token | Unknown | | - | No |

## User Endpoints

| Endpoint | Method | Description | Status | Notes | Last Tested | Auth Required |
|----------|--------|-------------|--------|-------|-------------|---------------|
| `/users` | GET | List all users | Unknown | | - | Yes |
| `/users/{id}` | GET | Get user details | Unknown | | - | Yes |
| `/users` | POST | Create new user | Unknown | | - | Yes |
| `/users/{id}` | PUT | Update user | Unknown | | - | Yes |
| `/users/{id}` | DELETE | Delete user | Unknown | | - | Yes |

## Product Endpoints

| Endpoint | Method | Description | Status | Notes | Last Tested | Auth Required |
|----------|--------|-------------|--------|-------|-------------|---------------|
| `/products` | GET | List all products | Unknown | | - | Yes |
| `/products/{id}` | GET | Get product details | Unknown | | - | Yes |
| `/products` | POST | Create new product | Unknown | | - | Yes |
| `/products/{id}` | PUT | Update product | Unknown | | - | Yes |
| `/products/{id}` | DELETE | Delete product | Unknown | | - | Yes |

## Order Endpoints

| Endpoint | Method | Description | Status | Notes | Last Tested | Auth Required |
|----------|--------|-------------|--------|-------|-------------|---------------|
| `/orders` | GET | List all orders | Unknown | | - | Yes |
| `/orders/{id}` | GET | Get order details | Unknown | | - | Yes |
| `/orders` | POST | Create new order | Unknown | | - | Yes |
| `/orders/{id}` | PUT | Update order | Unknown | | - | Yes |
| `/orders/{id}` | DELETE | Delete order | Unknown | | - | Yes |

## Status Definitions

- **Working**: Endpoint functions as expected
- **Issues**: Endpoint works but has known issues (see linked issue)
- **Unknown**: Endpoint status has not been verified
- **Deprecated**: Endpoint is no longer supported or will be removed
- **Planned**: Endpoint is documented but not yet implemented