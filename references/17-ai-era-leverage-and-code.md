# 17 · AI-era leverage and code

Sources in this chapter: RICH-22 (17 Apr 2019) · NAV-ai (19 Feb 2026) · NAV-code (28 Apr 2026, a podcast with
Nivi) · NAV-industrial (1 Jun 2026, a panel episode with Nivi and three guests; only lines labelled `Naval:` are
quoted).

**Dated and moving fast.** These episodes are from 2026 and describe tools that change month to month. He says so
himself: knowing the edges of what the tools can do "is a moving target." [NAV-industrial] Read this for the
principles, not the tool list.

## Code leverage just got cheaper

In 2019 he called coding a way to command "robot armies" [RICH-22]. In 2026 he says coding agents had reached the
point where they could build apps end to end, and describes building his own private set of apps for himself and
his family [NAV-code]. The effect, in his words:

> "It takes the number of people who might have built apps from like 0.1 percent to one or two or three percent
> in the populace." [NAV-code]

> "But for the people who are creative, who are self-motivated, and who are articulate and have a good vision,
> you can code now." [NAV-code]

He also notes the limit: most people still won't code their own apps, and when an app needs to scale you still
want a great team and real engineers [NAV-code].

## Judgement and taste are the scarce inputs

> "So now a programmer with a fleet of AIs is, call it 5-10x more productive than they used to be." [NAV-ai]

He adds that choosing the right thing to work on, versus the wrong thing, is "an infinity difference" and depends
on judgement more than programming skill [NAV-industrial]. With so much content and software, "there's no demand
for average." [NAV-ai] But: "However, the set of things you can be best at is infinite." [NAV-ai] His summary of
what humans still bring is creativity and taste, plus enough agency to start and stick with it
[NAV-industrial].

## Spend tokens, save time

> "So I would say—just waste tokens, save time." [NAV-industrial]

His reasoning: however expensive the models seem, they're still far cheaper than a human, so measure your time and
the final output, not the tokens [NAV-industrial]. He says he doesn't bother learning prompt tricks, and would
rather let the AI learn how to be useful to him [NAV-ai].

## Humans as verifiers, and automate what repeats

He describes much of the old work of lawyers, engineers and operations people moving to verifying what the AI
produces and standing behind it [NAV-industrial]. And:

> "If there's anything left to automate, automate it—get it out of your life, it'll free you to be creative, and
> that's where you generate all the value." [NAV-industrial]

## What it does to companies and hiring

- **Pure software is a weak moat.** If your whole advantage is software others can't build, he calls it
  uninvestable, because others can hack it together and the agents keep improving [NAV-code].
- **More small teams.** He argues that higher productivity means more hiring, not less, and that of someone really good with
  AI: "I want to hire them more than ever, for the leverage." [NAV-industrial]
- **Generalists gain.** He says the falling barrier means "generalists are having a field day." [NAV-industrial]
- **The one thing to do.** "the single best thing you can do for yourself is get really good with these tools,
  and always know the edges of what they can and can't do." [NAV-industrial]

## How to apply it (our reading)

1. **List your repeated tasks** for one week. Anything done three times is a candidate to automate
   [NAV-industrial].
2. **Prototype one tool** you'd otherwise have paid for or waited on, with a coding agent, in a weekend.
3. **Move your own role up** to choosing what to build and verifying the result.
4. **Put the moat elsewhere:** specific knowledge, distribution, network effects, data, or hardware [NAV-code].
5. **Re-check the edges** every quarter; what failed last quarter may work now [NAV-industrial].

**Worked number (invented).** An operations manager at a 40-person logistics firm spends 8 hours a week
reconciling shipment spreadsheets. With a coding agent she builds a small checker in two weekends, using about
$60 a month in model usage. Saved: about 30 hours a month, roughly $1,800 at her loaded salary, and fewer errors.
Then she spends four of the freed hours a week on a routing tool no vendor sells for their niche. That's code
leverage plus specific knowledge, without hiring.

**Failure modes (our reading):**
- Shipping AI-written code to production without anyone verifying it.
- Treating a prototype as a company; scaling still needs a team [NAV-code].
- Building a business whose only edge is software anyone can now generate.
- Learning tool tricks instead of getting better at choosing what to build [NAV-ai].

**Limits:** these are early, enthusiastic views from a builder and investor in the field. Costs, accuracy and
rules about data and liability differ by industry and country.

**Use it now:** `templates/11-ai-leverage-plan.md`.

**Checks to run:**
1. Which of your weekly tasks repeat, and which could an agent do while you verify?
2. What could you prototype this weekend that you've been waiting on someone else to build?
3. If anyone can now copy your software, what is your real moat?
4. Do you know where the current tools fail in your field?
