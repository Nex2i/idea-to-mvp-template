# Implement the selected MVP

Read `requirements/idea.json`, `requirements/mvp.md`, `requirements/template-requirements.md`, and `AGENTS.md`. Read the opportunity report supplied for this run. Do not infer that a project should be built from a research score alone; use its explicit decision level and current buyer evidence.

If `idea.json` is still in template status, first turn the selected experiment into a concrete, reviewable requirement brief. Stop domain implementation if buyer, trigger, accepted output, or acceptance criteria are still unknown.

Build the smallest complete buyer task in the existing React/API/Postgres app. Keep the landing page claim specific and label unverified claims as hypotheses. Implement reusable authentication according to `docs/auth-design.md` before inviting real account holders. Use environment secrets, migrations, safe logs, and deterministic tests. Never commit customer data or credentials.

Run `npm test` and `npm run build`. Review the diff, list unmet requirements and operational risks, and deploy only after the chosen hosting path is configured. For a customer-facing deployment, verify registration, email confirmation, username login, reset, logout, session behavior, and the core buyer task in the live browser. Record actual URLs and results in `requirements/mvp.md`.
