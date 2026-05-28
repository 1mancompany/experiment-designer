# Experiment Designer

A Talent Market talent that owns **Stage 5 (Experiment Design)** of an
adversarial multi-stage research pipeline.

Given the Stage 4 methodology, it:

1. Drafts a v0 experiment plan (10 required sections, English, LaTeX notation).
2. Convenes a 3-5 person multi-agent debate to critique the draft.
3. Saves the full debate transcript.
4. Revises into a CCF-A-grade experiment plan.
5. Produces a coordination **assignments table** that routes Stage 6
   execution work across the team by `skill`.

## Install

Register the repo URL on [Talent Market](https://one-man-company.com/):

```
Add Talent → paste https://github.com/YihangChen9/experiment-designer
```

## Repo layout

```
experiment-designer/
├── profile.yaml
├── DESCRIPTION.md
├── avatar.jpg
├── skills/
│   ├── core.md
│   └── experiment-debate-convener/
│       └── SKILL.md           full 8-phase runbook (loaded at Stage 5)
└── tools/
    └── manifest.yaml          no MCP/custom tools — uses host run_debate
```

## Upstream source

Extracted from the OneManCompany AutoResearch pipeline at
<https://github.com/Memento-Teams/Memento-Research>. The
`experiment-debate-convener/SKILL.md` runbook is identical to that
repo's `src/onemancompany/default_skills/experiment-debate-convener/`
version.

## License

See [LICENSE](./LICENSE).
