# cryptology_tbw
Cryptology True Block Weight and Fair Fees

1) Clone the project to a server with a full ARK Node running
2) Select the V1 or V2 branch
3) yarn install (do not use npm!)
4) Copy example.env to .env
5) Edit .env to match your configuration


# Usage
`node bin/app.js` to show calculated payouts

`node bin/app.js check` to show calculated payouts and generated transactions

`node bin/app.js payout` to run payouts => will send payouts to your own forger, V1: and wait for it's slot

# Limitations
Please make sure to set the start blockheight to the first block after your previous payout and configure the .env NODE to point to the IP of your forger.
