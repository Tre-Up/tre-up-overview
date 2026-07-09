# Infrastructure (Planned)

Status: pre-MVP. Nothing described below is built yet — this is the
direction we're building toward, and the reason we're applying for
early-stage cloud credits in the first place.

## What We're Building Toward

- A backend API layer handling auth, the first data contract with the iOS
  client, and the pipeline that turns raw signals into the structured
  input Hawk's prototype will use
- Secure, encrypted storage for behavioral signal data, built with data
  minimization in mind from the start — see
  [`SECURITY_AND_PRIVACY.md`](./SECURITY_AND_PRIVACY.md)
- A small AI workflow testing environment to evaluate model behavior for
  Hawk's early prototype — this is experimentation, not a finished
  pipeline
- Basic logging, monitoring, and early-stage analytics, so we can tell
  whether the prototype is doing anything useful once real usage starts

## Client

iOS-first mobile app. The long-term Premium V1 target is native
Swift/SwiftUI; specific prototype implementation details may still evolve
during MVP development. Android is not part of the current plan — it may
be evaluated after Premium V1, if at all, but it isn't promised.

## Target Cloud Services (evaluation stage — no credits awarded yet)

We're applying to early-stage cloud credit programs across AWS, Google
Cloud, and Microsoft Azure. None of these credits are guaranteed or
currently awarded. The table below reflects intended usage **if**
applications are approved, not confirmed infrastructure.

| Provider | Target services |
|---|---|
| AWS | AWS Bedrock (AI workflow experimentation), backend infrastructure, secure storage, logging/monitoring |
| Google Cloud | Vertex AI / Gemini (model experimentation), backend services, secure data storage, early-stage analytics |
| Microsoft Azure | Azure OpenAI / Azure AI Foundry, backend APIs, observability, secure early-access testing infrastructure |

We expect the specific mix to narrow once we know which programs approve
credits and at what tier. This is not a commitment to run full production
infrastructure across all three platforms at once.

## Why This Needs Funding Before Revenue Exists

There's no product to charge for yet. The infrastructure described above
is what has to exist before there's anything to test with a small group of
early users — which is the actual next milestone. See
[`ROADMAP.md`](./ROADMAP.md).
