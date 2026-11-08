# NS Eventz Booking Website — UI Prototype

Mobile-first booking page for New Shubharambh Events & Entertainment / Bollywood DJ Night.

## Included
- Dark navy + blue branded booking UI
- Event details: 6 December 2026, 7:00 PM, Swarn Sparsh Resort, Dhule
- Pass prices and free coupon details supplied by the organizer
- Customer form with 18+ validation
- Demo confirmation screen and demo booking reference

## Important: not production-ready
This prototype does **not** take payments, create real tickets, send WhatsApp/SMS, or save bookings to a server. The confirmation is only a local UI demonstration. Do not publish it as a live paid booking page.

## Production integration still required
1. PhonePe Payment Gateway merchant onboarding and production credentials.
2. Secure backend (never put PhonePe salt/API secrets in browser code).
3. Server-side order creation, payment status verification and signed webhook handling, using the current PhonePe PG API documentation.
4. Database for orders, payment status, ticket IDs and idempotency.
5. Generate a unique signed ticket QR only after server-verified successful payment.
6. WhatsApp Business Platform provider/template approval and SMS provider/DLT setup.
7. Admin login, booking search, check-in QR scanner, refund/cancellation policy and deployment with HTTPS.

## Run locally
Open `index.html` in a modern browser. This is a static preview only.

## Official PhonePe documentation
https://developer.phonepe.com/
Website Standard Checkout docs are available from the PhonePe developer portal. API versions, endpoints, request signatures and webhook validation must be implemented against the current documentation and your merchant account configuration.
