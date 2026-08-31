# Subscription Evidence

## The management question

Does the tenant show evidence of a separately purchased Copilot subscription, and does its capacity appear to be assigned?

Microsoft 365 subscription inventory can support that question, but only within defined boundaries.

## What it can establish

A validated inventory can show:

- subscriptions visible in the tenant;
- their reported status;
- purchased or enabled capacity;
- aggregate consumed capacity.

## What it cannot establish

Subscription evidence alone does not identify:

- assigned users;
- direct versus group-based assignment;
- the capabilities enabled for each user;
- actual Copilot use;
- access to organizational information;
- whether Copilot is disabled across all surfaces.

Commercial product names, internal identifiers and included capabilities can also differ. A product-specific filter must therefore be interpreted against a successfully retrieved complete inventory.

## Decision table

| Observation | Defensible conclusion | Follow-up |
|---|---|---|
| Complete inventory succeeds; no separately named Copilot subscription appears | No separately named paid Copilot subscription was detected | Review recorded activity before discussing non-use or disablement |
| Copilot subscription appears with no consumed capacity | Subscription capacity exists, but aggregate assignment was not observed | Confirm user and group assignment paths if material |
| Copilot subscription appears with consumed capacity | Paid licensing appears to be assigned | Identify users, approval, purpose and actual use |
| Inventory fails or is implausibly empty | No conclusion can be drawn | Correct the evidence-collection failure |

## Recommended practice

Retain evidence that the complete inventory succeeded before relying on an empty product-specific result. Keep subscription, assignment and usage conclusions separate.

> “No paid Copilot subscription was detected” may be supportable. “Copilot is unavailable” requires additional evidence.
