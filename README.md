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

Pick a mode at the top of the page — it switches the entire field set and the entire generated guide, not just a couple of options. Every mode opens with the same Section 1: a **30-45 second "Tell Me About Yourself" answer** in three timed parts — Early Years (~10 sec), Most Recent Role (~10 sec), and What You'll Bring to This Role (~10-15 sec, the longest part, focused on how your resume lines up with this job description). It's also repeated at the top of the Quick Reference, since it's usually the first question asked. You also get a 20-second version for panels and networking, a one-sentence hook at the end that ties you to this specific role, and (if you gave a reason for leaving) a pointer to your gap answer, since "So what happened there?" is usually the next question. Optional fields for where you're from, your education, and the 2-3 things you most want remembered fill in what resumes leave out. Skip them and the answer works from your resume alone. Part 1 never includes dates, so it doesn't invite assumptions about age.

- **Recruiter Screen** — the 30-45 second "Tell Me About Yourself" answer, a qualifications T-chart, coached answers for the gap/leaving question and the salary question (grounded in real market research, framed as a range, not a negotiation), honest objection reframing for any concerns you name, standard logistics questions, and recruiter-appropriate questions to ask.
- **Hiring Manager Interview** — built for a real, time-boxed video call: the 30-45 second "Tell Me About Yourself" answer, company/role research, a resume-to-JD gap map, objection reframing, interviewer research (if named), a Candidate SWOT Analysis with honest weakness-mitigation talking points, a video-call logistics checklist tied to your actual platform, pacing scaled to your actual call length, your top 3-4 STAR-structured stories (not an exhaustive list — uses your own STAR Stories as-written if you supply them, otherwise points you to the right resume bullets), and HM-appropriate questions to ask.
- **General / Other** — the fuller original structure (the 30-45 second "Tell Me About Yourself" answer, company snapshot, gap map, objection reframing, interviewer research, the same Candidate SWOT Analysis, four categories of likely questions, STAR story scaffolding, questions to ask) as a fallback for technical rounds, panels, and final rounds.

## Quick start

1. Open `interview_prep_guide_builder.html` (via GitHub Pages, or download and double-click it).
2. Pick your mode: Recruiter Screen, Hiring Manager Interview, or General/Other.
3. Fill in the company, role, job description, and your resume (paste text, or plan to attach the files directly when you paste the prompt into Claude).
4. Optionally, fill in the "Tell Me About Yourself" extras (where you're from, education, the 2-3 things you most want remembered). Then fill in whatever's specific to your mode — location and salary context for a recruiter screen; call length, platform, and interviewers for a hiring-manager call; stage and interviewers for anything else. Optionally name any concerns you're worried will come up (a gap, a pivot, short tenures) and, in Hiring Manager or General/Other mode, write your own STAR Stories if you already know which ones you want to use.
5. Copy the generated prompt and paste it into a new Claude chat.
6. Review the guide — especially anything it flagged as needing your own input (a gap reason, an interviewer with no public footprint) — before your interview.

## What makes this different from generic interview advice

- **Never a scripted answer.** If you filled in the optional STAR Stories field, the guide uses those stories exactly as you wrote them and never embellishes them. Where a slot is unfilled, it points you to the specific resume bullet that's your strongest match and prompts STAR structure — it does not write the story for you. Claude doesn't know what actually happened in your work beyond what your resume states (or what you wrote yourself), and inventing specifics risks putting words in your mouth you'd have to walk back live.
- **"Tell Me About Yourself" stays factual.** The 30-45 second answer is built only from your resume, your own STAR Stories, and the optional extras. A detail none of those supply, like your hometown or school, is left out rather than invented, and anything you ask it to emphasize that your resume doesn't back up is flagged rather than stretched.
- **Interviewer research stays evidence-based.** If a named interviewer has little or no public footprint, the guide says so plainly and falls back to role-based prep instead of inventing a personality or interests to seem more personalized.
- **SWOT weaknesses stay honest.** In Hiring Manager and General/Other modes, a real weakness in the Candidate SWOT Analysis is never softened into a non-weakness, and its mitigation talking point is never a fabricated accomplishment used to explain the gap away — same standard as objection reframing.
- **Objection reframing stays honest, not spin.** Every reframe for a named concern is grounded in something real from your resume — if a concern genuinely doesn't have a strong answer, the guide says so rather than manufacturing one.
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
| `sample_prompt_objection_reframing.txt` | Real example of Hiring Manager mode's generated prompt with objection reframing and STAR Stories filled in. |
| `interview_sample_output.md` / `.docx` | The actual guide Claude returns when the prompt above is run — shows the "Tell Me About Yourself" answer, Candidate SWOT Analysis, and STAR Stories sections in context. |
| `interview_sample_output_cliftonstrengths.md` / `.docx` / `.doc` | The same guide with the optional CliftonStrengths fields filled in — adds the CliftonStrengths Talking Points section and feeds it into the SWOT. |

## Notes

- This repo can be public or private — GitHub Pages on the free tier requires a public repo (or a paid plan for private-repo Pages).
- Requires Web search in Claude for the company, interviewer, and salary research; Code execution and file creation is always needed, since every guide now comes back as a downloadable Word document.
- The generated prompt opens with an explicit "execute this directly, don't ask clarifying questions" instruction, aimed at other AI tools (e.g. ChatGPT) that sometimes respond with questions instead of just running the task.
- Interviewer lists are tracked separately per mode — switching from Hiring Manager to General/Other (or back) won't carry interviewers over between them, since they're genuinely separate lists.
