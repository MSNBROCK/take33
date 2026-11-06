# Northstar Banking Management System

A responsive **college-project banking dashboard simulation** built with plain HTML, CSS and JavaScript. It is designed for GitHub Pages and requires no build step.

## Important safety note
This is a front-end demonstration only. It does **not** connect to a bank, move money, validate UTRs, verify identity documents, create real KYC records, submit IPO applications, or perform real withdrawals. Do not enter real Aadhaar, PAN, voter ID, bank details, or other sensitive information. All transaction and progress states are illustrative.

## Run locally
1. Download and extract the ZIP.
2. Open `index.html` in a modern browser.
3. Sign in using one of the demo accounts below.

## Admin demo login
- Username: `admin`
- Password: `ADMIN129`

## Client demo logins
| Client | Client ID | Password |
|---|---|---|
| Shreyas | BRCLT-45871293 | SHR129 |
| Zain | BRCLT-797555 | ZAI129 |
| Rana | BRCLT-808835 | RAN129 |
| Nadeem | BRCLT-91274051 | NAD129 |
| Gani | BRCLT-34781926 | GAN129 |
| Dhanush | BRCLT-62845017 | DHA129 |
| Vinayak | BRCLT-73456218 | VIN129 |
| Shabana | BRCLT-SHABANA | SHA129 |
| Devraj | BRCLT-DEVRAJ | DEV129 |
| SAMYAK | BRCLT-974891 | SAM129 |
| Yashvantha | BRCLT-YASHVANTHA | YAS129 |
| NADEEM | BRCLT-NAD129 | 129129 |
| TANVEER | BRCLT-TANVEER | TAN129 |
| Sample Client 14 | BRCLT-SAMPLE014 | SAMPLE14 |

## Included features
- Client login and client dashboard
- Admin dashboard with all 14 client records
- Balance, invested, pending, P/L, shares and next allocation cards
- Simulated withdrawal form with UTR text field, four scroll-gated agreements and dummy KYC fields
- Illustrative 30-day progress timeline and request history
- 24-month sample statement view
- Jio IPO demo order screen (1–6 shares, illustrative ₹1,165–₹1,300 band and 20-month sample lock display)
- CSV export of client summary
- Browser localStorage for demo requests and orders

## Publish on GitHub Pages
1. Sign in to GitHub and create a new **public** repository, for example `northstar-banking-demo`.
2. Extract this ZIP on your computer.
3. Upload `index.html`, `styles.css`, `clients.js`, `app.js`, and `README.md` to the repository root.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait for GitHub Pages to publish. Your site URL will appear in the Pages section.

## Project files
- `index.html` — page structure and forms
- `styles.css` — responsive navy/blue/gold styling
- `clients.js` — seeded demo client records
- `app.js` — login, dashboards, simulated forms, history and CSV export

## Security limitation
This project stores demo data in browser JavaScript and is not suitable for real customer information or financial services. Anyone who can access the source can inspect the demo credentials. A production system needs a secure backend, password hashing, server-side authorization, database controls, audit logs, privacy/security review, and appropriate regulatory/payment integrations.
