---
id: faucet
title: How to Use the Testnet Faucet
sidebar_label: Get Testnet Tokens
description: Using the Avail Testnet Faucet
keywords:
  - docs
  - avail
  - explorer
  - accounts
  - faucet
  - funding
image: https://docs.availproject.org/img/avail/AvailDocs.png
---

An automated faucet on Discord has been configured to distribute Avail tokens (AVL) for the Goldberg testnet.

:::note Please note

- The verification step is **mandatory for all users.**
- The faucet is designed to distribute small amounts of AVL for testing purposes, not large quantities for validator bonding or similar activities.
- We appreciate that the verification process may be inconvenient for some users. However, it is necessary to prevent spam and ensure a fair distribution of test tokens. As time goes we will be looking into ways to make the process easier.

:::

## Account Verification Process

To prevent spam and ensure a fair distribution of test tokens, Avail has introduced a mandatory verification process based on [<ins>Gitcoin Passport</ins>](https://passport-verifier.avail.tools/). This process links your wallet address to your Discord account. If you are not already a member of the Avail community, please join the [<ins>Avail Discord server</ins>](https://discord.gg/y6fHnxZQX8) first.

:::note Please note

Gitcoin only supports the validation of EVM based addresses. You can still use your substrate based address to receive tokens from the faucet once you have completed the verification process.

:::

Follow these steps to complete the verification:

1. Go to the [<ins>Avail Faucet Verification page</ins>](https://passport-verifier.avail.tools/).

2. Click on the "Connect Wallet" button in the center of the page. You can choose from several wallet providers. For this demonstration, we will be using [<ins>SubWallet</ins>](https://www.subwallet.app/).

   <p align="center"><img src="/img/faucet/1.png" alt="Connect Wallet" width="80%"/></p>

3. A window will appear listing various wallet options. When prompted, verify and approve the connection request.

   <p align="center"><img src="/img/faucet/2.png" alt="Wallet Options" width="80%"/></p>

4. Ensure you don't have any pending connections, or else you won't be able to connect your wallet address.
If the connection is successful, you will be able to see your linked account on the top right-hand corner of the page.

   <p align="center"><img src="/img/faucet/4.png" alt="Connected Wallet" width="80%"/></p>

5. You will then need to connect your Discord account. Click on "Connect Discord" and authorize the requested permissions.Review the message prompt and click "Authorize". Your page should now look something like this:

   <p align="center"><img src="/img/faucet/5.png" alt="Discord connected" width="80%"/></p>

6. Click on "Submit Gitcoin Passport" to complete the verification process.
   
   <p align="center"><img src="/img/faucet/5b.png" alt="Gitcoin passport submitted successfully" width="95%"/></p>

7. Please note that you need a score of at least "20" to be verified. If your score is below 20, your screen will look something like this (however, see note below):

   <p align="center"><img src="/img/faucet/5c.png" alt="Gitcoin passport submission failed " width="85%"/></p>

8. You can work on your Gitcoin score from [their dashboard](https://passport.gitcoin.co/#/dashboard). You can also check out [Gitcoin docs](https://docs.passport.gitcoin.co/) for more information.

9. Finally, click on the "Give role" button. This will give your linked Discord ID a role named `verified-faucet` that will allow you to use the faucet.

Ensure that your Discord account is connected as it will be used in the following steps. You will also be able to see your connected Discord account that is verified on the top right-hand corner of the page.

Note: We have received reports from users with more than 20 points that are still getting the error page on the verifier. In that case, please refresh your stamps at the bottom of the Passport page, reload the page, reload the verifier site and wait a bit. We are looking into the problem, thank you!

## Obtaining Test AVL Tokens from Discord


:::note Please note

- The `/deposit` command has a cooldown period. You can use it only once every 3 hours.

:::

After completing the account verification process, you can obtain test AVL tokens:

1. In the Avail Discord, navigate to the `#goldberg-faucet` channel.

2. Use the command `/deposit <your-address>` to request AVL tokens.

   <p align="center"><img src="/img/faucet/6.png" alt="Verification Confirmation" width="100%"/></p>

   Should you attempt to use the faucet with an unverified Discord account or a different address, you will encounter the following message.

   <p align="center"><img src="/img/faucet/9.png" alt="Verification Confirmation" width="100%"/></p>

   Your wallet will receive 5 AVL tokens once the transaction status is marked as `Complete`. You can request AVL tokens every 3 hours.

   <p align="center"><img src="/img/faucet/8.png" alt="Transaction Complete" width="50%"/></p>

If you encounter any issues, please feel free to reach out to the Avail team and greater community on Discord.
