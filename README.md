# Vanity Name Registry

## Description

Build a vanity name registering system resistant against frontrunning. The purpose of the name is outside the scope of the assignment and you can make reasonable assumptions on the size, encoding, etc of the name to complete in time. An unregistered name can be registered for a certain amount of time by locking a certain
balance of an account. After the registration expires, the account loses ownership of the name and his balance is unlocked. The registration can be renewed by making an on-chain call to keep the name registered and balance locked. You can assume reasonable defaults for the locking amount and period. The fee to register the name depends directly on the size of the name. Also, a malicious node/validator should not be able to front-run the process by censoring transactions of an honest user and registering its name in its own account.


Contract deploy at https://ropsten.etherscan.io/tx/0x90729bd8d10720192b16f8c46355e52c96610af7d1591c901afa1c14a93cc93d with contract address "0x07a6ca4aea567e12c2a422624401f30944dce1a5"