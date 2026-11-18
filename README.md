# Task Manager — Allegro API Integration

Task Manager is a private, locally hosted application designed for task management and sales analysis.

## Allegro API Integration

The application uses the official Allegro REST API to retrieve:

- Active sales offers and their available quantities.
- Product names, offer identifiers and prices.
- Customer orders and sales quantities.
- Historical sales data for reporting and inventory monitoring.

## Access and Security

The integration is intended exclusively for the account owner's internal use.

- Read-only access to offers and orders.
- OAuth 2.0 authentication.
- No modification of Allegro offers, prices or orders.
- No public access to sales reports or account data.
- Application data is stored locally.

## Purpose

The integration enables the account owner to monitor Allegro sales, review offer availability and identify products with low stock.

This repository contains only public information about the integration. It does not contain application source code, authentication credentials or business data.
