# Liquidly

Liquidly (Liquidly, Inc.) is a New York based financial technology company building infrastructure for illiquid assets — a permission-based secondary marketplace that lets holders of private fund interests transact without disrupting the fund. It serves fund managers (streamlined, centrally supervised transfers plus market data), seller investors (a manager-approved sale process and standardized commercial terms), and buyer investors (manager-granted asset permissions and standardized diligence materials). Broker-dealer services are offered through Liquidly IAS, LLC, registered with FINRA and a member of SIPC.

- Website: https://www.liquidly.com/
- Platform login: https://demo.liquidly.com/Account/Login
- Legal / regulatory disclosures: https://www.liquidly.com/Legal

## API surface

**Liquidly publishes no public API.** As of the 2026-07-19 enrichment pass there is no developer portal, API reference, OpenAPI/AsyncAPI specification, SDK, CLI, webhook catalog, status page, changelog, or `/.well-known/` discovery document on any Liquidly host. The product is reached only through an authenticated web application. Artifacts in this repo are therefore identity, compliance, and security-posture only.

## Artifacts

- `conformance/liquidly-conformance.yml` — regulatory conformance posture (FINRA, SIPC, CIP, business continuity)
- `security/liquidly-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC
- `well-known/liquidly-well-known.yml` — probed `/.well-known/` surface (recorded negative result)
- `llms/liquidly-llms.txt` — agent-readable summary

Backed by: Anthemis, Portage Ventures, Village Global, AmTrust Financial.
