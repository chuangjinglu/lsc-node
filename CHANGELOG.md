<!--
Key Principles
•  Human-Friendly: Changelogs are written for humans, not machines.

•  Comprehensive: Every version should have an entry.

•  Categorized: Group similar types of changes together.

•  Linkable: Versions and sections should be easily linkable.

•  Chronological: The latest version appears first.

•  Dated: Each version's release date is displayed.

•  Versioning: Indicate if Semantic Versioning is followed.

Instructions
Add changelog entries to the Unreleased section under the appropriate category. Each entry must include a tag and the GitHub PR reference in the following format:

* #<PR-number> message

•  Tag: Indicates where the change is made (e.g., (core), (ui)).

•  Issue Number: Will be linked during the release process, no need to manually add links.

Change Categories
•  New Features: For newly added features.

•  Enhancements: For improvements in existing functionality.

•  Deprecations: For features that will be removed in the future.

•  Fixes: For bug fixes.

•  Breaking Changes: For changes that break backward compatibility.
-->

## Unreleased

### Features

### Enhancements

### Fixes

### Breaking Changes

- [#640](https://github.com/Lagrange-Labs/lsc-node/pull/640) Update dependencies for Optimism Holocene upgrade

## [v1.2.0](https://github.com/Lagrange-Labs/lsc-node/releases/tag/v1.2.0) *2024-10-31*

### Features

- [#614](https://github.com/Lagrange-Labs/lsc-node/issues/614) Optimize the verify logic on the rpc clients.

- [#603](https://github.com/Lagrange-Labs/lsc-node/issues/603) Implement the `UploadStatus` api to check the client status.

### Enhancements

- [#612](https://github.com/Lagrange-Labs/lsc-node/issues/622) Adjust the go module name regarding the repo name update.

### Fixes

### Breaking Changes

## [v1.1.0](https://github.com/Lagrange-Labs/lsc-node/releases/tag/v1.1.0) *2024-09-02*

### Features

- [#525](https://github.com/Lagrange-Labs/lsc-node/pull/525) Add the logic to check the version compatibility.

### Enhancements

- [#523](https://github.com/Lagrange-Labs/lsc-node/issues/523) Add the `Signer` module.
- [#530](https://github.com/Lagrange-Labs/lsc-node/issues/530) Create the own go modules to manage the dependencies.
- [#550](https://github.com/Lagrange-Labs/lsc-node/pull/550) Add G2 based BLS scheme.
- [#556](https://github.com/Lagrange-Labs/lsc-node/pull/556) Refactor the optimism rpc in a more combinient way.

### Fixes

### Breaking Changes

- [#557](https://github.com/Lagrange-Labs/lsc-node/pull/557) Update the batch hash logic with the merkle root.

## [v1.0.0](https://github.com/Lagrange-Labs/lsc-node/releases/tag/v1.0.0) *2024-07-30*

### Features

- [#480](https://github.com/Lagrange-Labs/lsc-node/issues/480) Make the epoch period flexible.

### Enhancements

- [#438](https://github.com/Lagrange-Labs/lsc-node/issues/438) Reduce the L2 RPC calls from the client node.

### Fixes

- [#474](https://github.com/Lagrange-Labs/lsc-node/issues/474) Fix the committee root verification failure.
