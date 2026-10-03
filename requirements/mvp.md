# MVP requirements

Fill this in after choosing an idea from the research report.

## Outcome

Buyer, user, trigger, accepted output, and the smallest useful job:

## Screens and states

Landing page promise, input form, processing state, result/review state, error state:

## API contract

Endpoints, request/response examples, validation, rate limits:

## Data

Tables, retention, deletion, export, and whether real customer data is allowed:

## Acceptance tests

Map each criterion in `idea.json` to an observable test:

## Operations

Support, onboarding, review, exceptions, and a five-hour weekly workload estimate:

## Release

Use a unique `<idea-slug>.nex2i.com` Netlify custom domain. Record the final Netlify and Render URLs, `NETLIFY_PROXY_ORIGIN`, exact `CORS_ORIGIN`, and optional `VITE_POSTHOG_PROJECT_TOKEN` and `VITE_POSTHOG_HOST`. After deployment, smoke test the buyer task and, when enabled, confirm a consented event reaches the MVP's PostHog project while a declined visit sends no events:
