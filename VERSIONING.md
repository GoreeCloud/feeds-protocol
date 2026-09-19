# GoreeCloud Feeds Protocol Versioning

## Current state

No GoreeCloud Feeds protocol version has been released or accepted.

The repository is currently unversioned from a protocol-compatibility perspective. Repository commits are source-control identities, not protocol release versions.

## Planned principles

When a protocol versioning model is selected, it should:

- identify breaking versus compatible changes;
- make server/client compatibility understandable;
- permit additive evolution where practical;
- define migration and deprecation behavior;
- avoid silent breaking changes;
- identify exact released protocol artifacts or schemas;
- distinguish protocol version from application release versions; and
- provide capability negotiation where version numbers alone are insufficient.

## Change discipline

A protocol-affecting implementation should be defined here before dependent repositories claim support for it.

A changed branch head, merged pull request, or generated client does not establish a released protocol version without the separate release and compatibility evidence required by GoreeCloud governance.
