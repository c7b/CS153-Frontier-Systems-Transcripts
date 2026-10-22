# Stanford CS153 Frontier Systems: transcripts

Every lecture from Stanford's CS153 course, as readable text you can search and quote. Fourteen talks, about 14 hours, 143,000 words. Speakers include Satya Nadella, Sam Altman, Jensen Huang, and Ben Horowitz, plus ten other founders and operators.

## Give this to your AI, don't just watch it

Watching 14 hours of video is slow, and most of it won't apply to you. Your AI assistant already knows what you're building. So hand it these transcripts and let it find what matters for your situation.

Paste this into Claude, ChatGPT, or Cursor along with the transcripts (or just the repo link):

> You have the transcripts of Stanford CS153 "Frontier Systems" (Nadella, Altman, Huang, Horowitz, and 10 other founders). You know what I'm working on.
>
> 1. The 5 ideas most relevant to my work right now. Give the speaker and timestamp for each.
> 2. Where my current strategy looks weak next to what these people actually say.
> 3. Three things I should do this week as a result.
>
> Cite the transcript and timestamp for every point.

When it flags something, open that transcript and search for the line. Text is easier to search and quote than a video, and a model can read all of it in seconds. That's where you'll see where your own thinking falls short, so go back to the transcript, not the clip.

The repo ships with an `AGENTS.md` (the standard file agents read). Tools like Claude Code, Cursor, and Codex pick it up on their own, so the agent will know what these files are and will ask you about your work before it answers.

## The lectures

| # | Speaker | Role | Talk | Links |
|--:|---------|------|------|-------|
| 1 | Satya Nadella | CEO, Microsoft | Building the Frontier Ecosystem | [transcript](01-satya-nadella-building-the-frontier-ecosystem.md) · [video](https://youtu.be/d0Pfu6B7gIM) |
| 2 | Sam Altman | CEO, OpenAI | Scale, AGI, and the Future of Everything | [transcript](02-sam-altman-scale-agi-and-the-future-of-everything.md) · [video](https://youtu.be/F_7M4Hc-usM) |
| 3 | Joe Sullivan | Former CSO, Uber & Cloudflare | The Road Ahead: Resilience Required | [transcript](03-joe-sullivan-the-road-ahead-resilience-required.md) · [video](https://youtu.be/g50FHC-PzK8) |
| 4 | Amin Vahdat | VP, ML & Cloud AI, Google | The Discipline of Delivering Value per Gigawatt | [transcript](04-amin-vahdat-value-per-gigawatt.md) · [video](https://youtu.be/VeTqsCpcDgg) |
| 5 | Garry Tan & Diana Hu | Y Combinator | The AI-Native Company: One Founder as a 1000x Engineer | [transcript](05-garry-tan-diana-hu-the-ai-native-company.md) · [video](https://youtu.be/Lri2LNYtERM) |
| 6 | Jensen Huang | CEO, NVIDIA | The Compute Behind Intelligence | [transcript](06-jensen-huang-the-compute-behind-intelligence.md) · [video](https://youtu.be/tsQB0n0YV3k) |
| 7 | Scott Nolan | CEO General Matter, Partner Founders Fund | Energy Bottlenecks | [transcript](07-scott-nolan-energy-bottlenecks.md) · [video](https://youtu.be/wisccQYTRQc) |
| 8 | Ben Horowitz | Co-founder, a16z | Venture Capital Systems & Network Effects | [transcript](08-ben-horowitz-venture-capital-systems.md) · [video](https://youtu.be/B8NvdfssGac) |
| 9 | Nikhyl Singhal | Founder Skip, ex-VP Product Meta | Product Management in the AI Era | [transcript](09-nikhyl-singhal-product-management-in-the-ai-era.md) · [video](https://youtu.be/BQrJ4lHAjhc) |
| 10 | Amit Jain | CEO, Luma AI | Unified Intelligence Systems | [transcript](10-amit-jain-unified-intelligence-systems.md) · [video](https://youtu.be/6nUl_w5W9Wk) |
| 11 | Andreas Blattmann | Co-founder, Black Forest Labs | Visual Intelligence | [transcript](11-andreas-blattmann-visual-intelligence.md) · [video](https://youtu.be/CBaLU0dDEY8) |
| 12 | Mati Staniszewski | CEO, ElevenLabs | The Future of Voice Systems | [transcript](12-mati-staniszewski-the-future-of-voice-systems.md) · [video](https://youtu.be/vfF011ko89o) |
| 13 | Anjney Midha | Founder, AMP PBC (ex-a16z) | Frontier Systems | [transcript](13-anjney-midha-frontier-systems.md) · [video](https://youtu.be/O5PfU_uDhS0) |
| 14 | Liam Fedus & Ekin Dogus Cubuk | Co-founders, Periodic Labs | Teaching AI to Touch Atoms | [transcript](14-liam-fedus-dogus-cubuk-teaching-ai-to-touch-atoms.md) · [video](https://youtu.be/8cAQdELWYuo) |

Full playlist: [Stanford Online CS153](https://www.youtube.com/playlist?list=PLoROMvodv4rN447WKQ5oz_YdYbS74M5IA).

## How these were made

**Update, October 21, 2026: every line now says who is speaking.**

1. **Audio:** [yt-dlp](https://github.com/yt-dlp/yt-dlp) downloads each video's audio.
2. **Text:** [Whisper large-v3](https://huggingface.co/openai/whisper-large-v3) transcribes it with timestamps. Where it skips punctuation, an AI adds it back without changing any word.
3. **Speakers:** NVIDIA [Nemotron-3 Diarization](https://huggingface.co/nvidia/Nemotron-3-Diarization) separates the voices.
4. **Names:** an AI names each voice from context. Audience questions are "Student"; an unsure moderator is "Host".

**What to keep in mind:** the wording is verbatim, so expect the occasional error in names and technical terms. When two people talk over each other, a short line ("Yeah", "Exactly") can land on the wrong person, and audience questions the guest repeats out loud stay inside the guest's answer. Check the video when precision matters.

The content belongs to the speakers and Stanford. This is an unofficial educational copy of public material, not affiliated with Stanford. If you hold the rights to something here and want it removed, open an issue.

---

by: Cristobal A.
