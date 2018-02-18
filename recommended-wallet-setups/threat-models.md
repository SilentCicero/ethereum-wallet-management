### Threat Models

To defend yourself, you need to know what you're defending against. There's multiple different threats to worry about, so let's divide them into common threats that you are likely to encounter and major threats that are rare but catastrophic.

Examples of Common Threats:
 - Malware
 
 - Forgetting, losing or corrupting instructions
 
 - Improper key handling (i.e. giving a third-party site your private key)
 
 - Spoofing attacks (hackers impersonating a trusted website)
 
 - Spoofed devices (e.g. ordering a Ledger off amazon and having the phrase already pre-set by an attacker)

Examples of Major Threats:
 - Fire
 
 - Flood
 
 - Burglary
 
 - File/hardware corruption

Figure out what you are most afraid of, and then design your wallet setup to ward off those fears.

As we increase the difficulty level, we are able to handle more and more of these threats.

For example, the Gnosis Multi-Sig Wallet with Daily Limit Withdrawal protects against the possibility of you losing all funds to situations like the destruction of all but one of your multi-signature accounts. It does so by having a policy of daily withdrawal. So long as you are in possession of at least one valid signing account, you can withdraw your daily limit of funds from the wallet every day, until your funds are restored. While this may take a while, at least you can eventually recover most of your funds (minus transaction fees). This kind of redundancy is simply not possible in non-contractual or multi-signature systems.

However, the higher difficulty levels are still vulnerable to threats of their own, such as forgetting instructions.

If you chose a higher-level setup but put all your keys in the same location (thereby making the keys vulnerable to fire, flood, and burglary) or didn't make physical backups of your keys (thereby making the keys vulnerable to file/hardware corruption), then basically choosing that level is almost meaningless. You have to be prepared for a variety of different threats.