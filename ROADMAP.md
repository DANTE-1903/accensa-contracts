# Roadmap

## Issue #443: stACC liquid staking derivative minting

- [x] Implement stACC liquid staking derivative minting (#443)
  - New `liquid_staking` module in `contracts/governance/src/liquid_staking.rs`
  - 1:1 mint/burn of stACC against locked underlying tokens
  - Exchange rate progression and lock-epoch-based redemption
  - CHANGELOG.md entry added

## Issue #663: Reconcile immutability claims with refund-vault's upgrade_wasm

- [x] Reconcile immutability claims with refund-vault's upgrade_wasm (#663)
  - Updated `docs/ADR-003-upgradeability.md`, `docs/SECURITY_MODEL.md`, `docs/AUDIT.md`, and `docs/MAINNET_DEPLOYMENT.md`
  - Documented RefundVault's admin-gated two-phase upgrade flow and ReceiptAnchor's immutability