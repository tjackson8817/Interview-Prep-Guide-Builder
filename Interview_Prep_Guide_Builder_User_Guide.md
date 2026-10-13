**SALE FISH**

MARKETING AND CONSULTING

# Interview Prep Guide Builder

*User Guide*

**Live Tool:** [https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html](https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html)

Created By: Tom Jackson
August 12, 2026 (Objection Reframing section and the worry-areas field updated August 17, 2026; Candidate SWOT Analysis and the optional STAR Stories field added September 1, 2026; 30-45 second "Tell Me About Yourself" section added to all three modes October 13, 2026)

This tool is a single web page (interview_prep_guide_builder.html) that turns your resume, the job description, and (optionally) who you're meeting with into a real, grounded interview prep guide. Like the other tools in this family, it runs entirely in your browser: no install, no account, nothing sent anywhere until you copy the prompt and paste it into a Claude chat yourself.

## Claude Settings You'll Need Before You Start

| Setting | Why you need it / Where to find it |
|---|---|
| Web search | Needed for company research, interviewer research, and (in Recruiter Screen mode) real salary market data. |
| Code execution and file creation | Always needed — every guide now comes back as a downloadable Word document. |

## 1. How This Fits With the Other Tools

Not sure what to target yet? Career Path Discovery Prompt Builder is the step before all of this. Once you know your direction: the Target Company Prompt Builder researches and ranks companies. The Job Posting Finder checks who's actively hiring. Resume & Cover Letter Tailoring fits your documents to a specific posting. Outreach Message Builder drafts your outreach. This tool picks up once you've actually landed an interview — the stage none of the others cover. Afterward, the specific things you actually discuss become the Context Notes for a genuinely grounded thank-you message back in the Outreach Message Builder.

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
| Things you're worried a hiring manager will hold against you (optional) | A gap, a career pivot, several short tenures, being overqualified, a tool named in the JD you're light on. These get built into a dedicated Objection Reframing section, not just noted in passing — naming the actual thing gets you real, specific talking points instead of generic prep. |
| STAR Stories — up to 3 (optional, Hiring Manager and General/Other modes only) | Write out your own Situation / Task / Action / Result for up to three stories if you already know which ones you want to use. The guide uses these exactly as written instead of just pointing you to a resume bullet — see Section 6 (Hiring Manager) or Section 7 (General/Other) below. Leave all three blank and the guide falls back to its usual behavior: identifying the strongest resume bullets and prompting you to structure them yourself. Not shown in Recruiter Screen mode, since that mode doesn't use behavioral/STAR-style questions. |

## 4. "Tell Me About Yourself" — Section 1 in Every Mode

Nearly every interview opens with "Tell me about yourself," so every guide, in all three modes, now leads with a short, focused answer to it, placed right after the Quick Reference. It walks the interviewer through your resume in 30-45 seconds (roughly 75-110 words), leaning into how your background lines up with this specific job description. It's built in three timed parts:

| Part | Time | What it covers |
|---|---|---|
| 1 · Early Years | ~10 sec | Where you're from, your education, and your early-career foundation. |
| 2 · Most Recent Role | ~10 sec | What you did in your last job, framed around what lines up with this job description. |
| 3 · What You'll Bring | ~10-15 sec (the longest part) | The 2-3 key things from your resume that most directly match the job description, and how you'd apply them in this role. |

You also get the three parts combined as one continuous answer with a word count and speaking time, plus a short delivery note: stay under 45 seconds, don't walk through every job in order, and stop after Part 3 so the interviewer can steer the next question. The combined answer is also repeated at the top of the Quick Reference.

The answer is built only from facts in your resume (and your own STAR Stories, if you wrote them). Resumes usually don't say where you're from, and sometimes leave out education, so anything Part 1 needs that isn't there comes back as a [bracketed placeholder], like [hometown] or [degree, school], for you to fill in. It's never invented. The emphasis shifts slightly by mode: crisp and qualifications-focused for a recruiter screen, pointed at the strengths you want probed for a hiring manager, and kept consistent across interviewers for panels and multi-round processes.

## 5. Recruiter Screen Mode

### Extra fields

- **Location** — compensation varies heavily by location, so this grounds the salary research described below.
- **Why you're not currently working / leaving your current role** (optional) — your own real reason, in your own words. Left blank, the guide gives you general guidance on structuring this kind of answer instead of inventing a reason for you.
- **Your target salary range, if you have one** (optional) — the guide researches real market data either way; this just gets checked against it rather than replacing it.

### What the guide builds

