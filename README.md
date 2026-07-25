# Finance Polandball Skills

Two Codex skills for creating clear, humorous money-market explainers in a
classic Polandball comic style.

## Included Skills

- `finance-polandball-style`: visual rules, dialogue, typography, composition,
  financial-accuracy checks, and classic comic references.
- `finance-polandball-members`: canonical Finance Polandball identities and
  participation rules for the Fed, banks, dealers, MMFs, GSEs, funds, and
  related actors.

Install both skills together. They reference each other.

## Install from GitHub

Ask Codex to install both paths from this repository:

```text
Install these skills from CircleCircleFace/US-money-market-polandball-skills:
.codex/skills/finance-polandball-style
.codex/skills/finance-polandball-members
```

The equivalent skill-installer arguments are:

```text
--repo CircleCircleFace/US-money-market-polandball-skills \
--path .codex/skills/finance-polandball-style \
       .codex/skills/finance-polandball-members
```

Restart or begin a new Codex turn after installation so the skills are
discovered.

For manual installation, copy both skill folders into:

```text
$CODEX_HOME/skills/
```

## Example Prompts

```text
Use finance-polandball-members and finance-polandball-style to draw a
three-panel comic explaining why SOFR usually trades between ON RRP and SRF.
```

```text
Review this Finance Polandball comic for character identity, financial
accuracy, forbidden limbs, dialogue style, and typography consistency.
```

## Repository Layout

```text
.codex/skills/
|-- finance-polandball-style/
|   |-- SKILL.md
|   |-- agents/openai.yaml
|   `-- assets/
`-- finance-polandball-members/
    |-- SKILL.md
    |-- agents/openai.yaml
    |-- references/roster.md
    `-- assets/
```

## Licensing

Original skill text, metadata, roster material, and project-created assets are
available under the
[Finance Polandball Skills Noncommercial License 1.1](LICENSE). It permits only
personal nonprofit use and noncommercial educational, teaching, study, and
research use. All commercial use requires separate prior written permission.

This is a source-available license, not an OSI-approved open-source license.

Several classic comic references are third-party open-content works with their
own licenses. See:

- [Style asset licenses](.codex/skills/finance-polandball-style/assets/LICENSES.md)
- [Member asset licenses](.codex/skills/finance-polandball-members/assets/LICENSES.md)

Third-party licenses override the project license for the files they cover.

## Notices

- Polandball is a community-created meme and art convention. This repository is
  not affiliated with or endorsed by any Polandball community.
- This repository is not affiliated with the Federal Reserve, the Federal
  Reserve Bank of New York, OpenAI, or any depicted financial institution.
- Comics generated with these skills are educational illustrations, not legal,
  investment, accounting, or regulatory advice.
