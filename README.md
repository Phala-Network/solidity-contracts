# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```

## Gas metering

```shell
REPORT_GAS=1 npx hardhat test ./test/PhatRollupAnchor.ts
REPORT_GAS=1 npx hardhat test ./test/SampleOracle.ts
```

## Coverage

``shell
npx hardhat coverage
# miniserve ./coverage
```
