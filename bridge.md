# How to move Redeemable from Cardano mainnet to Shareslake mainnet

In order to create a smooth transition from of Redeemable from Cardano mainnet to Shareslake mainnet we setup a bridge.

Shareslake addresses are fully compatible with Cardano addresses. That means you can use the same wallet / key pair to create transactions in both networks maintaining the same address.

The bridge will receive some Redemable in Cardano mainnet and will send the same amount to the sender's wallet address into Shareslake mainnet.

In short, you send Redeemable to the bridge and it sends you the same amount in the Shareslake mainnet to your same wallet address.

## Bridge usage

1. Send your Redeemable tokens to the following address: `addr1qypfxe56p0r3f0js5cav4jzja7qqedwfd888p6z9kxxs64cmth3jzw7y6ex4hxv9j4uj2e37ael8207rd2zfhjnnpukqy382j8`.

2. Edit your wallet settings to connect to a Shareslake node.

3. You should see your Redeemable.

## Important

Currently, moving your Redeemable to Shareslake mainnet is only recommended if you are able to create transactions using `shareslake-cli`, and from an address created using `cardano-cli`.

We are still working on adapting common Cardano wallets to work in both networks, so if you don't know how to create transactions with `shareslake-cli` we recommend to wait until common wallets are adapted. We will update this page with the list of supported wallets soon.
