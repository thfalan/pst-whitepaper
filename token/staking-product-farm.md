---
description: LiquidRoyalty RWA Vaults
---

# Vaults

<figure><img src="../.gitbook/assets/Screenshot 2025-02-11 at 10.03.17 AM.png" alt=""><figcaption><p>Yield Farming Tranches</p></figcaption></figure>

LiquidRoyalty currently offers 3 ERC-4626 compliant Vaults:

1. **🏦 Senior Vault (snrUSD) - Monthly Rebalancing**

* **For:** The conservative investor.
* **Profile:** You prioritize capital preservation and a predictable, stablecoin-denominated return.
* **How it Works:** Senior has an **11% APY floor · 13% cap**, backed by Junior and the Protocol Reserve (ALAR)—the highest-priority payout in the vault stack.
* **Yield Payout Method:** Yield is paid as additional snrUSD (within the 11–13% band) airdropped to snrUSD holders during rebalance, so snrUSD can stay integrable with other DeFi protocols (e.g. DEX, lending).
* Yield spillover only happens when total assets in the vault are over 110% of snrUSD circulation.
* **Cooldown**: User can withdraw USDe 7 days after initiating cooldown; snrUSD in cooldown will **not** receive yield airdrops.
* **Only users with snrUSD balance more than 0.01** receive the rebalance airdrop distribution.



2. **⚡ Junior Vault (JNR) - Liquid Staking**

* **For:** The growth-oriented investor.
* **Profile:** You are comfortable with higher volatility for a significantly amplified return.
* **How it Works:** Junior is private and variable; it receives **80% of yield above Senior’s 13% cap**. Spillover happens during rebalance.
* **Yield Payout Method:** Through JNR share price appreciation.
* **Cooldown**: User can withdraw USDe 7 days after initiating cooldown; JNR:USDe rate is based on the time of cooldown initiation.



3. **🛡️ Protocol Reserve / ALAR - Liquid Staking**

* **For:** The long-term ecosystem believer.
* **Profile:** You are invested in the protocol's health and sustainability.
* **How it Works:** ALAR (Protocol Reserve) receives **20% of yield above Senior’s cap**, which helps support the Senior floor and creates a virtuous cycle of growth.
* **Yield Payout method:** Spillover happens during rebalance.
* **Cooldown**: User can withdraw USDe 7 days after initiating cooldown; ALAR:USDe rate is based on the time of cooldown initiation.

