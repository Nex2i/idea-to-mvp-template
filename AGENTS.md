# Idea-to-MVP agent contract

Read `requirements/idea.json` and `requirements/mvp.md` before changing the app. If the idea brief still contains placeholders, complete the requirements from a research report or ask for the missing decision before building domain features.

Preserve the selected buyer, trigger, input, accepted output, and measurable acceptance criteria. Keep the first version to one narrow end-to-end task. Implement the domain flow in `apps/web` and `apps/api`, replace the demo waitlist, add only the tables needed, and keep `/health` working. Keep credentials in environment variables. Do not add paid services by default.

Run the requirements validator and build checks. Update `requirements/mvp.md` with the actual API contract, data model, test cases, deployment variables, and manual review steps. Record unresolved buyer or compliance assumptions; do not invent customer validation.

The research stage uses `prompts/commercial-opportunity-research.txt`. Do not run that long research automatically on every code change. Research and code generation require an authorized AI runtime; GitHub Actions CI only validates deterministic work.

Keep this checkout at `~/projects/mvp-ideas/idea-to-mvp-template`. Create each selected idea as a separate sibling checkout at `~/projects/mvp-ideas/<idea-slug>` from the public GitHub template. Do not implement an idea in this template checkout. Use a unique `<idea-slug>.nex2i.com` Netlify domain for each deployed MVP.
