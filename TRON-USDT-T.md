# USDT.T on TRON — Contract-specific Information

## THFpn — target contract

- Network: TRON Mainnet
- Standard: TRC20
- Project-reported name / symbol: USDT.T / USDT.T
- Project-reported decimals: 6
- Contract: THFpnLfqHzU58agVyzkkDncvXFSKr8hsV3
- Explorer: https://tronscan.org/#/token20/THFpnLfqHzU58agVyzkkDncvXFSKr8hsV3

Identification follows the existing project records. Live explorer
and on-chain getter confirmation was unavailable on 2026-10-20.

### Source matching and explorer verification

The project investigation record dated 2026-10-14 identifies the
contract name USDT_T_V2_BRIDGEABLE and reports an 8,786-byte runtime
match after constructor immutable values were applied to the saved
creation-code runtime template.

Reported runtime SHA-256:
179de15b8d60f2a5b3836af2043d2c036fdc7836e3b99f89957dcf84eeee9bd5

This is a recorded bytecode reconstruction result, not an independent
Solidity source compilation match or proof of TRONSCAN verification.
The investigation lists compiler candidate 0.8.6+commit.0e36fba0;
the exact deployed compiler build remains unproven.

Current TRONSCAN source-verification status could not be confirmed
during the 2026-10-20 review. This repository contains no Solidity
source or verification artifacts establishing successful verification.

The following TJoTq record concerns a different deployed contract.
Its deployer, ABI and security classification do not establish
the corresponding facts for THFpn.

## TJoTq — separate contract record

This independently deployed token is not issued by, affiliated with, or endorsed by Tether. No USD backing, fixed market value, or redemption guarantee is claimed.

## Token identification

- Network: TRON Mainnet
- Standard: TRC20
- Token name / symbol shown by TRONSCAN: USDT.T / USDT.T
- Decimals shown by TRONSCAN: 6
- Contract: TJoTqJYWzxo659vgf3mtNbiqk7NAejNbAC
- Deployer shown by TRONSCAN: TEzKLEstptKK82EPKg32TLodxgkQRvydFB

Explorer:
https://tronscan.org/#/token20/TJoTqJYWzxo659vgf3mtNbiqk7NAejNbAC

These details are based on TRONSCAN page information supplied by the developer.

## Purpose and contract features

This project explores token transfers and temporary balances.

The published contract ABI includes temporaryMint, temporaryBalanceOf, expire, disableTemporaryMint, and transferOwnership. Temporary balances have expiry conditions and should not be treated as permanent balances.

The source code has not been verified on TRONSCAN. ABI information alone does not establish the full behavior or security of the deployed contract.

## Developer and contact

- Developer name: Ali Demir
- GitHub account: hizadem-creator
- Public contact: https://github.com/hizadem-creator/CUSTOM-USDT-LOGO/issues

The developer name is not presented as independently verified legal identity.

## Review status

The existing developer-supplied record reports an Unsafe token rating and a phishing-report warning for TJoTq. This was not rechecked live on 2026-10-20.

The existing record describes a planned reassessment requesting the evidence behind this classification and the requirements for review. Its current submission status was not confirmed. No claim is made that the reports are false.

No independent audit report is provided. The BSC metadata validation results in this repository do not apply to this TRON contract.
