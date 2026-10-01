# Getting started

This is the flow the skill was actually built and validated against: one real profile, rewritten end-to-end against three real job postings. Follow it in order and you'll get a much better result than jumping straight to "rewrite my resume."

## Step 0 — Install the skill

Copy `.claude/skills/professional-profile-optimization/` into your own project's `.claude/skills/` folder, or clone this whole repo and work from it directly.

Then restart Claude Code, or start a new session, in that project. Project skills are discovered once per session, so a skill added mid-session won't show up until you restart.

## Step 1 — Give Claude your source material

Paste or upload:

- Your current LinkedIn profile. A PDF export works well (LinkedIn → More → Save to PDF).
- Your current CV/resume, if it differs from LinkedIn.
- Any target job posting(s) you already have in mind.

## Step 2 — Answer this before asking for a rewrite

The skill will ask versions of these on its own, but answering up front saves a lot of back-and-forth. Keep it short and in your own words; dictating by voice works fine.

**Identity and scope**
1. What's your current role, and how long have you been doing it?
2. What industry or domain is it in? Who are your users, and who pays?
3. Is it B2B, B2C, B2B2C, internal tooling, or something else?
4. What's the team structure around you (squads, departments, who you coordinate with)?

**Evidence and scale**
5. How many people or teams do you lead or coordinate with?
6. How many customers, users, or clients does what you work on reach?
7. Any measurable before/after you're proud of (adoption, retention, revenue, time saved, ratings)? If you don't have a hard number, say so; don't guess at one.
8. Any certifications, tools, or technical practices you use daily that aren't obvious from your title?

**Career narrative**
9. What did you do before this role? Is there a thread connecting it to where you are now?
10. Any past title that doesn't translate well to English, or to the market you're targeting?

**Target**
11. What market or language are you targeting?
12. Do you have specific job posting(s) in mind? Paste them.

## Step 3 — Let it diagnose before it rewrites

Ask for a review, not a rewrite: "test this skill on my profile and tell me what's weak before changing anything." A good run comes back with a gap analysis first, not a finished draft.

## Step 4 — Review flagged gaps honestly

If a target job needs something you don't have (a certification, a language level, a tool), the skill is designed to say so instead of inventing it. Decide for yourself how to handle each gap; don't ask it to paper over one.

## Step 5 — Ask for the output you actually need

Once the diagnosis holds up, ask for what you need: a rewritten LinkedIn section, a tailored resume, a cover letter combined into one PDF, answers to an application questionnaire. Name the job and the format.

## Step 6 — Keep your own knowledge file

As you give more detail across sessions (project stories, metrics, context), ask Claude to save that material in a separate file in your own project, outside this skill folder. That keeps the skill itself generic and reusable, and keeps your personal data out of anything you later share or fork from this repo.
