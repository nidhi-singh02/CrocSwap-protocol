For deploying CrocSwap smart contract via the hardhat kurtosis package,this is how the config.yaml file should look like

```
deployment:
  repository: "github.com/nidhi-singh02/CrocSwap-protocol"
  contracts_path: ""
  script_path: "misc/scripts/deploy.ts"
  network: "bartio"
  wallet:
    type: "private_key"
    value: "0xfffdbb37105441e14b0ee6330d855d8504ff39e705c3afa8f859ac9865f99306"
  dependency:
    type: git
    path: "misc/scripts/dependency/dependency.sh"
```
