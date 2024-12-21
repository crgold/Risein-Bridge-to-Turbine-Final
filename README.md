# Risein - Bridge to Turbine - Final Project

This project demonstrates how to interact with the Solana blockchain by performing tasks such as airdropping SOL, transferring SOL, and creating enrollment records on Devnet.

---

## Enrollment Transaction

You can view the enrollment transaction on the Solana Explorer:  
[3nJuSShPFcYYQzHipdciWLPjofguY99Uwg1XGVZR3T6PWVLxj1oVgepmCzr54Rac8b5JZ3ZJpZ28mVE15SspyPty](https://explorer.solana.com/tx/3nJuSShPFcYYQzHipdciWLPjofguY99Uwg1XGVZR3T6PWVLxj1oVgepmCzr54Rac8b5JZ3ZJpZ28mVE15SspyPty?cluster=devnet)

---

## Scripts Overview

### `airdrop.ts`

**Description**:  
This script allows a user to airdrop an amount of SOL to a designated wallet address.

**How to Run**:  
```bash
yarn airdrop
```

---

### `transfer.ts`

**Description**:  
This script allows a user to transfer a specified amount of SOL to a designated wallet address.

**How to Run**:  
```bash
yarn transfer
```

---

### `enroll.ts`

**Description**:  
This script creates an enrollment record on the Solana Devnet by interacting with a program. It uses a GitHub username as the enrollment data.

- **Program Address**:  
  [WBA52hW35HZU5R2swG57oehbN2fTr7nNhNDgfjnqUoZ](https://explorer.solana.com/address/WBA52hW35HZU5R2swG57oehbN2fTr7nNhNDgfjnqUoZ/anchor-program?cluster=devnet)

**How to Run**:  
```bash
yarn enroll
```

---

## Requirements

- Node.js installed on your system
- Yarn package manager
- A Solana wallet configured for Devnet

---

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/crgold/Risein-Bridge-to-Turbine-Final.git
   cd Risein-Bridge-to-Turbine-Final
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Run the desired script using the commands mentioned above.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

