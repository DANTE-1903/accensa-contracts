# Roadmap

## Issue #443: stACC liquid staking derivative minting

- [x] Implement stACC liquid staking derivative minting (#443)
  - New `liquid_staking` module in `contracts/governance/src/liquid_staking.rs`
  - 1:1 mint/burn of stACC against locked underlying tokens
  - Exchange rate progression and lock-epoch-based redemption
  - CHANGELOG.md entry added

## Issue #665: Fix CONFORMANCE.md build-vectors paths to the receipt-anchor crate

- [x] Fix CONFORMANCE.md build-vectors paths to the receipt-anchor crate (#665)
  - Corrected generator and generated file paths in `docs/CONFORMANCE.md` to `contracts/receipt-anchor/`
  - Verified `node contracts/receipt-anchor/scripts/build-vectors.mjs --check` matches CI