# Balanced Website

A standalone, lightweight public informational website for the Balanced ecosystem.

## Pages
- `/` company homepage and ecosystem overview
- `/life` Life: Balanced product introduction
- `/health` deployment health endpoint

## Run
`npm start` (Node.js 20+; no dependency install required).

## Deployment and domain
Deploy the branch `site/balanced-corporate-20261014` as an independent Railway service. It must not be deployed over the Life: Balanced API service. Connect `balanced.tools` only after confirming the hosting target and the registrar DNS entries; preserve `calendar.balanced.tools` CNAME and Google OAuth callback.

No real sign-in, billing, mailing-list capture, or product downloads are present. All early-stage product descriptions are aspirational. Email contact must be verified and provisioned before advertising it publicly.
