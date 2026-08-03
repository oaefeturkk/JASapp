# JASapp — Who Do You Trust?

A bilingual (EN/TR) interactive web experiment based on the **Judge-Advisor System (JAS)** paradigm. Participants answer general-knowledge estimation questions, receive advice from three simulated sources — an AI Agent, a Human Expert, and an Anonymous peer — and revise their answers. The app tracks which advisor participants trusted most, along with Weight of Advice (WoA), confidence shifts, and response times.

## Live Demo

Once GitHub Pages is enabled for this repo, the app will be available at:
`https://oaefeturkk.github.io/JASapp/`

## Features

- 🌐 Full English / Turkish language support (switchable anytime, including mid-session)
- ✅ Informed consent screen with nickname/email fields and a detailed research ethics notice
- 🤖🧑‍⚕️🙂 Three animated advisors (AI, Human Expert, Anonymous) revealing close-but-distinct estimates
- 📊 End-of-session "trust profile" with animated bars, Weight of Advice, confidence-gain, and accuracy stats
- 📝 Trial-by-trial results log
- 🔒 No backend required — runs as a single self-contained HTML file

## How It Works

1. Participant enters an **initial estimate** and **confidence rating**.
2. Three advisors reveal their own estimates one by one.
3. Participant clicks the advisor they trust most (or keeps their own estimate) to set their **final answer**.
4. Participant optionally rates their **final confidence**.
5. After all questions, a results screen summarizes trust patterns and decision metrics.

## LINK
https://oaefeturkk.github.io/JASapp/

## Data Collection

Research data (estimates, confidence, advisor choices, response times) is submitted via a form-based endpoint (e.g., [Formspree](https://formspree.io)) when the participant consents. See the `sendResearchData` function in the source for configuration.

## License

Released under the [MIT License](LICENSE.md).

## Disclaimer

This is a research/educational prototype. Advisors are algorithmically generated and do not represent real people, real experts, or real AI systems.
