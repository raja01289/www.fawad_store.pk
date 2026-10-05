# Fawad Sports — Production-ready baseline

A small full-stack sports shop for football, cricket, jerseys, shoes and accessories.

## Included
- Real SQLite database for products and orders
- Secure-ish admin baseline: bcrypt password hash, random session tokens, Helmet, rate limiting, validation
- Admin product add/delete and order status management
- Customer cart and Cash on Delivery checkout
- WhatsApp order handoff to 923405049439
- Product image upload endpoint (JPG/PNG/WebP, max 3 MB)
- Responsive storefront

## Run
1. Install Node.js 20+.
2. Copy `.env.example` to `.env`.
3. Set a long random `SESSION_SECRET` and a strong `ADMIN_PASSWORD`.
4. Run `npm install` then `npm start`.
5. Open `http://localhost:3000`.

## Important
This is a security-focused production baseline, not a guarantee of perfect security. Before public launch, use HTTPS, strong unique secrets, regular dependency updates, database backups, and a trusted host. Online card/mobile-wallet payments are intentionally not enabled until you create a merchant account and add that gateway's official credentials/API flow. Never collect raw card numbers in this app.
