### Added

- Expose a session-scoped image input controller through the public SDK so a host can admit, supersede and observe prompt images; `dispose()` is permanent, and a superseding checkpoint rebinds the controller to the new owner.

### Changed

- Clarify public SDK embedding contracts for builtin slash dispatch, routing authority and confirmation, reversible Settings receipts, canonical notifications, session-owned jobs, subagent job observation targets, and portable extension interactions; exercise builtin dispatch through the public package entry point.
