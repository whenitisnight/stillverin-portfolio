# Architecture

The TypeScript domain model validates inputs, represents amounts in integer cents and runs deterministic checks. Rules are associated with a customer and must move through rehearsal and publication before becoming active. The system does not infer legal or tax requirements.

An authenticated, owner-scoped API stores workspace state atomically in D1 with revision checks. The interface exposes the rule lifecycle, examples, batches and audit context. Demo behavior uses isolated in-memory fixtures instead of seeding a real workspace.

Recovery data is validated, and recovered rules require a new publication decision. The deployment relies on the platform authentication boundary; forwarding identity headers from an untrusted proxy would invalidate that assumption. Private operational documentation records the hosting constraints.
