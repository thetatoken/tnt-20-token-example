# TNT-20 Smart Contract Example

This repository contains a TNT-20 Smart contract example with basic unit tests

## Run test

### Setup
```
cd tests
npm install
```

Modify the following lines in `tests/test/mintable-tnt20.test.js` with the wallet addresses and private keys for your test.

```
const AddressAdmin = "ADMIN_WALLET_ADDRESS";
const AddressUser1 = "USER_1_WALLET_ADDRESS";
const AddressUser2 = "USER_2_WALLET_ADDRESS";
const PrivateKeyAdmin = "ADMIN_WALLET_PRIVATE_KEY";
const PrivateKeyUser1 = "USER_1_WALLET_PRIVATE_KEY";
const PrivateKeyUser2 = "USER_2_WALLET_PRIVATE_KEY";
```

Then, send a small amount of TFUEL (e.g. 50 TFUEL) to each of the above wallets. 

### Run tests
```
npm run test
```
