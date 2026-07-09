# Tre-Up

Tre-Up is a pre-MVP, iOS-first behavioral productivity system built around
one question: not "what should you do today," but "why do you keep not
doing it, and when is the moment it slips away?"

## What Tre-Up Is

Tre-Up reads behavioral signals — timing patterns, consistency, self-reported
intent, and later passive signals like sleep and activity — to help someone
notice the point where a plan, a day, or a habit starts to drift, before it's
already lost. The working name for this signal-to-guidance layer is **Hawk**.
Detail: [`docs/PRODUCT.md`](./PRODUCT.md)

## What Tre-Up Is Not

- Not a to-do list
- Not a habit tracker
- Not a mood tracker
- Not a general-purpose AI chatbot
- Not a wellness gimmick or a dashboard full of numbers nobody reads

## Current Stage

**Pre-MVP.** No shipped product, no public app, no user base yet. What
exists today:

- A locked internal product constitution defining the behavioral principles
  the product is built against
- This public overview and the infrastructure direction it describes
- An in-progress evaluation of cloud platforms ahead of building the first
  backend and prototype

This repository is published to give an honest picture of where things
stand to cloud credit reviewers and anyone else evaluating Tre-Up early —
not a polished product demo.

## Product Thesis

Most people already know what they should do. The failure point is rarely
information — it's timing, environment, and the moment a plan quietly falls
apart without anyone noticing until much later. Tre-Up is built on the bet
that a system designed to notice that moment, and say something useful
about it, is worth more than another list of tasks.

## Planned Infrastructure

We're evaluating cloud platforms to support the first backend, an early
Hawk prototype, and secure signal storage. Nothing below is built, awarded,
or committed yet. Detail: [`docs/INFRASTRUCTURE.md`](./INFRASTRUCTURE.md)

| Area | Target services under evaluation |
|---|---|
| AI workflow experimentation | AWS Bedrock, Google Vertex AI / Gemini, Azure OpenAI / Azure AI Foundry |
| Backend & storage | Managed backend compute, encrypted signal storage |
| Observability | Logging, monitoring, early-stage analytics |

## Current Focus

- Finalizing infrastructure direction across the platforms above
- Applying to early-stage cloud credit programs (AWS, Google Cloud,
  Microsoft Azure)
- Designing the first backend and the Hawk prototype's data contract
- Preparing the path to a small private beta once infrastructure exists

Roadmap: [`docs/ROADMAP.md`](./ROADMAP.md)

## Team

Yiğit Ali Kurt — founder, building solo at this stage.
Detail: [`docs/TEAM.md`](./TEAM.md)

## Contact

- Email: [company@tre-up.com](mailto:company@tre-up.com)
- Website: [tre-up.com](https://tre-up.com)

## License

See [`LICENSE`](./LICENSE). Proprietary — published for transparency, not
for reuse or redistribution.
## Security and Prıvacy
Security & privacy direction: [`SECURITY_AND_PRIVACY.md`](./SECURITY_AND_PRIVACY.md)
