# GoreeCloud Feeds Protocol Compatibility

## Current compatibility state

No stable or released GoreeCloud Feeds protocol exists, so there is currently no verified server/client compatibility matrix.

## Planned compatibility relationships

- feeds-server should implement accepted server-side versions of contracts owned here.
- feeds-web should consume accepted client-facing versions of contracts owned here.
- future desktop/mobile/other clients should consume the same supported contracts rather than relying on server-private behavior.
- feeds-shared may provide reusable helpers for protocol-adjacent implementation, but it must not become a competing source of protocol authority.

## Compatibility rules

Future compatibility documentation should define:

- supported server protocol versions;
- supported client protocol versions;
- additive-change rules;
- breaking-change rules;
- deprecation periods;
- migration paths;
- capability-negotiation behavior;
- unsupported combinations; and
- exact verification evidence.

No compatibility claim should be inferred from repository existence or shared naming alone.
