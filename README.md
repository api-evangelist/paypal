# PayPal (paypal)

PayPal is a global online payment system that lets individuals and businesses send and receive money electronically. PayPal exposes a broad surface of REST APIs covering payments, orders, subscriptions, invoicing, payouts, disputes, payment tokens, shipping tracking, transaction reporting, partner referrals, payment experience, and webhook notifications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paypal/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paypal/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Billing
- Commerce
- Disputes
- Invoices
- Orders
- Payments
- Payouts
- Subscriptions
- Tokens
- Webhooks

## Timestamps

- **Created:** 2024-04-14
- **Modified:** 2026-05-30

## APIs

### PayPal Billing Subscriptions API

The PayPal Billing Subscriptions API enables businesses to create and manage subscription plans, activate, suspend, cancel, capture, and revise customer subscriptions, and track recurring payments.

- **Human URL:** [https://developer.paypal.com/docs/api/subscriptions/v1/](https://developer.paypal.com/docs/api/subscriptions/v1/)

#### Tags

- Activate
- Billing
- Cancel
- Capture
- Plans
- Subscriptions
- Suspend
- Transactions

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/subscriptions/v1/)
- [OpenAPI](openapi/paypal-billing-subscriptions-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Catalog Products API

The PayPal Catalog Products API lets merchants create and manage product definitions used across orders, subscriptions, and invoicing.

- **Human URL:** [https://developer.paypal.com/docs/api/catalog-products/v1/](https://developer.paypal.com/docs/api/catalog-products/v1/)

#### Tags

- Catalog
- Products

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/catalog-products/v1/)
- [OpenAPI](openapi/paypal-catalog-products-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Orders API

The PayPal Orders API lets merchants create, update, authorize, capture, and manage orders for accepting payments through PayPal Checkout.

- **Human URL:** [https://developer.paypal.com/docs/api/orders/v2/](https://developer.paypal.com/docs/api/orders/v2/)

#### Tags

- Checkout
- Orders
- Payments

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/orders/v2/)
- [OpenAPI](openapi/paypal-checkout-orders-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Customer Disputes API

The PayPal Customer Disputes API allows merchants to retrieve, respond to, escalate, and settle disputes raised on transactions, including providing evidence and managing dispute lifecycles.

- **Human URL:** [https://developer.paypal.com/docs/disputes/integration-guide/](https://developer.paypal.com/docs/disputes/integration-guide/)

#### Tags

- Disputes
- Evidence
- Resolution

#### Properties

- [Documentation](https://developer.paypal.com/docs/disputes/integration-guide/)
- [OpenAPI](openapi/paypal-customer-disputes-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Partner Referrals API

The PayPal Partner Referrals API enables platforms and marketplaces to onboard merchants onto PayPal, generate referral links, and track partner account creation status.

- **Human URL:** [https://developer.paypal.com/docs/api/partner-referrals/v1/](https://developer.paypal.com/docs/api/partner-referrals/v1/)

#### Tags

- Onboarding
- Partner
- Referrals

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/partner-referrals/v1/)
- [OpenAPI](openapi/paypal-customer-partner-referrals-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Invoicing API

The PayPal Invoicing API allows merchants to create, send, schedule, track, and manage invoices, including reminders and payment status.

- **Human URL:** [https://developer.paypal.com/docs/api/invoicing/v2/](https://developer.paypal.com/docs/api/invoicing/v2/)

#### Tags

- Billing
- Invoices
- Payments

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/invoicing/v2/)
- [OpenAPI](openapi/paypal-invoicing-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Notification Webhooks API

The PayPal Notification Webhooks API lets developers subscribe to and manage webhook event notifications for payments, refunds, disputes, and other PayPal account activity.

- **Human URL:** [https://developer.paypal.com/api/rest/webhooks/](https://developer.paypal.com/api/rest/webhooks/)

#### Tags

- Events
- Notifications
- Webhooks

#### Properties

- [Documentation](https://developer.paypal.com/api/rest/webhooks/)
- [OpenAPI](openapi/paypal-notification-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](openapi/paypal-webhooks-asyncapi-original.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### PayPal Payment Experience API

The PayPal Payment Experience API lets merchants create web experience profiles to customize the look, feel, and flow of PayPal checkout pages.

- **Human URL:** [https://developer.paypal.com/docs/payment-experience/](https://developer.paypal.com/docs/payment-experience/)

#### Tags

- Checkout
- Customization
- Experience

#### Properties

- [Documentation](https://developer.paypal.com/docs/payment-experience/)
- [OpenAPI](openapi/paypal-payment-experience-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Payments API

The PayPal Payments API lets businesses authorize, capture, refund, void, and reauthorize payments, supporting credit and debit cards as well as PayPal and Venmo wallets.

- **Human URL:** [https://developer.paypal.com/api/rest/](https://developer.paypal.com/api/rest/)

#### Tags

- Authorizations
- Captures
- Payments
- Refunds

#### Properties

- [Documentation](https://developer.paypal.com/api/rest/)
- [OpenAPI](openapi/paypal-payments-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Payouts API

The PayPal Payouts API lets businesses send mass payments to multiple recipients with a single API call, useful for marketplaces, affiliates, rewards programs, and contractor payouts.

- **Human URL:** [https://developer.paypal.com/docs/api/payments.payouts-batch/v1/](https://developer.paypal.com/docs/api/payments.payouts-batch/v1/)

#### Tags

- Mass Pay
- Payouts
- Transfers

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/payments.payouts-batch/v1/)
- [OpenAPI](openapi/paypal-payouts-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Transaction Search (Reporting) API

The PayPal Transaction Search API provides access to historical transaction details, balances, and account activity for reporting, reconciliation, and accounting use cases.

- **Human URL:** [https://developer.paypal.com/docs/api/transaction-search/v1/](https://developer.paypal.com/docs/api/transaction-search/v1/)

#### Tags

- Reconciliation
- Reporting
- Transactions

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/transaction-search/v1/)
- [OpenAPI](openapi/paypal-reporting-transactions-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Shipping Tracking API

The PayPal Shipping Tracking API lets merchants attach, update, and retrieve tracking information on PayPal transactions for faster dispute resolution and improved buyer transparency.

- **Human URL:** [https://developer.paypal.com/docs/tracking/tracking-api/](https://developer.paypal.com/docs/tracking/tracking-api/)

#### Tags

- Carriers
- Shipping
- Tracking

#### Properties

- [Documentation](https://developer.paypal.com/docs/tracking/tracking-api/)
- [OpenAPI](openapi/paypal-shipping-tracking-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PayPal Vault Payment Tokens API

The PayPal Vault Payment Tokens API lets merchants securely store and reuse customer payment instruments as tokens for repeat billing and one-click checkout flows.

- **Human URL:** [https://developer.paypal.com/docs/api/payment-tokens/v3/](https://developer.paypal.com/docs/api/payment-tokens/v3/)

#### Tags

- Tokens
- Vault
- Wallet

#### Properties

- [Documentation](https://developer.paypal.com/docs/api/payment-tokens/v3/)
- [OpenAPI](openapi/paypal-vault-payment-tokens-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/paypal)
- [LinkedIn](https://www.linkedin.com/company/paypal)
- [Website](https://www.paypal.com)
- [Developer  Portal](https://developer.paypal.com)
- [Documentation](https://developer.paypal.com/api/rest/)
- [Authentication](https://developer.paypal.com/api/rest/authentication/)
- [Status Page](https://www.paypal-status.com/)
- [Pricing](https://www.paypal.com/us/business/paypal-business-fees)
- [Terms of Service](https://www.paypal.com/us/legalhub/useragreement-full)
- [Privacy Policy](https://www.paypal.com/us/legalhub/privacy-full)
- [Features](undefined)
- [L L Ms Txt](https://developer.paypal.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
