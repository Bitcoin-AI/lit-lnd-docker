# lit-lnd-docker
Docker configuration to run Lightning Terminal with LND in testnet

Done using https://github.com/nostrassets/taproot-docker/tree/main/testnet as starting point

Create .env file with following content:

```
# LND
ALIAS=your_alias
# Lightning Terminal
UIPASSWORD=litui-password-here
```

Run ``docker-compose up``

Open Lightning terminal at ``https://localhost:8444``

Create ``Lightning Node Connect`` sessions to use https://terminal.lightning.engineering/ and import in Alby extension (LNC)

* Accessing Lightning Terminal

![Litd1](./imgs/litd1.jpeg "Lightning Node Connect Page")
*Figure1: Lightning Node Connect page*

![Litd2](./imgs/litd2.jpeg "Lightning Node Connect Creating Admin Session")
*Figure2: Creating admin session to be used at https://terminal.lightning.engineering/*

![Litd3](./imgs/litd3.jpeg "Admin LNC created")
*Figure3: LNC Session created, copy access pairing phrase*

![Litd4](./imgs/litd4.jpeg "Connecting to Lightning Terminal UI")
*Figure4: Paste access pairing phrase*

![Litd5](./imgs/litd5.jpeg "Node connected")
*Figure5: Node connected to lightning terminal UI*

    * Accessing Alby

![alby1](./imgs/alby1.jpeg "Custom LNC Session for alby")
*Figure6: Creating custom LNC session for alby usage*

![alby2](./imgs/alby2.jpeg "Setting permissions")
*Figure7: Setting permissions*

![alby3](./imgs/alby3.jpeg "Accessing Alby")
*Figure8: Alby connect wallet main page, select "Bring Your Own Wallet"*

![alby4](./imgs/alby4.jpeg "Accessing Alby - LNC")
*Figure8: Select Lightning Terminal (LNC)*

![alby5](./imgs/alby5.jpeg "Accessing Alby - LNC - Pair Phrase")
*Figure9: Paste pairing phrase generated for alby usage*

![alby6](./imgs/alby6.jpeg "Wallet connected")
*Figure10: Alby connected to node*