# Professional Profile Optimization — a Claude Code skill

A [Claude Code](https://claude.com/claude-code) skill for creating, reviewing, translating, and optimizing your professional profile: LinkedIn, resume/CV, cover letters, and alignment with a specific job posting or ATS.

It does not just "make the text sound nicer." It diagnoses your actual positioning first, insists on real evidence instead of invented metrics, and only rewrites once the diagnosis holds up.

## Why this exists

This skill was built, then field-tested end to end on one real profile against three real job postings: diagnosis and gap analysis first, then tailored resumes with a combined cover letter, then answers to an actual application questionnaire. The process surfaced and fixed real problems (zero metrics in the original resume, a certification buried under generic ones, a mixed-language profile, an unexplained job-title overlap) before it ever touched the final documents. The original draft this skill grew from is in [`ORIGINAL-DRAFT.md`](./ORIGINAL-DRAFT.md).

## Install

1. Copy `.claude/skills/professional-profile-optimization/` into your own project's `.claude/skills/` folder, or clone this repo and open it directly in Claude Code.
2. Restart Claude Code, or start a new session, so the skill is discovered. Project skills load once per session.
3. Read [GETTING-STARTED.md](./GETTING-STARTED.md) before your first run. It has the intake questions that save you the most back-and-forth.

## What it will never do

- Invent metrics, certifications, tools, or seniority you haven't confirmed.
- Translate a job title literally when that would misrepresent your actual scope.
- Treat "not mentioned" as "doesn't have."
- Hide a gap against a job requirement to make a resume look like a better fit than it is.

The full list lives in [`revisao-e-consistencia.md`](./.claude/skills/professional-profile-optimization/references/revisao-e-consistencia.md).

## How it's organized

```
.claude/skills/professional-profile-optimization/
├── SKILL.md                                  entry point: principles, golden rule, 12-step workflow
└── references/
    ├── diagnostico-e-descoberta.md           initial diagnosis, metrics, gap analysis, discovery questions
    ├── narrativa-de-carreira.md               career-thread framing, incl. a Customer Success → Product case
    ├── linkedin-e-cv.md                       headline, About, experience bullets, seniority signals
    ├── keywords-produto-ats.md                Product Management keyword taxonomy, Skills, ATS
    ├── localizacao-internacional.md           translation, job titles, professional English
    ├── cover-letter.md                        cover letter structure
    ├── linguagem-natural.md                   how to avoid generic/AI-sounding text
    └── revisao-e-consistencia.md              review rubric, job-targeting process, consistency, what not to do
```

`SKILL.md` stays short on purpose and points to the reference file each step of the workflow actually needs, so a session only loads what's relevant instead of the whole thing at once.

## Content is in Portuguese

The skill's instructions are written in Portuguese (the author's working language), but it produces output in whatever language the person using it needs, including fully localized English profiles. Translate the skill files yourself if you'd rather work in another language; the structure will carry over directly.

## Forking this for your own profile

This skill is intentionally generic. It has no information about any specific person baked into it. If you adapt it for your own use:

- Keep your CV, LinkedIn export, metrics, and application history in a separate file or folder, outside this skill's directory.
- Follow [GETTING-STARTED.md](./GETTING-STARTED.md), which tells you how to ask Claude to do the same.

## License

MIT. See [LICENSE](./LICENSE).