1. **"Tell Me About Yourself" (30-45 Second Answer)** — see the box below; same structure in every mode.
2. **Qualifications T-Chart** — a two-column table, JD requirement on the left, your matching resume evidence on the right, one row per major requirement. Meant to be genuinely scannable in the 30 seconds before the call.
3. **The Gap/Leaving Answer** — if you gave a real reason, drafted as a brief, honest, forward-looking 2-3 sentences with no badmouthing a previous employer. If you didn't, general guidance on structure only — the guide never invents a reason on your behalf.
4. **Objection Reframing** — if you named specific worries, a short, honest, spoken-ready way to address each one if it comes up: 2-3 sentences per concern, framed as neutral or as a genuine advantage wherever your actual background supports that — never spin, never a fabricated accomplishment used to explain a concern away. If you left the field blank, general guidance on reframing common concerns (industry breadth, short tenures, a pivot, overqualification) instead.
5. **The Salary Question** — real market compensation data researched and sourced (levels.fyi, Glassdoor, Payscale, BLS data, comparable disclosed postings), never a guessed number. If you gave your own target, it's checked against the research and flagged if notably out of step, not just validated. The delivery is coached as a stated range with flexibility — explicitly framed as not a negotiation yet.
6. **Standard Logistics Questions to Expect** — notice period, work authorization, remote/travel flexibility, other interviews in process. The guide prompts you to supply your own actual answers here rather than inventing personal facts.
7. **Keep It Tight** — a coaching note that recruiter screens reward concise answers over deep technical detail.
8. **Questions to Ask the Recruiter** — process/timeline, the top priority for this hire in the first 90 days, comp band confirmation. Deliberately skips deep team/strategy questions, which belong in a later round.

## 6. Hiring Manager Interview Mode

### Extra fields

- **Call length (minutes)** — defaults to 60, edit to match your actual call.
- **Platform** — Microsoft Teams, Zoom, Google Meet, Phone, or Other. Feeds directly into the logistics checklist.
- **Interviewers** (optional) — bulk-paste Name and Role pairs (one per line, e.g. from a calendar invite), or add manually. Each gets a role category (Recruiter/HR, Hiring Manager, Peer/team member, Skip-level/executive, Cross-functional partner) that shapes what angle the interviewer-research section takes.

### What the guide builds

1. **"Tell Me About Yourself" (30-45 Second Answer)** — the three-part answer described in Section 4.
2. **Company & Role Snapshot** — real, recent research (roughly the last 6 months): what the company does, recent news, funding, leadership changes, and how this role fits into what's happening there now. If nothing notable turns up, the guide says so rather than padding with generic filler.
3. **Resume-to-JD Gap Map** — where you map cleanly (named specifically as your strongest talking points) and where there's a real gap, framed constructively as what the interviewer may probe and why — never softened away, never manufactured where it doesn't exist.
4. **Objection Reframing** — if you named specific worries, a short, honest, spoken-ready way to address each one if it comes up: 2-3 sentences per concern, framed as neutral or as a genuine advantage wherever your actual background supports that — never spin, never a fabricated accomplishment used to explain a concern away. If you left the field blank, general guidance on reframing common concerns (industry breadth, short tenures, a pivot, overqualification) instead.
5. **Interviewer Research** — for each named interviewer, real search for their public professional background. If little or nothing turns up for someone, the guide says so plainly rather than inventing a personality or interests to seem more personalized, and falls back to role-based prep instead.
6. **Candidate SWOT Analysis** — a Strengths/Weaknesses/Opportunities/Threats breakdown of your candidacy for this specific role, grounded in the Company & Role Snapshot, the Resume-to-JD Gap Map, and the Interviewer Research above (not a generic SWOT template). Strengths and Weaknesses draw directly from the gap map; Opportunities and Threats draw from the actual company situation and role/interviewer context. Directly under the Weaknesses list, the guide gives 1-2 short talking points for how to address each weakness if it comes up — same guardrail as Objection Reframing: grounded in something real from your resume, never a fabricated accomplishment used to explain a gap away.
7. **Video Call Logistics Checklist** — tied to your actual platform: test audio/video ahead of time, check lighting and background, close notifications, have a backup dial-in if one exists, look at the camera not the screen.
8. **Time-Boxing** — a realistic cadence scaled to your actual call length, plus a coaching note to keep individual answers to 90 seconds-2 minutes unless explicitly asked to go deeper, since one long answer can eat a meaningful chunk of a short call.
9. **Your Top 3-4 Stories** — not an exhaustive list. If you wrote your own STAR Stories in the field described in Section 3, the guide uses those exactly as written (tightened for spoken delivery if needed) rather than pointing you to a resume bullet, and fills in any remaining slot up to 3-4 by pointing you to the strongest resume experiences the same way it always has. If you left the STAR Stories field blank, same rule as always: the guide points you to the story, it never writes the story or invents outcomes on your behalf.
10. **Likely Questions** — behavioral, role/technical, culture/values, and gap-probe, sized realistically for the time you actually have rather than an exhaustive list you won't get through.
11. **Questions to Ask the Hiring Manager** — team structure and day-to-day, how success is measured in the first 90 days, current priorities, management style. Tailored using the interviewer research where applicable.
12. **Logistics Checklist** — video-call-appropriate: notes visible off-camera but out of the way, your own questions written down, the platform link confirmed ahead of time.

## 7. General / Other Mode

The fallback for technical rounds, panels, and final rounds — the fuller original structure:

- **Interview stage** — Technical/skills round, Panel, Onsite/final round, or Not sure.
- **Interviewers** (optional) — same bulk-paste/manual mechanism as Hiring Manager mode, but tracked as its own separate list.

