# Singapore Miles Card Recommender

A mobile-friendly static web app that recommends a credit card for a Singapore transaction based on expected miles.

## Inputs
- Cardholder (C or M)
- Transaction amount and merchant
- Spend category
- Online vs in-store channel
- Payment method
- Local vs foreign currency
- Optional MCC
- Bonus-cap spend already used
- UOB Lady's Savings Account MAB

## Output
The app ranks the available cards, shows a primary and backup recommendation, estimates miles, flags relevant caps/caveats, and links to issuer sources.

## Deploy
This repository is a static site. No build command or framework is required. Import the repository into Vercel and deploy from the repository root.

## Important
Reward rates, MCC treatment, exclusions, monthly caps and promotions can change. Confirm high-value transactions against the issuer's current terms and conditions.
