# My thoughts on the Corion ICO

Corion is a new cryptocurrency, its main goal is to have a stable USD
price.  The system aims to ensure that 1 COR is priced close to 1 USD
and fluctuations that are happening should be auto-corrected.

Corion is planned to be hosted on the ETC chain, not on ETH as with
several other ICOs.

During the ICO, 51% of the Corion coins are sold, the remaining 49% is
minted and kept by the Corion Foundation.

On 2017-07-10 I decided to look into Corion to evaluate if I should
contribute to the ICO or not.  This led me to interesting discoveries
that I would like to share with like-minded crypto traders.


# TL;DR

Corion's smart contracts are not on the ETC chain; they are collecting
funds into wallets right now without any contract.  They are late not
just with the product, but even with a simple ICO smart contract, and
they start the ICO anyways!

Corion can abort the ICO and keep 10% of your funds without any
consequences.

Corion has no backing to keep it stable at 1 USD.  It won't ever be
worth a lot more, but no guarantees that it won't be worth a lot less.

The only backing is a stability fund that will own non-corion funds in
the ratio of 6.25%.

They are locked into ETC until the end of the ICO: so when they mint
4M USD worth of COR, it can easily happen that they only have 1M USD
worth of investments when they can finally sell at the end of the ICO.

The team is a group of business people, not technical people.  One of
the founders is a business person who was a leader of a company, which
was part of a company group that is suspected to have organized a
country-wide multi-year Ponzi in Hungary, disguised as an investment
bank, travel agency and other businesses.

# Files in this directory

In the [whitepapers/](whitepapers/) sub-directory you can find the
whitepapers downloaded from http://www.corion.io/ at the time of
writing this article.

In the [slack/](slack/) directory you can find my discussion with the
Corion team on their Slack channel.  We started the discussion in
English, but they asked me to switch to Hungarian (which I speak).  At
this point it was not clear to me, if they will say anything
interesting, so I agreed to switch, sorry.  If there is a demand for a
translation, I will try to make one myself (contributions are
welcome).

