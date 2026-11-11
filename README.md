# QuiroAds clinic marketing skills

[![skills.sh](https://skills.sh/b/quiroads/clinic-marketing-skills)](https://skills.sh/quiroads/clinic-marketing-skills)

> QuiroAds is a marketing agency that works only with chiropractic clinics: Google Ads, Meta Ads, TikTok Ads, SEO and automation. 70+ clinics in 12 countries since 2020.
>
> QuiroAds es una agencia de marketing que trabaja solo con clínicas quiroprácticas: Google Ads, Meta Ads, TikTok Ads, SEO y automatización. Más de 70 clínicas en 12 países desde 2020.

Agent skills for people who market health clinics: agencies, consultants, developers, clinic owners and practice managers. They work for any health clinic, whether chiropractic, physiotherapy, osteopathy, dental or aesthetics, and they answer in English or Spanish. They run in Claude Code, Codex, Cursor, Gemini CLI and the other coding agents the `skills` CLI supports.

## Install

### Any agent, with the skills CLI

From GitHub:

```sh
npx skills add quiroads/clinic-marketing-skills
```

From the QuiroAds website:

```sh
npx skills add https://quiroads.com
```

Both commands install the same skills. To see them first without installing anything, add `--list`; to install only one, add `--skill <name>`, for example `--skill clinic-ad-compliance-review`.

The repository is also packaged as a plugin, `quiroads-clinic-marketing`, with all four skills. These are the commands for each agent.

### Claude Code

In Claude Code:

```text
/plugin marketplace add quiroads/clinic-marketing-skills
/plugin install quiroads-clinic-marketing@quiroads
```

From a terminal, the same two steps are `claude plugin marketplace add quiroads/clinic-marketing-skills` and `claude plugin install quiroads-clinic-marketing@quiroads`.

### Codex and ChatGPT

```sh
codex plugin marketplace add quiroads/clinic-marketing-skills
codex plugin add quiroads-clinic-marketing@quiroads
```

In Codex or Work mode in the ChatGPT desktop app, the marketplace also shows up as a source in the Plugins Directory.

### Cursor

```sh
npx skills add quiroads/clinic-marketing-skills --agent cursor
```

The repository root also holds a `plugin.json` in the open Agent Plugins format.

### Gemini CLI

```sh
gemini extensions install https://github.com/quiroads/clinic-marketing-skills
```

### Hermes Agent

```sh
hermes plugins install quiroads/clinic-marketing-skills --no-enable
hermes plugins enable quiroads-clinic-marketing
```

## Skills

| Skill | What it does |
| --- | --- |
| [`clinic-meta-ads-access-audit`](skills/clinic-meta-ads-access-audit/SKILL.md) | Walks you through Meta Business Suite screen by screen to find out who owns and controls the clinic's ad account, Page, Instagram, dataset, WhatsApp account and domain, ranks the risks with the official fix for each, separates what the clinic can recover from what has to be rebuilt, and drafts a message asking the previous agency to release the assets. |
| [`clinic-ad-compliance-review`](skills/clinic-ad-compliance-review/SKILL.md) | Checks an ad, the description of its image or video, a landing page, an organic post or a WhatsApp sales message against the Meta and Google health ad policies and the health advertising rules of Spain, the United Kingdom, the United States and Australia, quotes each problem phrase with its rule and source, and rewrites the piece. |
| [`clinic-lead-follow-up`](skills/clinic-lead-follow-up/SKILL.md) | Designs a speed-to-lead system that works with any tool, from a spreadsheet to a CRM: a first WhatsApp message within minutes, call and voicemail scripts, a short follow-up sequence, booking confirmations and reminders, consent texts, SMS where WhatsApp doesn't reach, and a sheet to measure response time, bookings, attendance and lead-to-patient rate. |
| [`clinic-patient-retention`](skills/clinic-patient-retention/SKILL.md) | Scripts the first visit and the report of findings for the practitioner and the assistant, presents the care plan and the payment options, answers the usual objections, and sets up the messages for patients who don't start, missed visits, plan renewals, reactivation and reviews. |

Once a skill is installed, ask your agent in your own words, for example «who controls my clinic's Meta ad account?» or «revisa este anuncio de mi clínica antes de publicarlo».

## Privacy and support

The skills are plain instructions in `SKILL.md` files. They run inside your own agent, bundle no scripts or MCP servers, ask for no credentials, connect to no ad platform or clinic software, read no web pages and send nothing to QuiroAds. They work only from what you paste or describe to your agent: ad copy, what you see on a screen, counts and stages. A skill never needs patient names or records, so don't paste any into the chat. They are not legal advice: they report the problems they find with the rules as checked on a stated date, and the final decision on an ad belongs to the platform and the regulator. Maintainers build and test this repository with private tooling; the plugin itself is only the files you see here.

- Privacy policy: https://quiroads.com/privacy-policy
- Terms: https://quiroads.com/terms
- Support: ajustame@quiroads.com, or https://quiroads.com/contact

## About QuiroAds

The skills are published by QuiroAds: https://quiroads.com

## License

[MIT](LICENSE)
