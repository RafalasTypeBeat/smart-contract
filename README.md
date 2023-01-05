# Marketplace smart contract

Programa leidžia naudotojams įkelti prekes pardavimui ir jas pirkti. Nupirkus preke jos "ownership" perduodamas iš pardavėjo pirkėjui.

## Unit tests
Testų paleidimas lokaliame *Ethereum* tinkle:
```bash
    > truffle test
```

Testų vykdymo rezultatas:
```bash
Using network 'development'.

Compiling .\src\contracts\Marketplace.sol...


  Contract: Marketplace
    deployment
      √ deploys successfully
      √ has a name (113ms)
    products
      √ creates products (451ms)
      √ lists products (125ms)
      √ sells products (1290ms)


  5 passing (3s)
  ```

  ## Smart contract testavimas Sepolia tinkle

  ### Kontrakto sukūrimas
Kontrakto sukūrimo transakcija:  https://sepolia.etherscan.io/tx/0xaeb6e9d85d606cc529d9d16e12b2997359d4d24947124d16c47233eee00acb81

Kontrakto panaudojimo transakcija:  https://sepolia.etherscan.io/tx/0xcac7231c77abbc867662ddba39e22f9cf7ccaa4ee90b43de94ed827aff03ee54


  