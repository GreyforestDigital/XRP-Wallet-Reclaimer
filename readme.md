# XRP Wallet Reclaimer

## A simple client-side tool to recover old Ripple / XRP wallets via secret key for transferring reserved funds to new wallet.

Connects to any wallet via the Secret Key and allows instant transfer of funds to new destination wallet.

No tracking, advertisements, third-party dependencies, or required libraries aside from the official XRPL API Library.

**Use This Tool:** [https://greyforestdigital.github.io/XRP-Wallet-Reclaimer](https://greyforestdigital.github.io/XRP-Wallet-Reclaimer).

*NOTICE: No information is saved or transmitted to any server other than the Ripple Network.*

**OR**

Download this repo and run the single HTML file locally from your browser for total security and transparency.


## INSTRUCTIONS

### Connecting Wallet:

- Enter your wallet's secret key into the "Secret Key" input
- Click "Connect to Wallet" and wait for success or error message
- If successful, you will see your wallet's public address and the current balance in XRP
- If unsuccessful, double-check that your secret key is 29 characters long and starts with an "s"

### Transferring Balance

- Enter a new destination address to send your XRP
- Enter an amount in XRP to send, then click "Send XRP" button
- *Reminder that you must leave at least 1 XRP in your wallet for a transfer to send successfully*

### Precautions

- There are no confirmation prompts before a payment is sent
- Confirm the accuracy of destination address BEFORE clicking "Send XRP"


## HISTORY

In the beginning, Ripple's wallet software set a minimum balance requirement of 20 XRP tokens in a wallet for activation. This was at a time when XRP was worth almost nothing, so 20 XRP was a minor expense.

As time continued, XRP's value rose, and with it, the minimum cost of keeping a wallet open/active. Despite a lowering to only 10 XRP required in 2021, many XRP tokens have been lost or forgotten via the locked-up nature of the XRP reserve minimum.

Recently (December 2024), the Ripple foundation reduced the minimum wallet balance to only 1 XRP. Meaning there are countless wallets now in existence where their balance has potentially reached ~$44 USD (as of 12/25/2024).

In searching for a way to reclaim XRP locked in a wallet created using the offical Ripple wallet client, which ceased functioning years ago, I found almost no answers that didn't involve signing up for a third-party exchange or other wallet platform with multiple verification steps, KYC, document uploads required, 2FA setup, etc etc.

This simple webtool is the result of wanting a private, instant, zero trust  solution for reclaiming the 10-20 XRP abandoned in so many wallets throughout history.


## TERMS & CONDITIONS

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software. 


