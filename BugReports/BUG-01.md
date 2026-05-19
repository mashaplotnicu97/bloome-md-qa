# BUG-01 — Incorrect product price displayed on mobile product page

## Severity
High

## Priority
High

## Environment
- Device: iPhone
- OS: iOS
- Browser: Safari/Chrome Mobile

## Preconditions
User opens the Bloome product page.

## Steps to Reproduce
1. Open https://bloome.md
2. Navigate to the product page
3. Observe the displayed product price

## Actual Result
The product price is displayed as "1,99 MDL".

## Expected Result
The correct product price should be displayed according to the actual product pricing configuration.

## Notes
The displayed price appears unrealistic for the product type and may indicate incorrect pricing configuration or test data remaining in production.