Builds: "Tell Me About Yourself" (30-45 Second Answer, see Section 4), Company & Role Snapshot, Resume-to-JD Gap Map, Objection Reframing (grounded in your named worries, or general guidance if you left that field blank), Interviewer Research (or a plain statement that it's skipped if no names given), a Candidate SWOT Analysis with weakness-mitigation talking points (same shape and guardrails as in Hiring Manager mode, see Section 6), Likely Questions across the same four categories, Story Scaffolding via STAR (using your own STAR Stories from Section 3 as written if you filled them in, otherwise pointing you to resume bullets as always), Questions to Ask Them, and a Logistics Checklist.

## 8. The Non-Negotiable Guardrails

These apply in Hiring Manager and General/Other modes (Recruiter Screen mode has its own parallel guardrails, in Section 5), except the "Tell Me About Yourself" rule, which applies in all three modes:

- **Never a fabricated story.** If you filled in the STAR Stories field, the guide uses those stories exactly as written and never adds, embellishes, or invents detail beyond what you gave it. Where a slot is unfilled, the guide points you to the specific resume bullet that's your strongest match and prompts STAR structure — it never writes the actual story, invents what happened, or fabricates outcomes or metrics. Claude doesn't know what actually happened in your work beyond what your resume states (or what you wrote yourself in a STAR Story), and inventing specifics risks putting words in your mouth you'd have to walk back live.
- **"Tell Me About Yourself" stays factual.** The 30-45 second answer uses only what's in your resume (or your own STAR Stories). A fact it needs that isn't there, like your hometown or school, comes back as a [bracketed placeholder] for you to fill in, never an invented detail.
- **Interviewer research stays evidence-based.** A thin or empty search result for a named person is a valid, expected outcome — the guide reports it as such rather than filling the gap with a plausible-sounding personality profile.
- **SWOT weaknesses stay honest.** A real weakness in the Candidate SWOT Analysis is never softened into a non-weakness, and its mitigation talking point is never a fabricated accomplishment used to explain the gap away — same standard as Objection Reframing. The SWOT is only built in Hiring Manager and General/Other modes, since Recruiter Screen mode stays deliberately brief and checklist-oriented.

## 9. Output

Every guide always comes back as a **downloadable Word document (.docx)** — there's no chat-table option anymore. It's a reference guide you'll want on hand right before walking in, with a one-page Quick Reference summary at the very top (opening with your 30-45 second "Tell Me About Yourself" answer) and full detail below it. This requires the **Code execution and file creation** setting (Settings → Capabilities) to be on; without it, Claude will fall back to a chat response.

## 10. Typical Workflow, Start to Finish

1. Pick your mode.
2. Fill in company, role, job description, and resume.
3. Fill in whatever's specific to your mode.
4. Copy the generated prompt, paste it into a new Claude chat (attach your resume/JD files here if you didn't paste the text).
5. Review the guide — pay particular attention to anything flagged as needing your own input (a gap reason you didn't supply, an interviewer with no research found, a [bracketed placeholder] in your "Tell Me About Yourself" answer). Then say that answer out loud with a timer: it should land between 30 and 45 seconds.
6. After the interview, carry the specific things you actually discussed into the Outreach Message Builder's Context Notes for a genuinely grounded thank-you message.

## 11. Quick Troubleshooting

| Problem | Fix |
|---|---|
| Wrong fields are showing | Check the mode toggle at the top — switching modes swaps the entire field set. |
| Prompt panel shows placeholder text | Fill in at least the company, the role, or the job description. |
| My interviewers disappeared after switching modes | Expected — Hiring Manager and General/Other track separate interviewer lists. Re-add them in the mode you're actually using. |
| The salary section feels generic | Make sure Location is filled in — the market-data research is grounded by location, and comp varies significantly by market. |
| The guide didn't address my actual gap/leaving reason | Check that you actually filled in that field — left blank, the guide intentionally gives general guidance rather than inventing your situation. |
| Interviewer research came back thin for someone | That's an expected, honest outcome, not a bug — the guide falls back to role-based prep rather than inventing detail about a real person. |
| The objection reframing feels generic | Name the specific thing you're actually worried about in the field, rather than leaving it blank — a named concern gets a grounded, specific reframe; a blank field only gets general guidance. |
| My STAR Stories fields aren't showing | Expected in Recruiter Screen mode — that mode doesn't use behavioral/STAR-style questions, so the field is hidden there. Switch to Hiring Manager or General/Other mode to see it. |
| The story section still points me to a resume bullet instead of using my story | Check that you actually filled in at least one field (Situation, Task, Action, or Result) for that story — a fully blank story block is treated the same as not providing one. |
| My "Tell Me About Yourself" answer has [hometown] or [degree, school] placeholders | Expected when your resume doesn't include those facts. Fill them in yourself, or add them to the resume text before generating the prompt. |
| My "Tell Me About Yourself" answer runs longer than 45 seconds | Trim Parts 1 and 2 first. Part 3 (how your background fits this job) is the part worth the extra seconds. |
| In ChatGPT, it asks clarifying questions instead of running the task | The prompt opens with an explicit "execute this directly" instruction — restate it more bluntly as a follow-up if needed. |
