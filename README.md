# Introduction

The prompts I use for common tasks.

# Prompts

## General 

```md
Always use British spelling. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".
```

## Daily Status

```md
Goal
Create a daily status update for a specific date based on my Microsoft 365 activity, using a controlled, review‑driven flow.

Operating rules
- Work step by step
- Stop completely at any step that explicitly says “STOP”
- Do not assume or invent information
- If required information is missing, ask for it and STOP

Step 1 - Audience selection
Ask me which audience this update is for and present these options only:
1. Engagement team (Engagement Partner, Engagement Manager, PMO, delivery team)
2. Whole project team (Project Manager, Engineering Manager)

STOP after asking.

Step 2 - Date confirmation
Ask me for the date. Repeat the date back in ISO format (YYYY‑MM‑DD).

STOP to confirm the date.

Step 3 - Microsoft 365 activity review
Explain what Microsoft 365 activity you can currently see for the confirmed date.

If no activity is visible or access is incomplete, clearly state that and ask me to provide the activity manually.

If activity is visible, pull the information to extract explicit source links based on these rules:
- Pull fully: Emails, Teams messages (inspect the underlying thread or message directly)
- Pull: Meetings (calendar event with its link; if no calendar event link is available, use the Teams meeting link; otherwise no link)
- Pull only if missing link: Files

Present it as a concise list:
- One line per item with its explicit source link
- No interpretation, grouping, or outcomes
- Only work‑related activity

STOP and ask me to confirm, correct, add, or remove items.

Step 4 - Project identification
Using only the confirmed activity:
- Propose a list of projects
- Order them by business‑critical priority

Ask me to confirm, rename, reorder, add, or remove projects.

STOP after presenting the project list.

Step 5 - Generate the status update
After project confirmation, generate the daily status update using this exact structure:

YYYY‑MM‑DD

Project

What I did
- (key outcomes and progress)

Blockers
- (risks, dependencies, or delays)

What I will do
- (planned actions)

Constraints:
- British spelling
- Executive, neutral tone
- non‑code, Microsoft Word‑friendly
- Include source links only from the confirmed activity in Step 3
- For each bullet, append the link(s) from the activity items that directly support the bullet at the end where they exist, otherwise leave the bullet without a link
- Use all available links from the confirmed activity in Step 3

Do not add commentary, explanations, or extra sections.

End of prompt.
```

## Email General

```md
Always use British spelling. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Draft an email for me with an email subject. I want to start it by Hi and then the recipient name(s). I am using my email signature so do not end the email. Use neutral or positive tones. Be precise, concise, certain and professional.
```

## Email Draft Review

```md
Always use British spelling. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Review my email draft for me. I want to start it by Hi and then the recipient name(s). I am using my email signature so do not end the email. Use neutral or positive tones. Be precise, concise, certain and professional.
```

## Email Reply

```md
Always use British spelling. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

I'm replying to an email. I want to start it by Hi and then the recipient name(s). I am using my email signature so do not end the email. Use neutral or positive tones. Be precise, concise, certain and professional.
```

## Post‑Leave Summary

```md
My leave was from <Start Date> inclusive to <End Date> inclusive.
I’ve just returned from leave and want a concise but comprehensive summary of what I missed during my absence.

Please review my emails, Teams chats, meetings, shared documents, and any relevant updates from my close collaborators during the period I was away.

Summarise the information using the following structure:
1. Key decisions made or confirmed
2. Important discussions or themes
3. Actions taken or completed while I was away
4. Open actions, risks, or items requiring my attention
5. Upcoming deadlines, meetings, or milestones

Prioritise items that are high-impact, time-sensitive, or directly related to my role.  
Keep the summary clear, skimmable, and focused on what I need to act on first.
```

## Ticket Draft

```md
Always use British spelling. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Draft a ticket including the acceptance criteria for me. The ticket description needs to be in the Why What How style. Use a numbered list in the How section. The ticket is for the **<developers|QA engineers|other roles>** to:
```

## Proposed Solution 

```md
Always use British spelling. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

Review my draft on a proposed solution. I am looking to get approval for this solution from the business team. Mind that there could be typo in the provided requirement. My proposed solution should contain more accurate information. Generate any revised text.

**The requirement** is that:

**My proposed solution** is that:
```

## Documentation

```md
Always use British spelling. Do not use semicolons. Do not use the em dash (—). Do not use "thereby".

I'm writing a documentation. I'm going to feed you the context, and then start composing it.

**Objective**:

**Target audience**:

**Other context**:
```

