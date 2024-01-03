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
