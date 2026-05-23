# Wawa

Wawa is a privately held, family-owned convenience store and fuel retail chain headquartered in Pennsylvania. Founded in 1803 as a dairy farm and operating convenience stores since 1964, Wawa runs approximately 1,100 stores across PA, NJ, DE, MD, VA, FL, NC, IN, and AL. The brand is known for fresh-made hoagies, built-to-order beverages, fuel, and the Wawa Rewards loyalty program.

This repository profiles Wawa for the [API Evangelist Network](https://github.com/api-evangelist/api-evangelist-network). Wawa does **not** publish a public developer portal, public APIs, OpenAPI specs, SDKs, or a public GitHub presence as of May 2026.

## Status

| Property | Value |
|---|---|
| x-type | company |
| x-tier | 3 |
| x-tier-reason | no-apis |
| Public APIs | none |
| Developer portal | none |
| OpenAPI / AsyncAPI | none |
| SDKs / CLIs | none |
| Public GitHub repos | 0 (org `github.com/wawa` exists but has no public repositories) |
| Status page | none |
| RSS / changelog | none |

## What does exist

- [wawa.com](https://www.wawa.com) — consumer website (menu, store locator, careers)
- [order.wawa.com](https://order.wawa.com) — mobile/web ordering surface
- [Wawa Mobile App](https://www.wawa.com/ways-to-order/mobile-app) — iOS/Android app for ordering, rewards, fuel pricing
- [Wawa Rewards](https://www.wawa.com/rewards) — loyalty program
- Third-party delivery integrations with **Uber Eats**, **Grubhub**, and **DoorDash** — no public API contract for partners is published by Wawa
- Internal MuleSoft-based API management platform (referenced in industry coverage; not publicly accessible)

## Why no artifacts?

Per the API Evangelist pipeline rules, we do not generate empty or placeholder OpenAPI, AsyncAPI, JSON Schema, capability, example, ruleset, plans, rate-limits, or FinOps files when there is no underlying public API to describe. Wawa's digital strategy is consumer-facing and partner-driven through a small set of pre-existing aggregator integrations — there is no documented public developer surface to profile.

If Wawa launches a public developer portal, partner API program (e.g. fleet/fuel-card APIs, location feed, menu/inventory feed, or a webhook surface for delivery partners), this repository will be revisited.

## Files

- [apis.yml](./apis.yml) — APIs.json/APIs.yml index for this provider
- [README.md](./README.md) — this file

## Related

- [API Evangelist Network registry entry](https://github.com/api-evangelist/api-evangelist-network/blob/main/apis.yml)
- [Wawa on GitHub](https://github.com/wawa) (0 public repos)
