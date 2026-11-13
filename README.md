# Scyllarus Keyword Planner

**Turn a rough idea into a clearer business, a memorable name, and an actionable keyword plan.**

An open-source AI brainstorming and keyword planning project by **[Scyllarus](https://github.com/scyllarusllc)** for business brainstorming, domain ideation, and SEO keyword research. Bring an idea, a website, or a Google Keyword Planner export. Available as an AI skill today; a website version is a future direction, not an available feature.

[中文说明](README.zh-CN.md) · [Try an example](examples/saipan-marketplace.md) · [Read the skill](skills/keyword-planner/SKILL.md) · [Work with Scyllarus](mailto:hey@scyllar.us)

## What you can do

| Start with | Work toward |
| --- | --- |
| “I want to build something for my local community.” | Audience hypotheses, customer problems, and a focused business direction |
| “What should I call it?” | Brand and domain candidates with clear tradeoffs |
| “How would people find it?” | Search intents, keyword clusters, and a prioritized page plan |
| A Google Keyword Planner export | An interpretation of demand and advertising metrics with their original context |

The skill separates generated ideas, observed evidence, and measured data. It does not invent search volume or claim that a domain is available without checking.

## Quick start

Clone this repository and ask your AI coding agent to read `skills/keyword-planner/SKILL.md`:

```sh
git clone https://github.com/scyllarusllc/keyword-planner.git
cd keyword-planner
```

Example request:

> Read skills/keyword-planner/SKILL.md and use it to explore a Saipan marketplace for rentals, supermarket promotions, and local supply and demand. Start with positioning and domain names. Reply in Chinese. Label unverified ideas and do not invent keyword metrics.

For an agent with a skill-directory mechanism, copy the entire `skills/keyword-planner/` folder; it contains `SKILL.md`, `agents/openai.yaml`, and supporting references. Follow your agent's skill installation instructions; merely cloning the repository does not install it globally.

## Prompts to try

**Find a sharper idea**

> Help me explore who this idea serves, what problem they need solved, and which niche to start with. Compare the strongest directions and explain your recommendation.

**Brainstorm a name**

> Generate brand and domain candidates for this concept. Compare memorability, pronunciation, geographic fit, and room to expand. Keep availability unknown unless checked.

**Build an SEO plan**

> Expand these seed keywords, group them by search intent, and propose useful landing pages. Prioritize business relevance and label which conclusions have evidence.

**Interpret real keyword data**

> Analyze my Google Keyword Planner export. Preserve ranges and targeting context. Separate advertiser competition from organic SEO difficulty.

## Google Keyword Planner relationship

This is an independent AI skill, not a Google product or a bundled Google Ads integration. It can guide qualitative research and analyze supplied exports. Live Google metrics require a separately available, authorized data connection. See [data handling and official references](skills/keyword-planner/references/google-data.md).

## Bring your idea to Scyllarus

Have a project that is hard to name, position, or explain? Send me:

- Your idea in a few sentences.
- Who you want to help and where they are.
- The decision you are stuck on: niche, name, keywords, or next step.

**[Email Scyllarus: hey@scyllar.us](mailto:hey@scyllar.us)** · **[GitHub: @scyllarusllc](https://github.com/scyllarusllc)**

For reusable improvements or bugs, [open an issue](https://github.com/scyllarusllc/keyword-planner/issues). Use email for private project details. Please do not post credentials or private customer information in public issues.

## Contribute

Useful contributions include realistic examples, clearer research workflows, and fixes for misleading interpretations of keyword data. Describe the problem, expected behavior, and any public evidence in an issue or pull request. Keep examples clearly labeled when their data is fictional or unmeasured.

## Naming and project direction

The product name is **Scyllarus Keyword Planner**; the repository and skill identifier remain `keyword-planner`. We use singular **keyword** as the modifier in “Keyword Planner.” Read the [naming decision record](docs/naming.md) for alternatives, the skill-first roadmap, and copyright and trademark considerations.

## License

[MIT](LICENSE) — use, adapt, and share the skill with the license notice included.
