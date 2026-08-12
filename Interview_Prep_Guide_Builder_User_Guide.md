**SALE FISH**

MARKETING AND CONSULTING

# Interview Prep Guide Builder

*User Guide*

**Live Tool:** [https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html](https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html)

Created By: Tom Jackson
August 12, 2026

This tool is a single web page (interview_prep_guide_builder.html) that turns your resume, the job description, and (optionally) who you're meeting with into a real, grounded interview prep guide. Like the other tools in this family, it runs entirely in your browser: no install, no account, nothing sent anywhere until you copy the prompt and paste it into a Claude chat yourself.

## Claude Settings You'll Need Before You Start

| Setting | Why you need it / Where to find it |
|---|---|
| Web search | Needed for company research, interviewer research, and (in Recruiter Screen mode) real salary market data. |
| Code execution and file creation | Only needed if you choose the downloadable Word document output format. |

## 1. How This Fits With the Other Tools

The Target Company Prompt Builder researches and ranks companies. The Job Posting Finder checks who's actively hiring. Resume & Cover Letter Tailoring fits your documents to a specific posting. Outreach Message Builder drafts your outreach. This tool picks up once you've actually landed an interview — the stage none of the others cover. Afterward, the specific things you actually discuss become the Context Notes for a genuinely grounded thank-you message back in the Outreach Message Builder.

## 2. The Mode Toggle

At the top of the page: **Prepping for: Recruiter Screen / Hiring Manager Interview / General / Other**. This switches the entire field set and the entire generated guide — not just a couple of options. The three modes exist because a recruiter screen and a hiring-manager round genuinely need different preparation, not just a different depth of the same thing:

- **Recruiter Screen** asks whether you clear the basic qualifications bar and can speak to logistics — brief, checklist-oriented.
- **Hiring Manager Interview** asks whether you're the right fit for the actual role and team — deeper, story-driven, and here specifically built around a real, time-boxed video call.
- **General / Other** is the fuller original structure, for anything that doesn't fit the first two — technical rounds, panels, final rounds.

Switching modes doesn't carry your interviewer list between Hiring Manager and General/Other — they're tracked as genuinely separate lists, since a name relevant to one context usually isn't relevant to the other.

## 3. Shared Fields (All Modes)

| Field | What to put in it |
|---|---|
| Company | The company name. |
| Role / job title | The specific role you're interviewing for. |
| Job description | Paste the full text, or skip it and attach the posting file directly when you paste the prompt into Claude. |
| Your resume | Paste the full text, or attach the file directly instead. |
| Areas you're less confident about (optional) | A gap, a pivot, a tool named in the JD you're light on — naming these directly gets you real prep for the question you're actually worried about. |

## 4. Recruiter Screen Mode

### Extra fields

- **Location** — compensation varies heavily by location, so this grounds the salary research described below.
- **Why you're not currently working / leaving your current role** (optional) — your own real reason, in your own words. Left blank, the guide gives you general guidance on structuring this kind of answer instead of inventing a reason for you.
- **Your target salary range, if you have one** (optional) — the guide researches real market data either way; this just gets checked against it rather than replacing it.

### What the guide builds

1. **Tight "Tell Me About Yourself" Script** — a 60-90 second narrative arc built only from facts actually in your resume. No invented motivations or personal narrative details — factual and professional, not an origin story.
2. **Qualifications T-Chart** — a two-column table, JD requirement on the left, your matching resume evidence on the right, one row per major requirement. Meant to be genuinely scannable in the 30 seconds before the call.
3. **The Gap/Leaving Answer** — if you gave a real reason, drafted as a brief, honest, forward-looking 2-3 sentences with no badmouthing a previous employer. If you didn't, general guidance on structure only — the guide never invents a reason on your behalf.
4. **The Salary Question** — real market compensation data researched and sourced (levels.fyi, Glassdoor, Payscale, BLS data, comparable disclosed postings), never a guessed number. If you gave your own target, it's checked against the research and flagged if notably out of step, not just validated. The delivery is coached as a stated range with flexibility — explicitly framed as not a negotiation yet.
5. **Standard Logistics Questions to Expect** — notice period, work authorization, remote/travel flexibility, other interviews in process. The guide prompts you to supply your own actual answers here rather than inventing personal facts.
6. **Keep It Tight** — a coaching note that recruiter screens reward concise answers over deep technical detail.
7. **Questions to Ask the Recruiter** — process/timeline, the top priority for this hire in the first 90 days, comp band confirmation. Deliberately skips deep team/strategy questions, which belong in a later round.

## 5. Hiring Manager Interview Mode

### Extra fields

- **Call length (minutes)** — defaults to 60, edit to match your actual call.
- **Platform** — Microsoft Teams, Zoom, Google Meet, Phone, or Other. Feeds directly into the logistics checklist.
- **Interviewers** (optional) — bulk-paste Name and Role pairs (one per line, e.g. from a calendar invite), or add manually. Each gets a role category (Recruiter/HR, Hiring Manager, Peer/team member, Skip-level/executive, Cross-functional partner) that shapes what angle the interviewer-research section takes.

