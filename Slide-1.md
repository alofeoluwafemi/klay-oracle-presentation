## Oracle Problem

By design, the blockchain is deterministic and therefore does not have an inbuilt ability to fetch data directly from an external source or push data to it.

### Impossible 🙅🏻

- Making a GET call to an external API from a smart contract in order to obtain the KLAY pricing
- Send a poll request to update the weather information.
- Send a POST request with a transaction response to a webhook URL.

### Roubustfullness

To build rich applications on the blockchain smart contracts need to be able to access off-chain data.

**Such as:**

What is the cost in KLAY to send a user for a deposit of $1000 in USDT? Create a distinct, unpredictable random number that is impossible to predict or guess. How much does an ounce of gold currently cost for a derivative smart contract? How is the climate in Sydney?

Off-chain data like this and many others are required by smart contracts because they were designed for more than just exchanging tokens.

[Slide 2](https://github.com/alofeoluwafemi/klay-oracle-presentation/blob/master/Slide-2.md)
