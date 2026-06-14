# PayPal GraphQL Schema

## Overview

This conceptual GraphQL schema represents the PayPal payments platform surface, covering REST APIs for Orders, Payments, Payouts, Subscriptions, Invoicing, Reporting, Disputes, Shipping Tracking, Vault/Tokens, Webhooks, and Identity.

PayPal does not currently offer a public GraphQL endpoint. This schema is a conceptual mapping of the PayPal REST API domain model into GraphQL types, intended to support tooling, documentation, and API design exploration.

- Provider: PayPal
- Source: https://developer.paypal.com/docs/api/
- GitHub: https://github.com/paypal
- Schema file: paypal-schema.graphql

## Domain Coverage

### Orders and Checkout

The Orders domain models the full lifecycle of a PayPal checkout session. An `Order` contains one or more `PurchaseUnit` objects, each with an `AmountBreakdown`, `Shipping` details, and references to captures or authorizations. Payment sources include `CardPaymentSource`, `PayPalPaymentSource`, and `VenmoPaymentSource`, as well as alternative payment methods: `BLIK`, `iDEAL`, `SEPA`, `P24`, `Bancontact`, `MultiBanco`, `Eps`, `Giropay`, `Mybank`, `Sofort`, and `PayLater`.

### Payments

The Payments domain covers `Authorization`, `Capture`, and `Refund` objects tied to purchase units. Authorizations can be captured or voided; captures can be refunded.

### Payouts

The Payouts domain supports mass disbursement via `PayoutBatch`, `PayoutItem`, and `PayoutItemDetails`. Batches are submitted asynchronously and polled for status.

### Subscriptions and Billing

The Subscriptions domain covers recurring billing via `Plan`, `BillingCycle`, `PricingScheme`, `Subscription`, `BillingPreferences`, `ShippingPreferences`, `PaymentPreferences`, and `Taxes`.

### Invoicing

The Invoicing domain covers `Invoice`, `InvoiceItem`, `InvoiceTemplate`, `Invoicer`, and `RecipientInfo`. Invoices can be drafted, sent, scheduled, and paid.

### Reporting and Transactions

The Reporting domain covers `Transaction`, `ReportRequest`, `Report`, `ReportMetadata`, `Balance`, and `BalanceCurrency` for historical transaction search, reconciliation, and balance inquiries.

### Disputes

The Disputes domain includes `Dispute`, `DisputeMessage`, and `DisputeEvidence` for managing buyer/seller disputes, providing evidence, escalating to PayPal, and settling.

### Shipping Tracking

The Shipping domain covers `Tracker` and `TrackingInfo` for attaching carrier tracking data to transactions.

### Vault and Payment Tokens

The Vault domain covers `CreditCard`, `VaultedCard`, `PaymentToken`, and `Token` for storing and reusing payment instruments across transactions.

### Products / Catalog

The `ProductCatalog` type represents items registered for use in subscriptions and invoicing.

### Webhooks and Events

The Webhooks domain covers `Webhook` and `WebhookEvent` for event-driven integrations with PayPal payment notifications.

### Identity

The Identity domain covers `IdentityToken`, `UserInfo`, `Address`, `CountryCode`, and `CurrencyCode` for user profile and locale context.

## Type Summary

| Category | Types |
|---|---|
| Orders | Order, OrderItem, PurchaseUnit, AmountBreakdown, PaymentSource |
| Payment Methods | CardPaymentSource, PayPalPaymentSource, VenmoPaymentSource, Token, BLIK, iDEAL, SEPA, P24, Bancontact, MultiBanco, Eps, Giropay, Mybank, Sofort, PayLater |
| Vault | CreditCard, VaultedCard, PaymentToken |
| Payments | Capture, Authorization, Refund |
| Payouts | Payouts, PayoutItem, PayoutBatch, PayoutItemDetails |
| Subscriptions | Subscription, Plan, BillingCycle, PricingScheme, BillingPreferences, ShippingPreferences, PaymentPreferences, Taxes |
| Invoicing | Invoice, InvoiceItem, InvoiceTemplate, Invoicer, RecipientInfo |
| Shipping | Tracker, TrackingInfo |
| Disputes | Dispute, DisputeMessage, DisputeEvidence |
| Reporting | Transaction, ReportRequest, Report, ReportMetadata, Balance, BalanceCurrency |
| Catalog | ProductCatalog |
| Webhooks | Webhook, WebhookEvent |
| Identity | IdentityToken, UserInfo |
| Shared | Address, CountryCode, CurrencyCode, PaymentStatus, Shipping |

Total named types: 58
