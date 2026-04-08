# Introduction

The prompts I use for everyday tasks.

# Prompts

## General 

Always use British spellings. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

## Daily Status

```md
Goal: Create the daily status update for a given day using my Microsoft 365 activity.

Prompt:

Before generating the update, confirm the audience:
1. the engagement team including Engagement Partner, Engagement Manager, PMO, delivery team
2. the whole project team including the Project Manager and Engineering Manager

Ask for the date if not provided. Confirm the date back to me in ISO format (YYYY‑MM‑DD).

Identify projects using a hybrid approach:
1. Infer project names from my Microsoft 365 activity (emails, meetings, documents, team channels).
2. Allow me to add, rename, or remove project names.
3. Generate the update for each project, ordered by business‑critical priority.

After I confirm, produce the update using British spelling, an Executive + Neutral tone, and this exact structure:

# YYYY-MM-DD
## Project A
### What I did
- ...
### Blockers
- ...
### What I will do
- ...
## Project B
### What I did
- ...
### Blockers
- ...
### What I will do
- ...

- "What I did" should summarise key outcomes and progress.
- "Blockers" should identify risks, dependencies, or delays.
- "What I will do" should outline my top planned actions for the next working day.
```

## Email General

Always use British spellings. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Generate an email for me with an email subject. I want to start it by Hi and then the recipient name(s). I am using my email signature so do not end the email. Use neutral or positive tones. Be precise, concise, certain and professional.

## Email Draft Review

Always use British spellings. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Review my email draft for me. I want to start it by Hi and then the recipient name(s). I am using my email signature so do not end the email. Use neutral or positive tones. Be precise, concise, certain and professional.

## Email Reply

Always use British spellings. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

I'm replying to an email. I want to start it by Hi and then the recipient name(s). I am using my email signature so do not end the email. Use neutral or positive tones. Be precise, concise, certain and professional.

## JIRA Ticket

Always use British spellings. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Draft a JIRA ticket including the acceptance criteria for me. The ticket description needs to be in the Why What How style. Use a numbered list in the How section. The ticket is for the **<developers|QA engineers|other roles>** to:

## Proposed Solution 

Always use British spellings. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Review my draft on a proposed solution for me. I am looking to get approval for this solution from the business team. Mind that there could be typo in the provided requirement. My proposed solution should contain more accurate information. Generate any revised text.

**The requirement** is that:

**My proposed solution** is that:

## Documentation

Always use British spellings. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

I'm writing a documentation. I'm going to feed you the context, and then start composing it.

**Objective**:

**Target audience**:

**Other context**:
