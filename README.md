# battle-tested

A Claude Skill that writes marketing copy using battle rap mechanics.

Most marketing copy gets written in a quiet room where nobody argues back. Battle rap gets written for a room that is rooting for you to fail, judged instantly, against an opponent who gets to respond. That pressure produced a working set of mechanics for making a line land and stick.

Those mechanics port straight to marketing:

| Battle rap | Marketing |
|---|---|
| The angle | Positioning |
| The scheme | Campaign concept |
| Setup and punch | Headline and subhead |
| Rebuttals | Objection handling inside the copy |
| Bar economy | Compression |
| Crowd reaction | Whether anyone repeats it |
| Reputation | Brand |

## What it does

Four modes:

**Open verse.** Nothing written yet. Six rounds from scouting the room to a scored final cut.

**Punch-up.** You have copy and it is fine but forgettable. Usually a missing angle, not weak wording.

**Get bodied.** Claude writes the round your sharpest competitor would drop on you, then you fix what got exposed. Run it before a launch, a pitch, or a pricing change.

**Rebuttal round.** Objections are killing the page. Answer them before the reader finishes forming them.

Every line comes back scored on truth, specificity, compression, repeatability, and room fit. Anything you cannot back gets killed, no matter how good it sounds.

## Install

Claude Code or the Claude apps:

```
git clone https://github.com/MichaelDoesMarketing/battle-tested.git ~/.claude/skills/battle-tested
```

Or drop the `.skill` file into your skills settings. Then just ask for copy. The skill triggers on headlines, taglines, positioning, hero copy, ad hooks, cold email openers, and anything that has to compete for attention. You never have to say the words battle rap.

## Try it

```
This headline is fine but nobody remembers it. Punch it up.
```

```
Write the round my competitor would drop on my homepage.
```

```
Our pricing page loses to "we'll just build it internally." Rebuttal round.
```

## What it actually does

The first thing this skill did, on its first real run, was tell its own author that his LinkedIn headline was selling the wrong decade.

The copy: *Former Battle Rap Champ Turned AI-Native.*

The round it came back with:

> Every marketer on LinkedIn added "AI-native" to their headline in the last eighteen months. You're wearing the most crowded two words on the platform next to the most interesting five, and the crowded ones are doing the framing.
>
> Your headline sells your past. The buyer is standing there with a present-tense problem.
>
> "Battle rap champ" is a claim with no receipt attached. Which league, what record, who'd you beat. And *turned* AI-native says the rap thing is the before picture. You made your differentiator the part you moved on from.
>
> Hardest shot: nothing in the copy says what happens to my business.

Then the fix. New angle, three scored lines, a rebuttal layer, and a list of what got cut and why. Including a line that scored a 9 out of 25 for being alliterative and meaning nothing.

That is the point. It finds positioning problems, not wording problems, and it will find yours the same way.

## Rules of engagement

The skill swings at ideas, claims, and lazy category habits. Never at people, never at anyone's identity. Comparative claims about a named competitor need a real fact behind them.

Edge is a tool, not a personality. In a room that punishes swagger, the mechanics still run quiet.

## License

MIT
