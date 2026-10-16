# Roadmap

## Issue #443: stACC liquid staking derivative minting

- [x] Implement stACC liquid staking derivative minting (#443)
  - New `liquid_staking` module in `contracts/governance/src/liquid_staking.rs`
  - 1:1 mint/burn of stACC against locked underlying tokens
  - Exchange rate progression and lock-epoch-based redemption
  - CHANGELOG.md entry added

## Issue #664: Remove the fictional refund-window enforcement from SECURITY_MODEL

- [x] Remove the fictional refund-window enforcement from SECURITY_MODEL (#664)
  - Reconciled zero-window semantics in `docs/SECURITY_MODEL.md` to reflect unbounded window and TTL handling
  - Aligned `docs/storage-audit.md` and removed references to non-existent `set_refund_window`, `InvalidWindow`, and `MIN_REFUND_WINDOW`