### What the guide builds

1. **Company & Role Snapshot** — real, recent research (roughly the last 6 months): what the company does, recent news, funding, leadership changes, and how this role fits into what's happening there now. If nothing notable turns up, the guide says so rather than padding with generic filler.
2. **Resume-to-JD Gap Map** — where you map cleanly (named specifically as your strongest talking points) and where there's a real gap, framed constructively as what the interviewer may probe and why — never softened away, never manufactured where it doesn't exist.
3. **Interviewer Research** — for each named interviewer, real search for their public professional background. If little or nothing turns up for someone, the guide says so plainly rather than inventing a personality or interests to seem more personalized, and falls back to role-based prep instead.
4. **Video Call Logistics Checklist** — tied to your actual platform: test audio/video ahead of time, check lighting and background, close notifications, have a backup dial-in if one exists, look at the camera not the screen.
5. **Time-Boxing** — a realistic cadence scaled to your actual call length, plus a coaching note to keep individual answers to 90 seconds-2 minutes unless explicitly asked to go deeper, since one long answer can eat a meaningful chunk of a short call.
6. **Your Top 3-4 Stories** — not an exhaustive list. The 3-4 resume experiences most likely to be useful, each prompted for STAR structure. Same rule as always: the guide points you to the story, it never writes the story or invents outcomes on your behalf.
7. **Likely Questions** — behavioral, role/technical, culture/values, and gap-probe, sized realistically for the time you actually have rather than an exhaustive list you won't get through.
8. **Questions to Ask the Hiring Manager** — team structure and day-to-day, how success is measured in the first 90 days, current priorities, management style. Tailored using the interviewer research where applicable.
9. **Logistics Checklist** — video-call-appropriate: notes visible off-camera but out of the way, your own questions written down, the platform link confirmed ahead of time.

## 6. General / Other Mode

The fallback for technical rounds, panels, and final rounds — the fuller original structure:

- **Interview stage** — Technical/skills round, Panel, Onsite/final round, or Not sure.
- **Interviewers** (optional) — same bulk-paste/manual mechanism as Hiring Manager mode, but tracked as its own separate list.

Builds: Company & Role Snapshot, Resume-to-JD Gap Map, Interviewer Research (or a plain statement that it's skipped if no names given), Likely Questions across the same four categories, Story Scaffolding via STAR, Questions to Ask Them, and a Logistics Checklist.

## 7. The Two Non-Negotiable Guardrails

These apply in Hiring Manager and General/Other modes (Recruiter Screen mode has its own parallel guardrails, in Section 4):

- **Never a fabricated story.** The guide points you to the specific resume bullet that's your strongest match and prompts STAR structure — it never writes the actual story, invents what happened, or fabricates outcomes or metrics. Claude doesn't know what actually happened in your work beyond what your resume states, and inventing specifics risks putting words in your mouth you'd have to walk back live.
- **Interviewer research stays evidence-based.** A thin or empty search result for a named person is a valid, expected outcome — the guide reports it as such rather than filling the gap with a plausible-sounding personality profile.

## 8. Output Format

- **Downloadable Word document** (default) — a reference guide you'll want on hand right before walking in, with a one-page Quick Reference summary at the very top and full detail below it.
- **Table in chat** — the same content, presented directly in the response instead.

## 9. Typical Workflow, Start to Finish

1. Pick your mode.
2. Fill in company, role, job description, and resume.
3. Fill in whatever's specific to your mode.
4. Copy the generated prompt, paste it into a new Claude chat (attach your resume/JD files here if you didn't paste the text).
5. Review the guide — pay particular attention to anything flagged as needing your own input (a gap reason you didn't supply, an interviewer with no research found).
6. After the interview, carry the specific things you actually discussed into the Outreach Message Builder's Context Notes for a genuinely grounded thank-you message.

## 10. Quick Troubleshooting

| Problem | Fix |
|---|---|
| Wrong fields are showing | Check the mode toggle at the top — switching modes swaps the entire field set. |
| Prompt panel shows placeholder text | Fill in at least the company, the role, or the job description. |
| My interviewers disappeared after switching modes | Expected — Hiring Manager and General/Other track separate interviewer lists. Re-add them in the mode you're actually using. |
| The salary section feels generic | Make sure Location is filled in — the market-data research is grounded by location, and comp varies significantly by market. |
| The guide didn't address my actual gap/leaving reason | Check that you actually filled in that field — left blank, the guide intentionally gives general guidance rather than inventing your situation. |
| Interviewer research came back thin for someone | That's an expected, honest outcome, not a bug — the guide falls back to role-based prep rather than inventing detail about a real person. |
| In ChatGPT, it asks clarifying questions instead of running the task | The prompt opens with an explicit "execute this directly" instruction — restate it more bluntly as a follow-up if needed. |
