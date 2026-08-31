# Reporting Language

## Finding structure

Every management finding should contain:

1. **Observation** — what the evidence showed.
2. **Interpretation** — what it reasonably means.
3. **Boundary** — what was not established.
4. **Action** — the proportionate next step.

## Recommended findings

### No paid subscription and no recorded activity

> No separately named paid Copilot subscription was detected, and no Copilot interaction was returned for the assessed period. This does not establish that every Copilot surface is disabled or that Copilot was never used outside the available evidence period.

### No paid subscription, but activity exists

> No separately named paid Copilot subscription was detected. However, one or more Copilot interactions were recorded. The events require classification to determine the experience used and whether public or organizational resources were involved.

### Public Web Chat activity

> A Copilot Web Chat interaction was recorded. The inspected event used public web resources and contained no recorded organizational context. It demonstrates Copilot Chat use, but not organizational-data access.

### Organizational resources recorded

> A Copilot interaction involving recorded organizational resources was identified. This does not by itself demonstrate unauthorized access or a breach. Authorization, sensitivity, purpose and information-protection controls require review.

### Paid capacity appears assigned

> A paid Copilot subscription with consumed capacity was detected. User assignment, approval, business purpose and actual use remain to be verified.

### Evidence could not be collected

> The requested evidence could not be obtained within the available access or collection conditions. No conclusion should be drawn from the absent result.

## Language to avoid

- “Copilot is disabled.”
- “Copilot has never been used.”
- “No paid licence means no Copilot access.”
- “A Copilot event proves a data leak.”
- “Copilot bypassed permissions.”
- “The tenant is GDPR compliant.”

## Executive summary pattern

> **Objective:** Determine whether paid Microsoft 365 Copilot appears deployed and whether Copilot activity was recorded during the assessed period.  
> **Evidence:** Authorized subscription and audit evidence collected on `[date]` for `[period]`.  
> **Finding:** `[bounded finding]`.  
> **Limitation:** `[material evidence not collected]`.  
> **Decision:** `[accept, investigate, expand scope, restrict or remediate]`.

Severity should reflect actual exposure and control failure—not merely the presence of Copilot activity.
