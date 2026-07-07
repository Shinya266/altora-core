
Runtime Concept

Altora Core treats runtime behavior as inspectable state.

Instead of hiding model failure, fallback behavior, or route decisions, the system exposes them through metadata.

Example Runtime Metadata

requested_useCore: true
final_useCore: false
route_reason: local_only_fallback
fallback_class: local_only
model_error: null

Runtime States

Possible high-level runtime states:

core route requested
model route completed
local fallback used
quota fallback used
runtime gate blocked
human review required
degraded mode active
Local Fallback

Local fallback allows the runtime to continue producing structural metadata even when an external model is unavailable.

Useful for:

testing
debugging
deterministic inspection
quota-safe development
offline architecture validation
