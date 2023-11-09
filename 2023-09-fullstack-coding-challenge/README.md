# Blinq Full-Stack Coding Challenge

Blinq intends to supply third-party integrations for our business customers. Each business customer's workspace can be connected to multiple third-party services. We need you to build out the integration settings page for our customers.

## The challenge

Build a simple integration settings page for Blinq business customers. The user should be able to connect, configure & disconnect each provider.

The solution should be extensible so that many more integration partners can be added.

For this challenge, only three integration partners are required:

- Salesforce
- HubSpot
- Zapier

Each third-party integration has its own set of fields that are required for Blinq to connect to each integration partners API:

### Salesforce

- `client_id`
- `client_secret`

### Zapier

- `api_key`

### HubSpot

- `tenant_domain`
- `client_id`
- `client_secret`

For HubSpot integrations, Blinq needs to know which fields to map the contact details to. Within HubSpot's API, these may be keys like: `first_name`, `last_name` or `hs_custom_field1234`.

## The codebase

A mock database is available in `/database/index.ts`. You can use this as a simple in-memory database, you do not need to integrate your own database.

A sample of a user & contact are already defined within the database so you can get started quickly.

Please expand on the existing codebase to complete the challenge.

## The Project Template

We have leveraged Next.js (a popular framework we love using here at Blinq) to set you up with a mock database, user interface and APIs in this project template.

You should extend this codebase to complete the coding challenge.

## Getting Started

Setup by running `yarn` && `yarn dev`

## More information

- You do not need to actually sync the contacts with these external services
- You do not need to create actual database connections

## Submitting

Please bundle your submission using git. To do this, commit your changes & then run:

```bash
git bundle create <your_name>.bundle --all
```

Then email the bundle file to your Blinq contact.