In the [solidity/](solidity/) directory you can find the sources of
the solidity contracts, dowloaded from
[Corion's GitHub](https://github.com/CORIONplatform) at the time of
writing this article.

# Corion is not on the ETC chain

After studying the source code of the contracts, I wanted to look at
them live on the blockchain, since the ICO is going strong for more
than a month now and wanted to see how the contract is doing.

After looking for it and unable to find, I asked on Slack and it
turned out that they are not at all on the ETC blockchain yet!  They
are late and couldn't finish the ICO smart contract before launch of
the crowdsale, so they just started to collect ETC into wallets.

Once the code is ready, they promise to send out the coins for the
already existing contributions and then it will be possible to
contribute to the ICO the smart contract way, as with other ICOs.
Alas, they will only be ready for the last days of the ICO, so whoever
wants to contribute safely will get no bonuses and will have a very
short period of time to review everything and make the decision.

# The 10% trap called abort

Also, reading the smart contract, you will find one other peculiarity
that is not advertised anywhere on the website, only mentioned in the
whitepaper.

For any reason, at the Corion's discretion, they can abort the ICO at
any point while it runs.  If this abort is called by Corion, then
everyone can get back 90% of their ETC (in exchange for some gas).
The remaining 10% is kept by Corion in this case, as a payment for
their super hard work and marketing that they already invested in the
project.

They can also extend the ICO indefinitely and abort during the
extension periods.

# Corion is a stable coin without backing

Do you know about Tether, the nice USDT and EURT coins?  Yes, they are
minted when someone pays in USD or EUR and they are backed by these
deposits.  Now, Corion is not like that.

In Corion there are two mechanisms to keep the COR/USD value at 1:

  - if the price is too high, they give free coins to people who
    already own some, this way they make the price drop,

  - if the price is too low, they stop giving out free coins, making the
    price go up.

I trust the first mechanism, it's rock solid.  The second mechanism I
don't trust.

When asked on chat or reading the white paper, the Corion team has two
addiotional points:

  - when the price is below 1 COR/USD, in addition to new coins not
    being minted, also part of the transaction costs are burned and
    lost forever.  This lowers the supply of COR tokens in the world,
    raising the price,

  - from the funds invested during the ICO, 25% is reserved as a
    stability fund that can intervene on the markets.

I think the first point is NOT EVEN CLOSE to stop a dip — like those
we see every week on the crypto markets — to turn into a total bank
run.

# Stability fund: 25%, 12%, maybe not even that?

About the stability fund: on chat they tried to deny its existence,
then they were not sure that it's 25% or not, then they were not sure
that they will intervene on the markets.  Saying things like "please
let the foundation make their own decisions and don't try to question
them".

After some time, they agreed with my interpretation of the whitepaper
and said that they have the 25% stability fund.  Although they kept it
all in ETC during a down market, so the 2M USD contributed so far is
closer to a 250K USD stability fund than to 500K.  Also, in case of 2M
USD contributions, they mint 4M COR tokens.  29% of their share of the
COR tokens will also be used for stability, but with COR tokens they
can only provide stability against rising, not falling price.

So we have a stable coin, which is "backed" by 6.25% reserves, sounds
like Federal Reserve to me!

And BTW, this ratio can go radically down if the coin first goes up:
let's assume that the system starts with 4M coins and with the
inflation mechanism it rises in a bubble to 50M USD.  Then we have a
stable coin worth 50M USD backed by 250K reserves.

# ETC is falling, and no access to the funds before the end of the ICO

During the ICO (if they were following the contract model), they have
a mechanism to adjust the current ETC/COR price in the contract to
match the current ETC/USD price on the markets.  This mechanism is
necessary, because they want to give you COR tokens similar in numbers
to the USD value you invested.

They can withdraw the ETC funds invested at the end of the ICO.
Before the end of the ICO, they only get 10% of the funds right away,
continuously as investments are made.

What does this mean if the ETC price is falling hard during the ICO,
as it is happening now?

It means that they mint COR tokens supposed to be worth 1 USD, but
they only withdraw the ETC funds at the end of the ICO, at which time
they can exchange it to USD for a lot less than when the investment
was made.

When asked on chat about this, their answer was two-fold.  First, as
we already know, COR is not a backed stable coin, therefore the value
of ETC they receive is only bad for their employees and don't change
the investors' situation with regards to Corion.  Second, they said
that they can lengthen the ICO if needed.  I'm not sure what they mean
by that.  If the ETC is not high enough, they extend the ICO in the
hopes it gets higher?  What if it gets lower???

Also, about only being bad for the employees: not true, since the
stability fund is created from the 25% of the ICO funds.  So, it would
be good to have that stability fund as close to the 25% of the
incoming investment as possible, not 10% just because ETC was
dropping.

# The team

They have two core engineers working on the project.  Neither of them
was a founder, they were hired by the management team.

As seen on LinkedIn,
[Dancs Attila](https://hu.linkedin.com/in/attila-dancs-03a00bb9) was
working for almost 7 years in a leadership position at Questor.  This
was a Hungarian company, part of a company group that is now suspected
to have operated a country-wide Ponzi scheme, in which many investors
lost all of their funds in 2015.  The company went bankrupt, arrests
were made and investigations by the authorities started.

Since the Ponzi was really big and a lot of Hungarian people were
involved, the government bailed out part of the investments.  I don't
think they would do the same for Corion though.

# Conclusions, disclaimers, flipping

Finally, as always, we have to have some disclaimers: this is not
investment advice, please only invest in Corion the amount of your
crypto reserves that you want to surely lose!  Do not invest coins
that you don't want to lose!

Also, in the other direction: I'm not responsible if by flipping you
can get a 20-30% profit at the launch of Corion.  Please don't make
your investment decision based solely on this article!  Before you
arrive at the conclusion that this is a Ponzi, make your own research!

I personally hope that they call the `abort` function before it's too
late.  It would be better for all the investors to lose 10% now, than
for the majority to lose a lot more during a bank run later in which
only the lucky fast ones win.

# Rebuttal

If the Corion team would like to write a rebuttal and host it here on
my Github together with this article, I'm totally open to it.

Please open a ticket with your markdown formatted text and publish
this article on your website.  In exchange for that, I will host the
rebuttal here, so everyone can do their research and reach their own
conclusions.

If other people, not involved with the Corion team, have comments or
issues, please don't hesitate to use Github for communication with me
(pull requests, tickets, etc.)

# Comments

This article has also been published
on
[r/ethereumclassic](https://www.reddit.com/r/EthereumClassic/comments/6o8ohk/my_thoughts_on_the_corion_ico/),
feel free to discuss there!

The article has also been posted on r/ethtrader, r/icocrypto and
bitcointalk, but please keep the discussion on the main thread on
r/ethereumclassic.

# Donation

If this article helped you, please consider supporting me by sending
coins to the following ETH/ETC address:
`0xf9b73e65f3decf9f57f292bec0fdf45d8f031bd6`
