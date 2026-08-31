# Copilot Interaction Interpretation

## The decision question

What type of Copilot activity was recorded, and is there evidence that organizational information was involved?

A recorded interaction must be classified using the context Microsoft supplied. No single event attribute should determine the finding.

## Classification factors

Consider:

- the Copilot experience and host application;
- the recorded licence context;
- public search or other supporting services;
- whether organizational context was supplied;
- the nature and location of referenced resources;
- missing or ambiguous information.

## Public activity

Public citations about Microsoft 365, SharePoint or OneDrive are not automatically organizational resources. A public webpage concerning OneDrive must not be reported as access to the organization's OneDrive.

When the evidence shows a web-chat experience, public search and public citations with no organizational context, a defensible conclusion is:

> The recorded interaction used public web resources. The inspected event does not provide evidence of organizational-data access.

## Organizational resources

When tenant resources or organizational context appear, the event requires further review. Determine:

- whether the user was authorized;
- whether the access was appropriate for the user's role;
- whether the information was shared too broadly;
- whether sensitivity and information-protection controls applied;
- whether the processing had an approved business purpose.

The presence of an organizational resource is not automatically a breach. It may represent permitted access.

## Incomplete evidence

If event detail is missing or ambiguous, report:

> A Copilot interaction was recorded, but the available evidence is insufficient to determine whether organizational resources were involved.

## Avoid overstatement

One interaction does not establish that Copilot bypassed permissions, exposed the tenant, trained a public model on company information, or caused a reportable incident.
