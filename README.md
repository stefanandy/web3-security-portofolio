# 0xStefanAndrei's Portfolio

## About

Hi, I'm Andrei, SR, avid rustacean & gopher

Currently, I am an WEB3 Independent Security Researcher
For private audits or security consulting, please reach out to me on Twitter [*@0xStefanAndrei*](https://x.com/0xStefanAndrei).

### Highlights

- [Code4rena Profile](https://code4rena.com/@AM)
- [Sherlock](https://audits.sherlock.xyz/watson/theOwl)



## Competitive Audits Contests

| Contest                       |  Platform  | Alias  | Ranking | Technology | Report                                                                                                                                                   |
|-------------------------------|-----------|--------|---------|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| DODO Margin Trading	          |  Sherlock  | theOwl | 2nd 🥈  | EVM        | [Link](https://github.com/sherlock-protocol/sherlock-reports/blob/main/audits/2023.05.12%20-%20Final%20-%20DODO%20Margin%20Trading%20Audit%20Report.pdf) |
| Splits	                       |  Sherlock  | theOwl | 2nd 🥈  | EVM        | [Link](https://github.com/sherlock-protocol/sherlock-reports/blob/main/audits/2023.04.24%20-%20Final%20-%20Splits%20Audit%20Report.pdf)                  |
| USSD	                         |  Sherlock  | theOwl |         | EVM        | [Link](https://audits.sherlock.xyz/contests/82/report)                                                                                                   |
| Acala Network	                |  Code4rena | AM     | 4th   🎖️  | Substrate  | [Link](https://audits.sherlock.xyz/contests/82/report)                                                                                                   |
| RadicalxChange	               |  Sherlock  | theOwl | 3rd 🥉     | EVM        | [Link](https://audits.sherlock.xyz/contests/82/report)                                                                                                   |
| Wise Lending	                 | Code4rena | AM     |         | EVM        | [Link](https://audits.sherlock.xyz/contests/82/report)                                                                                                   |
| Wildcat Protocol              | Code4rena | AM     |         | EVM        | [Link](https://audits.sherlock.xyz/contests/82/report)                                                                                                   |





## Private Audits

### Solo Auditing

| Client            | Description      | Technology      | Report                |
|-------------------|------------------|-----------------|-----------------------|
| Injective Network | L1               | CosmosSDK / EVM | [Link](audits/injective_report.pdf) |
| Today The Game    | NFT Game/Staking | EVM             | _Pending Publication_ |
| Today The Game    | NFT Game/Staking | EVM             | _Pending Publication_ |


### Auditing at Quantstamp

| Client                      | Description                          | Technology | Report                                                                                                                                                              | Findings |
|-----------------------------|--------------------------------------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
| Startale                    | Stablecoin Vaults                    | EVM        | [Link](https://certificate.quantstamp.com/full/startale-stablecoin-vaults/402c94ac-7cc8-4b28-94b0-83876f38cf56/index.html)                                          | <ul><li><a href="qs-raw-work.md?plain=1#L159">Leveraged TVL Manipulation via Sandwich Attack on distribute()</a></li><li><a href="qs-raw-work.md?plain=1#L240">Boost Rewards Not Settled During Deposit Operations</a></li><li><a href="qs-raw-work.md?plain=1#L396">Incorrect S_base Calculation with Donations Causes Yield Misallocation</a></li><li><a href="qs-raw-work.md?plain=1#L462">Unbounded activeBoostTokens Array Growth</a></li><li><a href="qs-raw-work.md?plain=1#L547">Boost Rewards Precision Loss Without Carry Accounting</a></li><li><a href="qs-raw-work.md?plain=1#L602">No Validation of M0 Yield Recipient Configuration</a></li><li><a href="qs-raw-work.md?plain=1#L643">Missing Validation for USDSC Address in RewardRedistributor</a></li><li><a href="qs-raw-work.md?plain=1#L685">Boost Rewards System Incompatible with Double-Entry Point Tokens</a></li></ul> |
| StakeStone                  | Tokenized Vault                      | EVM        | [Link](https://certificate.quantstamp.com/full/stake-stone-tokenized-vault/aa7fd663-908f-49c5-bb62-eac2463f57f1/index.html)                                         | <ul><li><a href="qs-raw-work.md?plain=1#L1436">Price Update Restrictions Enable Stablecoin Depeg Arbitrage</a></li><li><a href="qs-raw-work.md?plain=1#L1487">Unbounded Cut-Off Price Array Growth</a></li><li><a href="qs-raw-work.md?plain=1#L1501">Cut-Off Price Expiration Causes Withdrawal Processing DoS</a></li><li><a href="qs-raw-work.md?plain=1#L1522">Array Length Gas DoS in Asset Management</a></li><li><a href="qs-raw-work.md?plain=1#L1549">Asset Removal Blocks Liquidity Replenishment</a></li></ul> |
| Datachain                   | IBC                                  | Go         | [Link](https://certificate.quantstamp.com/full/datachain-ibc/1e53ee14-4316-4cb1-9977-45753e49d5b2/index.html)                                                       | <ul><li><a href="qs-raw-work.md?plain=1#L2874">DoS through Closing Channel Abusing Different Gas Limits Between Chains</a></li><li><a href="qs-raw-work.md?plain=1#L2891">Functions calcBlockDelay Could Make the Packet Result in Unexpected Timeout</a></li><li><a href="qs-raw-work.md?plain=1#L2904">Functions channelCloseConfirm Not in Accordance with Specs</a></li><li><a href="qs-raw-work.md?plain=1#L2917">Function updateClientCommitments Not in Accordance with Specs</a></li><li><a href="qs-raw-work.md?plain=1#L2929">Function updateClient Not in Accordance with Specs</a></li><li><a href="qs-raw-work.md?plain=1#L2941">Functions channelOpenInit Not in Accordance with Specs</a></li><li><a href="qs-raw-work.md?plain=1#L2953">Functions channelOpenTry Not in Accordance with Specs</a></li><li><a href="qs-raw-work.md?plain=1#L2977">Functions channelOpenAck Not in Accordance with Specs</a></li><li><a href="qs-raw-work.md?plain=1#L3001">Functions channelOpenConfirm Not in Accordance with Specs</a></li></ul> |
| Venus                       | e-mode Core Pool                     | EVM        | [Link](https://certificate.quantstamp.com/full/e-mode-core-pool-venus/6e476cd9-4dd6-4df2-b2d1-b668e1b5c4ea/index.html)                                             | <ul><li><a href="qs-raw-work.md?plain=1#L2038">Gas Inefficiency in Pool Operations</a></li><li><a href="qs-raw-work.md?plain=1#L2052">Borrowing Restriction for Emode Bypass</a></li><li><a href="qs-raw-work.md?plain=1#L2074">Universal Core Pool Membership</a></li><li><a href="qs-raw-work.md?plain=1#L2096">Risk Parameter Fallback Might Represent Logic Edge Case</a></li><li><a href="qs-raw-work.md?plain=1#L2117">E-Mode Inefficiency Compared to Aave</a></li><li><a href="qs-raw-work.md?plain=1#L2135">Forced Liquidation State Inconsistency</a></li><li><a href="qs-raw-work.md?plain=1#L2150">Missing Multi-Category Asset Support</a></li><li><a href="qs-raw-work.md?plain=1#L2165">VToken Transfer Validation Bypass Risk</a></li><li><a href="qs-raw-work.md?plain=1#L2179">Inconsistent Error Handling Across Facets</a></li></ul> |
| TAC                         | Zerolend Proxy Re-Audit              | EVM        | [Link](https://certificate.quantstamp.com/full/tac-zerolend-proxy-re-audit/5d22c8cb-48f8-4d05-9fe5-d595d9f1bdd8/index.html)                                        | <ul><li><a href="qs-raw-work.md?plain=1#L2466">Possible Wrong Balance Calculation in claimSA Function</a></li><li><a href="qs-raw-work.md?plain=1#L2493">Hardcoded Bridging Token Amount in Borrow Function</a></li><li><a href="qs-raw-work.md?plain=1#L2517">Missing Events for Critical Operations</a></li></ul> |
| TAC                         | Euler Proxy                          | EVM        | [Link](https://certificate.quantstamp.com/full/tac-euler-proxy/3cb7db37-a824-4837-ba32-a7672843007a/index.html)                                                    | <ul><li><a href="qs-raw-work.md?plain=1#L2641">No Fee for Tokens that Are Bridged Back</a></li><li><a href="qs-raw-work.md?plain=1#L2653">A Large Number of Tokens to Bridge Could Self DoS the Request</a></li></ul> |
| TAC                         | Carbon Proxy                         | EVM        | [Link](https://certificate.quantstamp.com/full/tac-carbon-proxy/291c3fae-d737-4a78-9673-aa43aff0e703/index.html)                                                    | <ul><li><a href="qs-raw-work.md?plain=1#L1834">Unbounded Token Array Processing Gas Risk</a></li><li><a href="qs-raw-work.md?plain=1#L1861">Missing Input Validation Controls</a></li></ul> |
| Zircuit                     | L2 Upgradeable Contract              | EVM        | [Link](https://certificate.quantstamp.com/full/zircuit-l-2-upgradeable-contract/e765bc0e-0cbc-40f8-9a84-a7cfbd91cae0/index.html)                                    | - |
| OpenLedger                  | Banking Contract                     | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| OpenLedger                  | Governance                           | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| OpenLedger                  | Staking                              | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Hashflow                    | Kalshi                               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| FDFI                        | Smart Account Smart Contract         | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Hypha                       | Liquid Staking                       | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Position Swapper            | General protocol audit               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Profitr                     | Token                                | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| ShredPay                    | General protocol audit               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Temple                      | Queue Manager                        | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| OpenLedger                  | OFT Adapter                          | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| TIBBERS TEST - ShredPay     | General protocol audit               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| TenPlanet                   | General protocol audit               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| BOBG - BlackCell            | General protocol audit               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Hemi                        | Vetro VUSD                           | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Sapien                      | POQ Protocol                         | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Hemi                        | YieldVault                           | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Tapir Protocol              | General protocol audit               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Accountable Capital         | General protocol audit               | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Venus                       | Yield Plus                           | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Spectrum                    | Spectrum on EVM                      | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Boba Network                | Optimism                             | Go         | _Unpublished_                                                                                                                                                       | _Unpublished_ |
| Berachain                   | BEX                                  | EVM        | _Unpublished_                                                                                                                                                       | _Unpublished_ |


### Auditing at Zokyo

| Client                 | Description                                            | Technology | Report                                                                                       |
|------------------------|--------------------------------------------------------|------------|----------------------------------------------------------------------------------------------|
| Limit Break            | Audit for PaymentProcessV1                             | EVM        | [Link](https://github.com/limitbreakinc/payment-processor/blob/main/audits/Limit_Break_Zokyo_audit_report_June12_2023.pdf)           |
| Limit Break            | Audit for minimum foor operator                        | EVM        | [Link](https://github.com/zokyo-sec/audit-reports/blob/main/Limit%20Break/Limit%20Break_Zokyo_audit_report_June12th_2023.pdf)           |
| Fox Yieldy             | General protocol audit                                 | EVM        | [Link](https://github.com/zokyo-sec/audit-reports/blob/main/FoxYieldy/FOX%20Yieldy%20audit%20report.pdf) |
| Global Interlink (GIL) | Move audit                                             | Move       | [Link](https://github.com/zokyo-sec/audit-reports/blob/main/Global%20Interlink%20(GIL)/Global%20Interlink%20audit%20report.pdf) |
| Umami                  | Multiple audits for Umami such as GLP vaults and yield | EVM        | [Link](https://github.com/zokyo-sec/audit-reports/tree/main/Umami) |
| TigrisTrade            | General audit over new features                        | EVM        | [Link](https://github.com/zokyo-sec/audit-reports/tree/main/TigrisTrade) |
| Velocore               | Audit of all protocol v1                               | EVM        | [Link](https://drive.google.com/file/d/1m2pX_XPrTfyxpVumcoklZJO0mNN1Y-rm/view) |



## Bug Bounty
| Program                                    | Description             | Severity | Platform     |Writeup                                                           |
|--------------------------------------------|-------------------------|---------|--------------| -------------------------------------------------------------------|
| [TempleDao](https://x.com/templedao) | Value extraction etc... | Low     | Hats Finance | [Link](https://x.com/0xStefanAndrei/status/1684626794727489537) |
