# Final Project

## Transaction Details
**Transaction Link:** [View Transaction on Solana Explorer](https://explorer.solana.com/tx/GuCpYjKp9EPhGiRb8nouHjycUoRucqjwvdsLi7oqcrPuv87VVprgu6YbaxPGieCX58QX452QawrGEJyaoVXcKf6?cluster=devnet)

---

## Project Overview
This project interacts with a Solana program on the **devnet**. It submits a transaction to register the completion of prerequisites using a GitHub username.

### Key Files in the Project:
1. **`keygen.ts`**  
   -  This file generates a new keypair.
  
2. **`airdrop.ts`**  
   -  Claim solana devnet tokens using this file.
     
3. **`transfer.ts`**  
   - Transfer funds from your wallet to other wallet using a PublicKey

4. **`wba_prereq.ts`**  
   - Contains the Interface Definition Language (IDL) and types that describe the Solana program's structure.

5. **`enroll.ts`**    
   - It submits a transaction to complete the program prerequisites by sending the user's GitHub account name.

---

## How to Run the Project

1.Install all the dependencies.
```bash
yarn install
```

2. Generate a keypair.
```bash
yarn keygen 
```

3. Transfer funds from your wallet to another wallet.
```bash
yarn transfer 
```

4. Enroll
```bash
yarn enroll 
```
