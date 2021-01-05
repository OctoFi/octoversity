---
title: What is impermanent loss?
subtitle: 
categories: [support, pools]
author: marco
---

An important aspect to consider when providing liquidity to automated market maker (AMM) protocols (such as Uniswap) are impermanent losses.

Many beginners to DeFi and providing liquidity are unaware of the risks and consider providing liquidity a ‘hold and earn’ type of situation. Whereas this can certainly be true, we’d like to also inform you about these interest-ink risks.

TLDR: Impermanent losses are the ‘losses’ made by providing liquidity to the protocol versus having held the same altcoins in a wallet. They are impermanent because these losses could well be made up for. This happens once the prices of the provided tokens return to the prices they were when you entered the liquidity pool.

Unfortunately, impermanent losses sometimes turn into real (cost-opportunity) losses. Meaning the returns are lower than they would have been if you had held the altcoin that went up in price (eating your profits), or in case of negative price action leaving you with real losses.

## How does this happen?

A big discussion (and concern) around the current AMM protocols are impermanent losses and leeching. This is one of the main reasons institutional money hasn’t entered in masses yet.

Impermanent losses happen when the prices of your deposited tokens (liquidity) change. The bigger these prices change, the more you’re exposed to impermanent losses. This means the value of your deposited funds is lower versus the time of deposit.

Next to that, liquidity leeching is still a concern. This is done in two ways:

- Uniswap (and other AMMs) have seen trading bots take advantage of users that set high slippage %s. The bot would pre-pump the price before the user’s transaction executes to match the tolerated slippage, and sell immediately after. Leaving the swapper with immediate losses and the bot with profits, sucking liquidity from the pool.
- Arbitrage hunters. AMMs don’t automatically match prices of external exchanges, this is done by arbitrage takers. They’d sell (or buy) on the AMM for additional profits, and sell these on external exchanges, also sucking liquidity from the pool.

## Does this mean providing liquidity isn’t worth it?

Not at all, providing liquidity is actually tenta-cool! Liquidity pools that are quite risky in terms of impermanent losses can still earn you money. Impermanent loss alone doesn’t mean you cannot earn money, if this were the case there wouldn’t be so much liquidity provided to trading pools.

To stick with our Uniswap example, Uniswap charges 0.3% in trading fees which are distributed among all liquidity providers on that specific trading pool (e.g. OCTO/ETH trading pool). Your earned fees would depend on your pool share (%).

Overtime, pools that attract large volume or return to their original price state can earn you plenty of trading fees and offset your impermanent losses. This while simply holding the liquidity pool tokens after all.

If you’re new to providing liquidity, we would well recommend you to first do so with a smaller amount. So you’ve sailed the dangerous waters and can thereafter enjoy more calm waters. And what do we call a relaxed octopus? A calm-ari!
