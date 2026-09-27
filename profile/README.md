## RIAIntelligence

Raya is an AI working environment for independent advisory firms: one build a firm's people open in
Microsoft Teams or a browser, reading the firm's CRM, portfolio system, custodian files, documents
and mail into one database the firm owns. RIAIntelligence builds it, fits it to each firm and keeps
it running. Today it runs on an invented firm. No real firm is connected.

### The repositories

| | |
|---|---|
| **[raya](https://github.com/RIAIntelligence/raya)** | The product. `docs/` says what Raya is and does, exactly enough to build from, and the code is built from those documents in numbered sprints. Start at `docs/RAYA-INDEX.md`. |
| **[hq](https://github.com/RIAIntelligence/hq)** | The company. Its current position on every topic (`spine/`), outside facts with their sources (`research/`), the story so far (`HISTORY.md`), and the live website and demo. |
| **hq-local** | Private. Real advisory material, recorded meetings and dictated direction. Clients appear only as patterns. |
| **tenant-firm-01** | Private. The first firm's record. |

Everything else here is archived and takes no work.

### How to work

Open Claude Code in `hq` for company work or in `raya` for product work, on your own machine or in
the cloud at claude.ai/code. The session loads who we are, what is settled and what is in flight, so
say what you want in plain words. In `raya`, "run the next sprint" builds the next piece of the
queue.

Nobody pushes to main. Work goes up as a pull request, the checks run, and it merges itself when
they pass. A routine on the founder's account runs the next sprint every three hours with nobody at
a machine; its switch is at claude.ai/code/routines.

The team talks in Slack: `#riai` for the product, `#riai-dev` for code.

### Where to read

- **What Raya is** → `raya/docs/RAYA-BIBLE.md`
- **What is built next** → `raya/docs/RAYA-BUILD-ORDER.md`
- **The company's position on a topic** → `hq/spine/`
- **What happened, and where older work went** → `hq/HISTORY.md`
- **A fact about the market, a vendor or a regulation** → `hq/research/INDEX.md`
- **What a word means** → `raya/docs/RAYA-GLOSSARY.md`

### What is live

- [www.riaintelligence.ai](https://www.riaintelligence.ai), the website
- [app.riaintelligence.ai](https://app.riaintelligence.ai), the demo on the invented firm

### Who carries what

| | |
|---|---|
| Erik, founder | Direction, product and positioning; anything that commits money or signs; the first firm |
| Justin, product lead | What the product does and how it feels; the demo; acceptance of its journeys |
| Daniel, infrastructure and security lead | Deployment, environments, identity, integrations, security; the code host, hosting and merging |
| Brittany, delivery lead | Onboarding and support; the website, proposals and teaching; how the product talks |

### What never enters a repository

A client's name. A firm's raw material or recordings, which live in `hq-local`. A key.
