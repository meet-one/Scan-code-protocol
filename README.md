Scan code protocol     
==============
Scan code protocol for MEET.ONE    

## Transfer

### 1.account name string
``` java
eosiomeetone //eos account name in chain
```

### 2.json

``` java
{
  "protocol":"MEET.ONE" //protocol name,must be "MEET.ONE"
  "action":"navigate" //Page jump action,must be "navigate"
  "target":"EOSTransferPage" //go to transfer page
  "to":"eosiomeetone" //receiver
  "amount":8.0000 //token amount
  "symbol":"eos" //token symbol
  "precision":4 //token precision
  "chainid":"d5a3d18fbb3c084e3b1f3fa98c21014b5f3db536cc15d08f9f6479517c6a3d86" //chain id
}
```


### 3.simplewallet protocol

[SimpleWallet Mobile SDK](https://github.com/southex/SimpleWallet/blob/master/README_en.md) 
