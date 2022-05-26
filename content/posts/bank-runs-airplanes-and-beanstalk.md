---
title: Bank Runs, Airplanes, and Beanstalk
subtitle: Part I - Protocol-native utility
date: 2022-05-26T20:15:29.456Z
author: Ereal
description: Protocol-native utility - the incentives that align Bean holders
  regardless of market conditions.
image: /assets/uploads/barn-and-beans.png
---
Beanstalk Farms is deeply saddened for everyone affected by the events following UST’s depegging and the ensuing collapse of Terra. 

We firmly believe that a decentralized and scalable stablecoin protocol has the potential to bring open access to digital money to every person with an internet connection. As such, we hope that the DeFi community keeps these possibilities in mind and holds onto its spirit of experimentation.

* * *

This is the first piece in a series that discusses why Beanstalk is more resistant to a fatal bank run than other uncollateralized/undercollateralized stablecoins. Part I covers Beanstalk’s *protocol-native utility* - the incentives that align Bean holders regardless of market conditions.

* * *

[Others](https://twitter.com/jonwu_/status/1523793482850050048?s=20&t=efsPdgRtAc_mfnIO0tppUA) have already done an excellent job of breaking down Terra’s recent bank run, so we'll avoid rehashing the entire sequence of events. Instead, we'll summarize the main points and then focus on what *protocol-native utility* is, why a lack of it ultimately doomed UST, and why it helps make Beanstalk antifragile.

From its inception, Terra’s dual-token system was designed so that LUNA captured the value generated by the protocol’s growth, not UST. As a result, market participants needed some _external _incentive to use UST over any other stablecoin.

Enter Anchor, a third-party savings account built on top of Terra offering 20% fixed interest on deposited UST. That kind of return on a dollar-denominated asset was far higher than anything available on other stablecoins, so Anchor quickly generated a large influx of (inorganic) demand for UST. However, Anchor had nowhere to deploy its deposited UST and earn yield to cover its promised 20%, so it instead relied heavily on subsidies.

And because Anchor was effectively the only place to earn yield on UST, Terra needed it to sustain systemic demand. Once questions around the sustainability of Anchor’s yield arose, the fixed yield was replaced with a variable one, which significantly altered the return profile of Anchor. Then, when the price of UST slightly depegged, market-perceived risk of holding UST skyrocketed, and roughly half of all Anchor deposits fled. With no other use cases for UST, when Anchor’s deposit base shrunk the excess UST supply had nowhere else to flow other than out of the Terra ecosystem entirely. That lack of organic demand meant Terra was ultimately unable to make buying UST or LUNA attractive at *any* price, allowing the bank run to perpetuate.

Instead, Beanstalk is designed from first principles to incentivize any capital entering the protocol to continuously maintain Bean exposure and in doing so participate in the growth of Beanstalk. Because the stability and upside of both UST and LUNA are baked into Beanstalk’s single token – Bean – such that the only way to participate in the growth of the ecosystem is through Bean exposure, demand for Beans is highly correlated with demand for Beanstalk. 

That’s protocol-native utility.

* * *

**Protocol-Native Utility**

Around 1899, Orville and Wilbur Wright set out to solve “the flying problem”. At the time, the latest in aviation technology were motorless gliders capable of floating for up to 30 seconds – but only when wind conditions were absolutely perfect. Without a motor or a steady tailwind, they couldn’t really *do anything*. In other words, early gliders had no native utility.

Modern airplanes do, since they can fly essentially regardless of what’s going on outside of the cockpit. 

Now, recall that we previously discussed Terra's reliance on Anchor to generate utility for UST holders. For a time, the price of UST remained at peg because of the tailwind created by Anchor’s subsidized yield. As faith in Anchor faltered, however, Terra’s glider began to feel the effects of gravity.

Beanstalk is the first uncollateralized stablecoin protocol to create protocol-native stablecoin utility – it’s the only airplane on the market. 

**How Beanstalk’s Autopilot Works**

Beanstalk is designed to fly no matter the conditions it faces. Still, like any plane, sometimes it hits patches of turbulence. As an autonomous monetary system, Beanstalk can’t be reliant on any one pilot – it has to be able to fly on autopilot. 

Any autopilot system worth its salt, though, has a variety of tools it can use to safely navigate the air. In practice, Beanstalk avoids performing open market operations as much as possible, and instead incentivizes each individual participant to contribute to peg maintenance. This makes manipulating the economic model very difficult. 

Let’s walk through two of Beanstalk’s primary tools:

*The Silo and Stalk*

Beanstalk’s native liquidity center, the Silo, is designed to incentivize participants to make long-term Deposits and contribute to peg maintenance. Every Bean or LP Token Deposit receives Stalk and Seeds. Stalk is the governance token which entitles holders to receive a share of new Bean mints. Seeds generate new Stalk every Season. Unlike UST, Stalk allows Bean and LP Token holders to participate in the growth of the Bean supply at the protocol level. 

When assets are withdrawn from the Silo, all Stalk for the Deposit must be forfeited. In the event of a bank run on Beanstalk, Stalk must be burned in order for people to leave and sell. As a result, the more Beans that are removed, the more Stalk gets burned, and the higher the opportunity cost associated with burning each additional Stalk. So as a bank run deepens, the opportunity cost for leaving the Silo actually grows.

What this all means is that Silo Members’ (i.e. Depositors of Bean or LP Tokens) participation in the growth of the Bean supply _increases _the longer they are in the Silo, and increases further anytime someone else exits the Silo. And nothing is reliant on subsidized yield or third-party use cases – it all exists at the protocol level.

*Convert*

To date, most stablecoins have had negative carry, such that holding it or using it has an associated opportunity cost. Beanstalk is willing to compensate individuals for their exposure to Bean, meaning it’s actually positive carry. Convert functionality lets individual Silo Members maximize the carry associated with their Bean exposure via active participation in peg maintenance. 

Specifically, it allows Silo assets to be swapped for one another to maximize returns without a loss of Stalk from Seeds in two scenarios:

1. When the price of Bean > $1, Silo Members can Convert Deposited Beans to Deposited LP Tokens, and;
2. When the price of Bean &lt; $1, Silo Members can Convert Deposited LP Tokens to Deposited Beans.

By allowing Silo Members to Convert Deposited assets without needing to Withdraw assets and lose their Stalk from Seeds, Beanstalk allows every Silo Member to manually arbitrage the price of Bean back to its peg.

From a systemic perspective, Convert improves the market efficiency of Beanstalk assets. In practice, it’s been responsible for two major outcomes for the protocol: 

1. Reducing price volatility; and
2. Increasing the ratio of liquidity to total Bean supply during growth cycles, which creates runway during bank runs that are inevitable in any monetary system.

From an individual participant’s standpoint, Convert allows peg maintenance to become a profit-maximizing activity, so in the instance where the Bean supply is in short-term excess (*i.e.*, P &lt; 1), the yield maximizing behavior for a Silo Member is to Convert LP to Beans, thereby increasing the price of Bean. Similarly, in the instance where there is a short-term shortage of Beans, (*i.e.*, P > 1), the yield maximizing behavior for a Silo Member is to Convert Beans to LP, thereby increasing the price of Bean. **Another way of saying that is that those who perform peg maintenance are the same people who most participate in the growth of Beanstalk.** 

With Anchor – when price of UST depegged – UST holders could either a) sell their UST at a discount, or b) wait for the price of UST to return to peg. Instead, in Beanstalk, Silo Members can actively participate in peg maintenance such that the choice is to a) sell Beans at a discount *and* realize opportunity cost in the form of Stalk from Seeds, or b) Convert LP to Beans, which in effect buys Beans below peg. The opportunity to participate in peg maintenance is the result of protocol-native utility, because the exposure to Beans themselves is what entitles each Silo Member to yield. 

