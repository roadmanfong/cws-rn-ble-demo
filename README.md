# CoolWalletS RN App Demo

![](https://i.imgur.com/THXHkCP.png)

This is a demo of how to use CoolWalletS SDK to built your own app.

### Install and run
```
npm insatll
```

```
yarn start 
# or
npm start
````

## Notes

In this demo, we use [`@coolwallets/transport-react-native-ble`](https://github.com/CoolBitX-Technology/coolwallet-js-sdk/tree/master/packages/transport-react-native-ble) as the bluetooth transport.

[`@coolwallets/wallet`](https://github.com/CoolBitX-Technology/coolwallet-js-sdk/tree/master/packages/cws-wallet) is imported to handle registration, pairing and create a seed with the card.

[`@coolwallets/eth`](https://github.com/CoolBitX-Technology/coolwallet-js-sdk/tree/master/packages/cws-eth) is use to sign eth transactions.
