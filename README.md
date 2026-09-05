# Colorado standing watch

Not a storefront. Not a dry-run theater.

## What is live
Daily automation checks IDs in `entities.txt` only.
- File empty → output is EMPTY LIST. No fake company.
- ID present → PING only if not Good Standing or window ≤ 30 days. Else QUIET.
- Never files. Never logs into SOS.

## How a real ID gets here
1. Someone pays Square $49/year (link goes in PAYMENT.md when it exists).
2. Checkout custom field: 11-digit Colorado SOS entity ID.
3. Director or bot types ADD ID <number> after payment is visible in Square.
4. That ID is appended to entities.txt.

Do not use the operator's own LLC. Not required.

## Not this project
Upwork, Freelancer, sheet-cleaner $500 page, Thousand Lines guestbook.