## Self Review

```md
Goal: Write a clear, balanced self‑review for a formal performance review, based strictly on my own reflections, observed behaviours, and demonstrated impact.

Context: This is a self‑assessment for a formal performance review. The review should be professional, reflective, and evidence‑based, highlighting strengths, impact, and areas for growth. It should be honest, balanced, and aligned with organisational expectations.

Language and Style Requirements:
- Use British English spelling and conventions throughout (e.g. behaviours, organisation, prioritisation).
- Use a clear, professional UK business writing style suitable for a corporate performance review.

Interaction Instructions (Critical):
You must follow the steps below exactly. Do not skip steps or combine questions.

---

Step 0 - Confirm the Template

First, present a brief summary of the template you will use, explaining that you will:
- Ask me reflective questions one at a time
- Gather my inputs on strengths, impact, development areas, and QRM & TE
- Draft the final self‑review only after all inputs are provided

Then ask me:
"Do you confirm this approach and template for your self‑review?"

Do not proceed until I explicitly confirm.

---

Step 1 - Strengths and Impact

After confirmation, ask:
"What key strengths and behaviours have you demonstrated during this review period, and what impact have they had on your team, stakeholders, or outcomes?"

Wait for my response before continuing.

---

Step 2 - Opportunities to Increase Impact

After I respond to Step 1, ask:
"Based on your reflection, what could you do to have a greater impact going forward? Please include areas for development, skills to strengthen, or changes in ways of working."

Wait for my response before continuing.

---

Step 3 - QRM & TE Reflection

After I respond to Step 2, ask:
"How have you demonstrated Quality, Risk Management, and Technical Excellence (QRM & TE) in your work? Please include examples such as ownership, attention to detail, risk awareness, adherence to standards, or improvements you have driven."

Wait for my response before continuing.

---

Final Output Instructions

After I have answered all questions, write a concise, well‑structured self‑review addressing:
1. What particular strengths do I demonstrate?
2. What could I do to have a greater impact?
3. Comments on QRM & TE

Formatting and Tone Expectations:
- Use clear headings or bullet points under each question.
- Maintain a professional, reflective, and objective tone.
- Be specific and evidence‑based.
- Avoid exaggeration, vague claims, or confidential project details.
```

## Peer Performance Feedback

```md
Goal: Write constructive, balanced performance feedback for a peer, based strictly on my direct observations.

Context: This is peer feedback for a formal performance review. The feedback should be professional, fair, and supportive, highlighting strengths and offering thoughtful suggestions for improvement. All feedback must be grounded in observed behaviours and impact, not assumptions.

Language and Style Requirements:
- Use British English spelling and conventions throughout (e.g. behaviours, organisation, prioritisation).
- Use a clear, professional UK business writing style suitable for a corporate performance review.

Interaction Instructions (Critical):
You must follow the steps below exactly. Do not skip steps or combine questions.

---

Step 0 - Confirm the Template

First, present a brief summary of the template you will use, explaining that you will:
- Ask me questions one at a time
- Collect my observations on strengths, opportunities for greater impact, and QRM & TE
- Draft the final peer feedback only after all inputs are provided

Then ask me:
"Do you confirm this approach and template?"

Do not proceed until I explicitly confirm.

---

Step 1 - Strengths and Positive Impact

After confirmation, ask:
"What specific strengths and behaviours have you observed in this individual, and what positive impact have these had on the team or outcomes?"

Wait for my response before continuing.

---

Step 2 - Opportunities to Increase Impact

After I respond to Step 1, ask:
"Based on your observations, what could this individual do to have a greater impact? Please include any behaviours to develop, skills to strengthen, or ways of working to improve."

Wait for my response before continuing.

---

Step 3 - QRM & TE Observations

After I respond to Step 2, ask:
"What are your observations regarding this individual’s approach to Quality, Risk Management, and Technical Excellence (QRM & TE)? Please include examples such as attention to detail, ownership, adherence to standards, or contributions to improving quality or technical outcomes."

Wait for my response before continuing.

---

Final Output Instructions

After I have answered all questions, write concise, well‑structured peer feedback addressing:
1. What particular strengths does this individual display?
2. What could this individual do to have a greater impact?
3. Comments on QRM & TE

Formatting and Tone Expectations:
- Use clear headings or bullet points under each question.
- Maintain a respectful, objective, peer‑to‑peer tone.
- Be specific and evidence‑based.
- Avoid vague praise, speculation, or confidential project details.
```
