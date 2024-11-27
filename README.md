# **AnubsTrueCoin Smart Contract**

This repository contains the source code for **AnubsTrueCoin**, a blockchain-based token developed by **AhketLabs**. The contract is designed using a **proxy pattern** to enable future upgrades without changing the contract address. The code is published for transparency and reference as part of the **Ahket Ecosystem** and its integration with the **VerifyAtOnce (VAO)** platform.

---

## **Important Note**
This repository is published solely for transparency and reference. **Unauthorized use, modification, or deployment** of the code without permission from AhketLabs is strictly prohibited.

---

## **Key Features**
- **ERC20-Compliant Token:** Implements the ERC20 standard for compatibility with wallets and exchanges.
- **Proxy Pattern Ready:** Designed for upgradeability, ensuring flexibility and consistency across versions.
- **Integration with VerifyAtOnce:** Supports attestations and verifications on the VAO platform.

---

## **Proxy Pattern Overview**
The **proxy pattern** separates the token’s logic from its storage, allowing seamless upgrades without changing the deployed contract’s address. This ensures:
- **Consistency:** The same contract address is retained for interacting with the token.
- **State Preservation:** Token balances and other state data remain intact across logic upgrades.
- **Future-Proofing:** New features and fixes can be implemented in future versions.

---

## **Versioning System**
The repository includes the source code for each version of the AnubsTrueCoin logic contract. Each version is stored in a dedicated folder, with version numbers following semantic versioning (`vMAJOR.MINOR`).

### **Available Versions**
| Version | Deployment Details                                   |
|---------|-----------------------------------------------------|
| v1.0    | Deployed on Polygon Mainnet at `0x123...` (Nov 2024) |

The **v1.0** source code is available in the `v1.0/` directory. Future versions will be added as they are deployed.

---

## **Source Code**
### **v1.0**
The source code for **AnubsTrueCoin v1.0** is located in the `v1.0/` directory:
- **`contracts/AnubsTrueCoinV1.sol`**: Contains the logic for the initial version of the token.

To verify the deployed contract, visit:
- Polygon Mainnet Explorer: [View on PolygonScan](https://polygonscan.com/address/0x7601ee96da06f566c6eeb9671c4843eacd6a2e35)