Protocol-native utility is created by  the alignment of interests between a protocol and its tokenholders. 

**Conclusion**

During periods of exuberance, just about any project with an ambitious enough roadmap in hypergrowth looks generational. It’s when markets sober up, however, that true product-market fit separates itself from hype. 

The demand for stablecoins is massive, which means the prize for domination is too. Accordingly, the allure of subsidizing rewards to create artificial demand is intoxicating. As the DeFi community recently witnessed with Terra, however, growth via mercenary capital does not equal product-market fit. Token holders need good reason to stick around when turbulence hits.

This is what makes Beanstalk unique. It creates protocol-native incentives via Stalk, the Silo and Convert functionality that reward Bean holders for contributing to the protocol’s health. To date, Beanstalk has never offered a subsidy for Silo Members, and has grown organically from an initial supply of 100 Beans at launch to over 108 million Beans at the time of the April 17 governance attack. By that point, Beanstalk had attracted ~$77 million of liquidity. Despite having 0 collateral, Beanstalk had over $.70 in value trading against every Bean in supply. 

That’s what a sustainable non-collateralized stablecoin looks like.

* * *

Thank you for reading. If you’d like to stay up to date on Beanstalk, subscribe to our newsletter [here](https://bean.money/). 

Visit our [Discord](https://discord.gg/xxMMbFbA) as well to join our active and thoughtful community dialogue.