# **AnubisTrueCoin v1.0**

This folder contains the source code for version **v1.0** of the **AnubisTrueCoin (ATC)** smart contract. This implementation follows a secure and modular design, leveraging OpenZeppelin's upgradeable libraries. It is built for integration with the **Ahket Ecosystem** and supports the **VerifyAtOnce (VAO)** platform.

---

## **Features**
- **ERC20 Standard**: Fully compatible with wallets, exchanges, and DeFi platforms.
- **Upgradeable Design**: Uses the UUPS proxy standard to enable seamless upgrades.
- **Burnable and Pausable**: Tokens can be burned or transfers paused as needed.
- **Role-Based Access Control**: Ensures secure management of administrative and operational functions.
- **Permit Functionality**: Supports gasless approvals via EIP-2612.

---

## **Deployment Details**
- **Token Name**: AnubisTrueCoin
- **Token Symbol**: ATC
- **Decimals**: 18
- **Initial Supply**: 1,000,000,000,000 ATC
- **Network**: Polygon Mainnet
- **Contract Address**: `0x123...` (View on [PolygonScan](https://polygonscan.com/address/0x7601ee96da06f566c6eeb9671c4843eacd6a2e35#code))

---

## **Security Features**
- **Access Control**: Only authorized accounts can mint, pause, or upgrade the contract.
- **Pausable Operations**: Transfers can be paused in emergencies to protect user assets.
- **Upgradeable**: Uses the proxy pattern to maintain state while allowing feature enhancements.

---

## **Testing**
Unit tests for this version are located in the `tests/` directory.

To run tests:
```bash
npx hardhat test
