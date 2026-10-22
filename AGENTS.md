# AGENTS.md

This repo holds transcripts of 14 lectures from Stanford's CS153 "Frontier Systems" course (2026). If someone points you here, your job is to connect these talks to what that person is actually doing. Do not just summarize the course.

## What's in the repo

- Files `01` through `14` in the root: one transcript per lecture, named `NN-speaker-topic.md`.
- Every paragraph starts with a `[mm:ss]` timestamp that maps to the video, followed by who is speaking (`**[mm:ss] Name:**`). Paragraphs that continue the same person's answer only carry the timestamp. Audience questions are labeled `Student`; a moderator who could not be named with confidence is `Host`.
- `index.json`: the same list in machine-readable form (guest, role, title, video URL, date, word count, and everyone who speaks).

## The lectures

1. Satya Nadella (Microsoft) — building the frontier ecosystem
2. Sam Altman (OpenAI) — scale, AGI, and the future
3. Joe Sullivan (ex-CSO Uber, Cloudflare) — resilience when things go wrong
4. Amin Vahdat (Google) — value per gigawatt
5. Garry Tan & Diana Hu (Y Combinator) — the AI-native company, one founder as a 1000x engineer
6. Jensen Huang (NVIDIA) — the compute behind intelligence
7. Scott Nolan (General Matter, Founders Fund) — energy bottlenecks
8. Ben Horowitz (a16z) — venture capital and network effects
9. Nikhyl Singhal (Skip, ex-Meta) — product management in the AI era
10. Amit Jain (Luma AI) — unified intelligence systems
11. Andreas Blattmann (Black Forest Labs) — visual intelligence
12. Mati Staniszewski (ElevenLabs) — the future of voice
13. Anjney Midha (AMP PBC, ex-a16z) — frontier systems
14. Liam Fedus & Ekin Dogus Cubuk (Periodic Labs) — teaching AI to touch atoms: autonomous labs for new materials

## Ask the user about themselves first

This is the important part. Generic course takeaways are not useful. The value comes from tailoring the lessons to the person in front of you.

If you do not already know the following, ask the user before you give any advice. Ask it as one short batch, not one question at a time, then proceed once they answer.

- What are you building, and what is your role in it?
- What stage are you at, and what is your main goal for the next 3 to 6 months?
- Where do you feel stuck, unsure, or behind?
- What constraints are you working under? Think team size, funding, compute, time, or market.
- Are there speakers or topics you most want to dig into? (optional)

If the user has already given you this context, through open files, a linked project, or earlier messages, use it and skip the questions. If something they say is vague, ask one follow-up rather than guessing.

## How to answer once you have context

1. Read the transcripts that fit the user's situation. Search across all 14 when a topic could appear in several.
2. Tie specific ideas to the user's work. For each, name the speaker, the file, and the `[mm:ss]`.
3. Quote the transcript itself, not your prior memory of what the speaker believes.
4. Be direct where the user's current plan looks weak against what these operators say. Disagreement is more useful than validation.

## Suggested output

- The 5 ideas most relevant to this user, each with speaker and `[timestamp]`.
- Where their strategy looks weak, paired with the counter-point from a transcript.
- 3 concrete actions to take this week.

## Notes

- The text is machine-transcribed (Whisper) and the speakers machine-separated (NVIDIA Nemotron), so expect minor errors in names and technical terms, and the odd short line credited to the wrong person. The meaning is intact.
- Most lectures are interviews: the host (Anjney Midha or Michael Abbott, the course instructors) asks and the guest answers. Cite the guest for their views, not the host's framing.
- When you cite something, prefer the transcript text over the video.
