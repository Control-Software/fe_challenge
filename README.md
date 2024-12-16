### **Non-Custodial Wallet Challenge: Create and Take Over**

#### **Objective:**
Use the Fireblocks NCW Web Demo repository to build a non-custodial wallet and demonstrate a wallet creation process, including a scenario simulating a wallet takeover by recovering the wallet using recovery mechanisms.

#### **Steps to Complete the Challenge:**

1. **Clone and Set Up the Repository:**
   - Fork the [Fireblocks NCW Web Demo repository](https://github.com/fireblocks/ncw-web-demo).
   - Clone the repository locally and follow the instructions in the README to set up the development environment.

2. **Implement Wallet Creation:**
   - Add functionality to allow users to create a new non-custodial wallet.
   - Ensure that the wallet generates a key pair (e.g., using ECDSA or Ed25519) and stores the private key securely in the client environment (e.g., using browser storage or a secure enclave).
   - Provide a simple and intuitive UI for wallet creation, including a recovery phrase or backup mechanism.

3. **Simulate Wallet Takeover:**
   - Implement a recovery mechanism where a user can regain access to their wallet in case of loss of private key access. This could involve:
     - Entering a recovery phrase.
     - Using a multi-signature setup with a trusted third party.
   - Simulate a takeover scenario where a user intentionally "loses" access to their wallet and then regains control using the implemented recovery process.

#### **Bonus Points:**
- Document all the calling procedures in mermaid as a sequence diagram
