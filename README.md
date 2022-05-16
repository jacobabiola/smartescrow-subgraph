# smart-invoice mono repo

## install packages

```
yarn install 
```


## Subgraph

### Configure the subgrap by changing these values in /config files respectively 

```
  "network": "metertest",
  "factories": [
    {
      "factoryName": "Version00",
      "startBlock": "15018939",
      "address": "0x588bAF3e28fA8CDE7B2FA75405478bF4eFA15A73"
    }
  ]
}

```

change the node address to yours in packages/subgraph/package.json

```
"create-metertest": "graph create --node http://167.71.140.181:8020 jacobabiola/smart-invoice",
```


### Deploy sungraph 
```
yarn run subgraph:deploy-metertest
```

