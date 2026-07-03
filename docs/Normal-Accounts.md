# Normal Accounts

Normal mode may use GE restock planning when enabled.

## Coded-In Normal Account Checks

| Category | Current Script Knowledge |
| --- | --- |
| Coins | Bank/inventory coin visibility is logged with [BANK-CHECK]. |
| Saplings | Highest usable standard and fruit saplings are selected by Farming level, then fallback lists are logged. |
| Compost | Automatic order is Ultracompost, Supercompost, Compost, then Skip. |
| Tools | Spade, rake, seed dibber, and axe-for-chop are validated at bank startup. |
| Protection | Protection items are planned when enabled and skipped gracefully when missing. |
| Transport | Route planner ranks direct item/teleport methods, guild/fairy/spirit/POH routes, then walk fallback. |

## GE Restock Intent

GE restock order:

1. Selected saplings.
2. Compost supplies.
3. Protection items.
4. Transport supplies.
5. Cheaper usable fallbacks when coins are short.

## Current Limits To Keep Tracking

- Live GE purchase execution should be expanded from the current planning/logging layer.
- Price-per-run and per-100k/per-1M projections are shown on overlay once live spend data is recorded.
