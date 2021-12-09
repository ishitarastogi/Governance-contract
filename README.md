# on-chain governance
Decentralized protocols are in constant evolution from the moment they are publicly released. Often, the initial team retains control of this evolution in the first stages, but eventually delegates it to a community of stakeholders. The process by which this community makes decisions is called on-chain governance

This governance protocol is generally implemented in a special-purpose contract called **“Governor”**.

# Setup

Token
The voting power of each account in  governance setup will be determined by an ERC20 token. The token has to implement the ERC20Votes extension. This extension will keep track of historical balances so that voting power is retrieved from past snapshots rather than current balance, which is an important protection that prevents double voting.
