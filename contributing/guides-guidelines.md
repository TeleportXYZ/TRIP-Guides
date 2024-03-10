# Guides Guidelines

{% hint style="info" %}
This guide documents guidelines for writing TRIP Guides.

This guide follows itself acting itself as an example of how to write a TRIP Guide.

After reading this guide, you will know:

* What conventions to follow when writing TRIP Guides content.
{% endhint %}

## Prologue

Each guide should start with motivational text at the top (that's the little introduction in the blue area). The prologue should tell the reader what the guide is about, and what they will learn.

In GitBook these are called [Hints](https://docs.gitbook.com/content-editor/blocks/hint).

## Show Don't Tell

"Showing" is stating how TRIP works today. "Telling" is stating how TRIP will work in the future.

Readers want to understand how TRIP works at this moment in time. If we incorporate content about how TRIP can or should work in the future, it creates opportunity for confusion.

Therefore show don't tell when writing TRIP Guides content.

## Roles over Technology

Organize guides around roles users can play and actions users can take within the TRIP protocol rather than around product or tech surfaces.

```
# BAD
# Guide: Rideshare Server

# GOOD
# Guide: How to Match Rides as an Operator
```

## Words to Avoid

Coinbase has done a lot of [consumer research](https://twitter.com/jessepollak/status/1764742947218858477) and "onchain" outperforms every other word that people use for crypto.&#x20;

Therefore avoid using blockchain, web3, crypto, NFT, etc. where possible. Words like blockchain and NFT are ok to use where technical implementation details must be discussed. That said, consider if that content can be reworked to not reference them.

For example, refer to "digital collectibles" instead of NFTs.

## Footer

At the end of each guide include a Hint section like this:

{% hint style="info" %}
#### Feedback

You're encouraged to help improve the quality of this guide.

Please contribute if you see any typos or factual errors. To get started, you can read our [Contributing to TRIP](https://guides.trip.dev/contributing/contributing-to-trip) section.

You may also find incomplete content or stuff that is not up to date. Please do add any missing content by [creating a free account in GitBook](https://app.gitbook.com/invite/0WSd8UiSeH2xhfJrSbUr/YFiygcuBiy7oN3WJyDRs). Check the [TRIP Guides Guidelines](https://guides.trip.dev/contributing/guides-guidelines) for style and conventions.

If for whatever reason you spot something to improve but cannot do it yourself, please [open an issue](https://github.com/TeleportXYZ/TRIP-Guides/issues/).

And last but not least, any kind of discussion regarding TRIP documentation is very welcome in the [official TRIP Community on Telegram](https://trip.dev/chat).
{% endhint %}

## Headings

Use `Heading 1` headings for guide sections. Use `Heading 2` headings for guide subsections. Note that GitBook generates `Heading 1` and `Heading 2` headings as `h2` and `h3` in HTML respectively. That is ok.

When writing headings, capitalize all words except for prepositions, conjunctions, internal articles, and forms of the verb "to be":

```
#### Recruiting and Educating Riders while Driving
#### Teleport is an App
#### When are Cities Unlocked?
```

## Wording

Write simple, declarative sentences. Brevity is a plus. Get to the point.

Use the app [Hemingway](https://hemingwayapp.com/) to help with this as well as assistants like [ChatGPT](https://chat.openai.com/chat) or [Claude](https://claude.ai/).

Don't mindlessly copy and paste from them though or you're likely to make your writing worse.

```
# BAD
# Riders may be able to cancel rides by being able to click the "Cancel Ride"
# button in the app.

# GOOD
# To cancel a ride, click "Cancel Ride" in the app.
```

Use present tense:

```
# BAD
# Requested a trip that...
# Will request a trip that...
# Request a trip that...

# GOOD
# Requests a trip that...
```

Communicate to the reader the current way of doing things, both explicitly and implicitly. Use the idioms recommended in TRIP Guides.&#x20;

Reorder sections to emphasize favored approaches if needed, etc. The documentation should be a model for best practices and canonical, modern TRIP usage.

Documentation has to be brief but comprehensive. Explore and document edge cases. What happens if a rider disputes a trip? What if a driver doesn't show up? What if a user doesn't have an onchain wallet?

### Naming

The proper names of TRIP components have a space in between the words, like "Rideshare Server". All TRIP documentation should consistently refer to TRIP components by their proper names.

Spell rideshare, software, and onchain industry names correctly. When in doubt, please have a look at some authoritative source like their official documentation.

```
Transportation Network Company (TNC)
Transportation Network Provider (TNP)
Fleet Manager
Solana
Anchor
HTML
JavaScript
Ottr
Backpack
Phantom
```

### Pronouns

Write plainly and to the reader. It is ok to use "you"s and "your"s.

```
# BAD
# If referral cards are needed, it is recommended to use a local print shop.

# GOOD
# If you need to print referral cards, use a print shop in your local area.
```

That said, when using pronouns in reference to a hypothetical person, such as "a user with a requested ride", gender neutral pronouns (they/their/them) should be used. Instead of:

* he or she... use they.
* him or her... use them.
* his or her... use their.
* his or hers... use theirs.
* himself or herself... use themselves.

## English

Please use American English (_color_, _center_, _modularize_, etc) spelling and correct grammar.

See [a list of American and British English spelling differences here](https://en.wikipedia.org/wiki/American\_and\_British\_English\_spelling\_differences).

## Oxford Comma

Please use the [Oxford comma](https://en.wikipedia.org/wiki/Serial\_comma) ("red, white, and blue", instead of "red, white and blue").

## Examples

Choose meaningful examples that depict and cover the basics as well as interesting points or gotchas.

{% hint style="info" %}
#### Feedback

You're encouraged to help improve the quality of this guide.

Please contribute if you see any typos or factual errors. To get started, you can read our [Contributing to TRIP](https://guides.trip.dev/contributing/contributing-to-trip) section.

You may also find incomplete content or stuff that is not up to date. Please do add any missing content by [creating a free account in GitBook](https://app.gitbook.com/invite/0WSd8UiSeH2xhfJrSbUr/YFiygcuBiy7oN3WJyDRs). Check the [TRIP Guides Guidelines](https://guides.trip.dev/contributing/guides-guidelines) for style and conventions.

If for whatever reason you spot something to improve but cannot do it yourself, please [open an issue](https://github.com/TeleportXYZ/TRIP-Guides/issues/).

And last but not least, any kind of discussion regarding TRIP documentation is very welcome in the [official TRIP Community on Telegram](https://trip.dev/chat).
{% endhint %}
