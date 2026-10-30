# StakingGuide

Crypto staking explained: rewards, lockups, validators, and risks. Staking means locking up crypto to help secure a proof-of-stake blockchain, in return for rewards.

> This guide is educational only, not financial advice. Staking rewards are not guaranteed, and staked assets can lose value or be penalised.

## 1. What staking is

In a **proof-of-stake (PoS)** blockchain, validators are chosen to propose and verify new blocks. To become a validator, you lock up ("stake") the network's native coin as a bond.

- If a validator behaves honestly, it earns rewards (newly issued coins and transaction fees).
- If it misbehaves — for example, by going offline or signing conflicting blocks — it can lose part of its stake. This penalty is called **slashing**.

Most people do not run a validator themselves. Instead, they **delegate** their stake to a validator, or stake through a pool or exchange, and share in the rewards minus a fee.

## 2. Why networks pay for staking

Staking replaces the energy-hungry mining of proof-of-work with an economic bond:

- Validators have something to lose, so they have a reason to behave honestly.
- Rewards compensate stakers for locking up capital and for the risk of slashing and price falls.
- The network stays secure as long as attacking it would cost more than the attacker could gain — which requires controlling a large share of staked coins.

## 3. Ways to stake

### Running your own validator
You set up a node, stake the required minimum, and maintain it 24/7.

- Pros: full control, no intermediary fee beyond your own costs.
- Cons: technical work, minimum stake can be large (for example, 32 ETH on Ethereum), downtime and misbehaviour risk slashing, and your stake is locked.

### Delegating to a validator
You assign your stake to an existing validator and keep ownership of your coins (on most networks, delegated coins never leave your wallet's control in the same way as an exchange deposit).

- Pros: no node to run, lower minimums, you can usually switch validators.
- Cons: the validator takes a commission, and you share its slashing risk if it misbehaves.

### Staking through an exchange
The exchange stakes on your behalf and pays you a share of rewards.

- Pros: simplest option, often no minimum, one click.
- Cons: the exchange holds your coins, can change rates, can pause withdrawals, and can fail. You also cannot choose the validator.

### Liquid staking
You stake through a protocol and receive a **liquid staking token** (for example, stETH) representing your staked position, which you can trade or use in DeFi while still earning staking rewards.

- Pros: your capital is not locked; you can exit by selling the liquid token.
- Cons: the liquid token can trade below the value of the underlying stake, the protocol adds smart contract and governance risk, and rewards are shared with the protocol.

## 4. Rewards: what the percentage really means

Staking rewards are usually quoted as an **APR or APY** (annual percentage rate / yield).

- **APR** is the simple annual rate. **APY** includes compounding, so it is higher if rewards are restaked.
- The rate is not fixed. It changes with the total amount staked, network issuance, and validator performance.
- Rewards are paid in the staked coin itself. If that coin's price falls 30% while you earn 5% in rewards, you are still down about 25% in dollar terms.
- Some "staking" offers on exchanges or apps are actually lending: your coins are lent to traders or protocols, and the return comes from that lending, with its own risks. Read the terms to know which one you are doing.

**Always ask:** is this reward paid by the network's issuance, by transaction fees, by lending my coins, or by a newly minted reward token? Each source has different risks.

## 5. Lockups and unbonding

Many networks do not let you withdraw staked coins instantly.

- **Lockup / bonding period:** the time your stake is committed after you stake.
- **Unbonding period:** after you request to unstake, you wait — often days to weeks — before the coins are liquid again. During unbonding, you usually earn no rewards, and you cannot sell if the price crashes.

This matters in a crash: you can watch the price fall and be unable to exit until unbonding finishes. Liquid staking avoids this, but adds its own risks (see above).

## 6. Risks, honestly listed

| Risk | What happens |
|---|---|
| Price risk | The staked coin falls in value more than rewards compensate |
| Slashing | Your validator misbehaves and part of your stake is destroyed |
| Validator downtime | A poorly run validator misses rewards, or gets penalised |
| Lockup risk | You cannot sell during unbonding while the price falls |
| Exchange / custodian risk | The platform holding your stake fails, freezes withdrawals, or is hacked |
| Smart contract risk | A liquid staking protocol has a bug or is exploited |
| Liquid token depeg | A liquid staking token trades below its underlying value |
| Inflation | Rewards are paid by issuing new coins, diluting all holders — your "reward" may just keep pace with dilution |
| Tax and regulatory risk | Staking rewards may be taxable when received, and rules vary by country |

## 7. Choosing a validator (if you delegate)

Check:

1. **Commission:** what percentage the validator keeps. Very low commission can be a marketing trick that rises later; very high commission eats your rewards.
2. **Uptime and performance:** a validator that is often offline earns less and risks penalties.
3. **History:** how long it has operated, and whether it has ever been slashed.
4. **Self-stake:** validators with their own coins at stake have more skin in the game.
5. **Size:** an extremely large validator concentrates network power. Spreading stake across smaller, reliable validators helps decentralisation.
6. **Jurisdiction and identity:** known operators are more accountable than anonymous ones, but also more exposed to regulation.

You can usually redelegate to a different validator without unbonding, but check your network's rules — some charge a fee or impose a waiting period.

## 8. Staking checklist

- [ ] I understand whether I am staking, delegating, or lending — and the difference.
- [ ] I know the lockup and unbonding periods.
- [ ] I know the validator's commission and history, or the exchange's terms.
- [ ] I know what happens if the validator is slashed.
- [ ] I am staking only an amount whose price fall I can tolerate.
- [ ] Rewards are a bonus, not the reason I hold the coin.
- [ ] I have a plan for taxes on rewards in my country.

## 9. Common mistakes

| Mistake | Better approach |
|---|---|
| Chasing the highest APR without checking lockup | Compare APR, lockup, and slashing together |
| Staking everything on one validator or exchange | Spread across validators; keep some liquid |
| Assuming rewards mean profit | Subtract price change and inflation first |
| Ignoring unbonding time | Never stake funds you might need urgently |
| Using an unknown "staking" site promising huge returns | If the return is far above the network rate, it is lending, leverage, or a scam |
| Forgetting taxes | Record reward dates and values; check local rules |

## 10. Frequently asked questions

**Is staking passive income?**
It can feel passive, but it is not risk-free income. You bear price, slashing, lockup, and custodian risk for the reward.

**Can I lose staked coins?**
Yes — through slashing, validator failure, exchange failure, smart contract exploits, or simply a price fall larger than your rewards.

**What is the difference between staking and mining?**
Mining (proof-of-work) secures a network with computing power and electricity. Staking (proof-of-stake) secures it with locked-up coins as an economic bond. Both earn rewards; staking uses far less energy.

**Do I keep my coins when I delegate?**
On most networks, delegated coins remain under your control and are not transferred to the validator's wallet, but they are locked and subject to the network's rules. On an exchange, you give up custody — different risk entirely.

**Should beginners stake?**
Staking a small amount on a well-established network, through a reputable validator or exchange, is a reasonable way to learn — after you understand lockups, slashing, and price risk. Do not stake money you need soon, and do not stake your entire holding in one place.

> Educational content only. This is not financial, investment, or tax advice.
