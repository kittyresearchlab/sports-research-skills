# Kitty Research Lab 🐈

Useful AI research skills to try, adapt, and improve together. Keep the thinking curious, the sources traceable, and the workflow flexible.

## Start here: Reddit Sports Research

[Read the skill](skills/reddit-sports-research/SKILL.md) · [Example prompts](skills/reddit-sports-research/references/examples.md) · [Research record format](skills/reddit-sports-research/references/research-records.md)

Turn public Reddit sports discussions into an attributed research digest. Follow useful claims to original reporting, separate observations from verified facts, preserve timestamps and corrections, and carry unanswered questions forward.

Works as a research workflow for NBA, men's college basketball, NCAA women's basketball, WNBA, or your chosen sports. Actual coverage depends on the research tools and public pages your assistant can access. It does not include a Reddit scraper, account login, API credential, paid service, or posting bot.

## Use it

For an agent environment with the skills CLI:

```bash
npx skills add https://github.com/kittyresearchlab/sports-research-skills --skill reddit-sports-research
```

Review the skill before installing. This command runs the skills installer; the research skill itself contains instructions and references, not executable collector code. CLI installation has not yet been tested for this repository. ChatGPT skill installation and sharing use the host's supported Skills interface rather than assuming terminal access.

Example request:

> Use Reddit Sports Research to review the last 24 hours of NBA, men's CBB, and NCAAW discussions. Find a few useful rotation, availability, or tactical leads. Link the sources, explain what is verified, and identify the next useful checks. Keep the sports separate.

Choose your own teams, competitions, time window, and research destination. Installing a skill does not create a scheduled task. Ask your assistant separately to schedule collection if its environment supports scheduling.

## What to expect

- A concise digest with original links and attributed observations.
- Clear distinctions among fan observations, attributed reports, independently verified claims, conflicts, and unresolved leads.
- Honest access gaps, including preview-only or blocked Reddit reads.
- Research additions that preserve existing forecasts and model settings.

This is a research aid, not a proven betting edge. Popular discussion is not independent confirmation. It does not post, comment, vote, message, or automatically change predictions.

## Initial validation

The skill passed a format check and two exploratory trials: a live three-sport roundup and a fictional exercise covering copied rumors, postgame timing, inaccessible sources, and instructions hidden inside source material. Live Reddit coverage was partial and relied on indexed excerpts. These trials do not establish comprehensive coverage, reliability across every agent, predictive value, or profitability.

## Build with us

Try the skill on a real question. Open an issue describing what worked, what was confusing, or what would help. Suggest improvements through a pull request. Keep examples public or fictional; leave out personal details, credentials, private research, and account-specific destinations. Small, useful improvements are welcome.

Licensed under [MIT](LICENSE). Reuse and adapt it with the license notice preserved.
