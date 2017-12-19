# How to obtain your blockchain application ID

Confirm your application by interacting with our HR smart contract on the ethereum Ropsten network:

* Submit a hash (Keccak-256) of your email address using the “apply” function.
* Retrieve your application ID using the “hasApply” function.
* Copy your application ID and paste it in the application form.

### Additional information

Contract address: 
```
0x0ab20d9af06b123a84CbA7C70FA884B0395197D0
```

Contract ABI: 
```
[{"constant": true,"inputs": [{"name": "email","type": "string"}],"name": "hasApplied","outputs": [{"name": "","type": "uint256"}],"payable": false,"stateMutability": "view","type": "function"},{"constant": false,"inputs": [{"name": "hash","type": "bytes32"}],"name": "apply","outputs": [{"name": "","type": "uint256"}],"payable": false,"stateMutability": "nonpayable","type": "function"}]
```

### Usefull links

* https://karl.tech/intro-guide-to-ethereum-testnets/
* https://www.myetherwallet.com/
* http://faucet.ropsten.be:3001/
