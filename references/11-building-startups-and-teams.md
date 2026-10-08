# 11 · Building startups and teams

Sources in this chapter: NAV-the-80-hour-myth (29 Nov 2005) · VH-pick-cofounder (12 Nov 2009, byline Naval) ·
VH-startup-principles (26 Apr 2010, byline Naval) · VH-passion-market (17 Jul 2011, byline Naval) · TF-QA (2 May 2016) ·
NAV-build-a-team-that-ships (27 Apr 2012) · RICH-11 (22 Mar 2019) · RICH-28 (6 May 2019) · RICH-36 (23 May 2019) ·
NAV-principal-agent (8 Jul 2019) · NAV-relationships (19 Jul 2019) · NAV-truly (26 Jul 2025) · NAV-fool (22 Sep
2025) · NAV-simplest (1 Oct 2025) · NAV-curate-people (7 Nov 2025) · NAV-code (28 Apr 2026) · NAV-sell (11 May 2026) · X posts (2024, 2025).

This chapter is the founder's overview. Recruiting and culture are in chapter 14, selling and deals in 15,
fundraising in 16, and AI-era building in 17. Venture Hacks posts were co-written by Naval and Babak Nivi; the ones
quoted here carry Naval's byline.

## What changed between 2010 and 2026

His 2010 one-page method [VH-startup-principles], our paraphrase: move to Silicon Valley (in 2016, any startup
hub [TF-QA]); pick a great co-founder with complementary skills; hire for intelligence, energy and integrity; pick
a big market; build a minimum viable product to test what the market needs; iterate until you find
product/market fit, and don't raise money until you do; then raise from people you trust, keep control, and
scale. The core line: "Iterate like crazy until you find product/market fit." [VH-startup-principles]

Our reading of how his newer sources update it:

| 2010 step | What the 2025 and 2026 episodes add |
|---|---|
| Move to a hub | Still his default for tech; but AI tools let small teams anywhere build prototypes [NAV-code] |
| Pick a co-founder | Still the biggest call; one seller, one builder [NAV-curate-people] |
| Hire well | Founders can't outsource recruiting, and early teams look like cults (chapter 14) [NAV-curate-people] |
| Build an MVP | A founder can now often prototype alone with coding agents (chapter 17) [NAV-code] |
| Iterate to fit | Iterations, not hours; good teams throw away most of what they build [NAV-curate-people] |
| Raise money | Raise early, from excitement, and walk away from bad terms (chapters 15 and 16) [NAV-sell] |

## Before product-market fit, passion-market fit

His 2011 argument: product-market fit is precise and the Internet is efficiently arbitraged, so you're most
likely to find it if you're obsessed with the market and have worked on it a long time [VH-passion-market]. He
later adds the founder to the fit [RICH-28]. His 2024 framing of the search: "A startup is a treasure hunt for a
true but untapped behavior." [X 2024-06-10](https://x.com/naval/status/1799988029643464854) In the same post: the
quality of the product is the quality of the search [X 2024-06-10](https://x.com/naval/status/1799988029643464854).

## The co-founder is the biggest decision

> "Picking a co-founder is your most important decision. It's more important than your product, market, and
> investors." [VH-pick-cofounder]

> "The ideal founding team is two people, with a history of working together, of similar age and financial
> standing, with mutual respect." [VH-pick-cofounder]

His other rules in that post, paraphrased: two is the right number; one builds and one sells; motives are
revealed, not declared; if you're compromising, keep looking; and if you're going to fall out, do it early, with
founder vesting in place [VH-pick-cofounder]. In 2025 he still describes the usual pair as one person better at
selling and one better at building [NAV-curate-people]. And: "The most under-recognized reason startups fail is
because the founders fall apart." [NAV-relationships]

## Build a team that ships

His 2012 rules for the early AngelList team, paraphrased [NAV-build-a-team-that-ships]: keep the team small, all
doers and no middle managers; let people choose what to work on; ship to production every week; one person per
project, alone accountable. His own caveat in the post: they shipped too many half-baked features
[NAV-build-a-team-that-ships].

## Incentives are half of management

> "If you can hack your way through the principal-agent problem, you'll probably solve half of what it takes to
> run a company." [NAV-principal-agent]

Be honest with hires about the deal. He says that at some level every founder has to lie to every employee, and
offers an alternative: tell entrepreneurial hires you'll support them when they leave to start their own thing
[RICH-36].

Why scale fights invention, in a 2025 post: hierarchy brings in the principal-agent problem, and "Going from zero
to one requires a founder-led flat team." [X 2025-03-22](https://x.com/naval/status/1903559048089485593)

## Someone holds the whole product in their head

He says the key person in going from zero to one is usually the founder, the one "who can hold the entire problem
in their head and make the trade-offs" [NAV-simplest].

## Take feedback from customers, not applause

> "You need customers. That's your real feedback." [NAV-fool]

He adds that optimizing for magazine covers or awards means you're failing [NAV-fool].

## What it costs you

> "You are the business. You are the product. You are the work." [NAV-truly]

He calls that the curse of the entrepreneur, and adds that a taste of that freedom can make you unemployable
[NAV-truly].

## How to apply it (our reading)

1. **Founding pair check.** Name the builder and the seller. If one is missing, that's the first hire or
   co-founder search.
2. **Write the market hypothesis** in one line, and the cheapest test of it.
3. **Count iterations,** not hours: how many shipped experiments with a real result each week?
4. **Set a fit bar** before raising: a number of users or revenue that would make you excited (chapter 16).
5. **Founder vesting and a written split** before any outside money [VH-pick-cofounder].

**Worked scenario (invented).** Two engineers want to build scheduling software for dental clinics. Neither has
sold anything. Our reading of his rules: find a seller co-founder who knows clinics, or one of them commits to
selling; ship a prototype in two weeks with coding agents; run 20 clinic demos before raising. A full pre-seed
example is in `examples/02-pre-seed-founder.md`.

**Failure modes (our reading):**
- Two builders and no seller, or the reverse.
- Hiring managers before there's anything to manage [NAV-build-a-team-that-ships].
- Raising before fit and scaling a guess [VH-startup-principles].
- Optimizing for press [NAV-fool].

**Dated numbers:** the 2009 to 2012 posts reflect costs, hubs and cap tables of that time. The direction holds;
the figures are history.

**Use it now:** `templates/04-long-term-partner-check.md` for a co-founder, `templates/08-hiring-scorecard.md` for
early hires.

**Checks to run:**
1. Do you have a builder and a seller? If you're one person, which half is missing, and who covers it?
2. Did you and your co-founder go through something hard before starting? Is founder vesting in place?
3. Has every person shipped something to production in the last two weeks?
4. Who on the team acts like an owner, and does their equity match?
