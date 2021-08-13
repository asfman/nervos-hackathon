## Task 3 Issue a Smart Contract Call to the Deployed Smart Contract

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![screenshot] (task-3.PNG)

2. The transaction hash from the console output (in text format).
```sh
 0x0c8bb0bd0ce1e4f798779ed23ec993e73876c580ccb05ce697482df1e2b15f73
```

3. The contract address that you called (in text format).
```sh
0xb232310B84c2aB1Fa68fEe4B5042f4612854DAcE
```

4. The ABI for contract you made a call on (in text format).
```sh
  [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```
