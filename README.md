# BESTWIFI Interactive Frontend Demo

## Included interactions
- Dashboard metrics update from demo records.
- Add, edit and delete hotspot packages.
- Generate and copy sample vouchers.
- Customer portal package selection and simulated checkout.
- Demo customer and payment records.
- Save basic business settings in the current browser using localStorage.

## Important limitations
This is an interactive frontend prototype, not a production hotspot system. It does not:
- Send real M-Pesa STK Push requests or verify payments.
- Authenticate customers or grant internet access.
- Integrate with Omada, MikroTik, UniFi, Ruijie or a gateway.
- Store data in a shared cloud database or provide admin login.

Before real launch, add a secure backend/database, admin authentication, M-Pesa Daraja callback verification, and a supported router/gateway controller integration. Keep all API keys and router credentials server-side. Do not use this demo to collect real payments.
