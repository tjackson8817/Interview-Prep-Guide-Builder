# Interview Prep Guide Builder

A single self-contained HTML tool that turns your resume, the job description, and (optionally) who you're meeting with into a real, grounded interview prep guide — not generic interview advice.

**[Open the live tool](https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html)**

No install, no account, nothing sent anywhere — it's a static form that assembles text entirely in your browser.

## Fourth tool in this family

Alongside:
- **[Target-Company-Prompt-Builder](https://tjackson8817.github.io/Target-Company-Prompt-Builder/prompt_builder.html)** — researches and ranks companies
- **[Job-Posting-Finder](https://tjackson8817.github.io/Job-Posting-Finder/job_posting_finder.html)** — checks who's actively hiring, right now
- **[Outreach-Message-Builder](https://tjackson8817.github.io/Outreach-Message-Builder/outreach_message_builder.html)** — drafts the actual outreach messages

This tool picks up once you've actually landed an interview — the stage none of the other tools cover. Afterward, the specific things you actually discuss become the Context Notes for a genuinely grounded thank-you message back in the Outreach Message Builder, closing the loop.

## Three modes, not one generic form

Pick a mode at the top of the page — it switches the entire field set and the entire generated guide, not just a couple of options:

- **Recruiter Screen** — a qualifications T-chart, a tight "tell me about yourself" script, coached answers for the gap/leaving question and the salary question (grounded in real market research, framed as a range, not a negotiation), standard logistics questions, and recruiter-appropriate questions to ask.
- **Hiring Manager Interview** — built for a real, time-boxed video call: company/role research, a resume-to-JD gap map, interviewer research (if named), a video-call logistics checklist tied to your actual platform, pacing scaled to your actual call length, your top 3-4 STAR-structured stories (not an exhaustive list), and HM-appropriate questions to ask.
- **General / Other** — the fuller original structure (company snapshot, gap map, interviewer research, four categories of likely questions, STAR story scaffolding, questions to ask) as a fallback for technical rounds, panels, and final rounds.

## Quick start

1. Open `interview_prep_guide_builder.html` (via GitHub Pages, or download and double-click it).
2. Pick your mode: Recruiter Screen, Hiring Manager Interview, or General/Other.
3. Fill in the company, role, job description, and your resume (paste text, or plan to attach the files directly when you paste the prompt into Claude).
4. Fill in whatever's specific to your mode — location and salary context for a recruiter screen; call length, platform, and interviewers for a hiring-manager call; stage and interviewers for anything else.
5. Copy the generated prompt and paste it into a new Claude chat.
6. Review the guide — especially anything it flagged as needing your own input (a gap reason, an interviewer with no public footprint) — before your interview.

## What makes this different from generic interview advice

- **Never a scripted answer.** For behavioral questions, the guide points you to the specific resume bullet that's your strongest match and prompts STAR structure — it does not write the story for you. Claude doesn't know what actually happened in your work beyond what your resume states, and inventing specifics risks putting words in your mouth you'd have to walk back live.
- **Interviewer research stays evidence-based.** If a named interviewer has little or no public footprint, the guide says so plainly and falls back to role-based prep instead of inventing a personality or interests to seem more personalized.
- **The salary question is grounded in real search, not a guess.** Recruiter Screen mode requires actual market-data research (levels.fyi, Glassdoor, Payscale, BLS data, comparable postings with disclosed ranges) with sources noted — never a number pulled from nowhere.
- **Sensitive personal facts stay yours to supply.** The reason for a gap or departure, your notice period, work authorization status — the guide never invents these. Left blank, it gives you general guidance on how to structure the answer instead.

## Files in this repo

| File | What it is |
|---|---|
| `interview_prep_guide_builder.html` | The interactive tool. Open it directly in any browser, or use the GitHub Pages link above. |
| `Interview_Prep_Guide_Builder_User_Guide.md` | Full usage guide — all three modes, every field, and the guardrails explained. |
| `Interview_Prep_Guide_Builder_User_Guide.docx` | Same guide, as a Word document. |
| `sample_recruiter_screen_prompt.txt` | Real example of Recruiter Screen mode's generated prompt. |
| `sample_hiring_manager_prompt.txt` | Real example of Hiring Manager mode's generated prompt. |
| `sample_general_prompt.txt` | Real example of General/Other mode's generated prompt. |

## Notes

- This repo can be public or private — GitHub Pages on the free tier requires a public repo (or a paid plan for private-repo Pages).
- Requires Web search in Claude for the company, interviewer, and salary research; Code execution and file creation only if you choose the downloadable Word document output.
- The generated prompt opens with an explicit "execute this directly, don't ask clarifying questions" instruction, aimed at other AI tools (e.g. ChatGPT) that sometimes respond with questions instead of just running the task.
- Interviewer lists are tracked separately per mode — switching from Hiring Manager to General/Other (or back) won't carry interviewers over between them, since they're genuinely separate lists.
