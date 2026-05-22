# Upstream PR Sync Log

Date: 2026-05-22
Upstream: `warpdotdev/warp`
Fork mainline: `origin/master`

## Merged

- `#11264` Only refresh tasks on RTC invalidation if a view is open.
- `#11423` Add host label for remote repos and files.
- `#11427` Fix markdown rendering on remote SSH sessions.
- `#11428` Fix deadlock in secret redaction due to mutex ordering mismatch.
- `#11464` Update filesystem watch filters.
- `#11465` QUALITY-726: session sharing for orchestrated agent sessions.

## Already Present / Empty Cherry-Pick

- `#11492` Fix gh hosts config filename.

## Skipped To Avoid Commercial Content

- `#11437` Enable SoloUserByok and BillingAndUsagePageV2 in stable.
- `#11450` Enable CustomInferenceEndpoints feature flag in stable.

## Verification

- `cargo check --manifest-path app/Cargo.toml --features decommercialized`
- `cargo check --manifest-path crates/warpui_core/Cargo.toml --features decommercialized`
