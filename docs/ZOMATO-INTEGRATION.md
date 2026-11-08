# Zomato integration request

## Who we are
An individual developer building a personal, non-commercial voice assistant ("Polygon"). Not affiliated with Zomato.

## What we want to build
A mobile app where a user says e.g. "order my usual from X" or "where is my order?", and the app performs it and answers aloud.

## What we need from Zomato
We do not yet know whether a public developer or sandbox API exists. We are asking:
1. Is there an official developer program, public API, or sandbox for individual developers?
2. If the official MCP server is the supported route, is there a way for individuals to access it without a Claude Pro subscription (e.g. standalone OAuth client)?
3. Terms of use, rate limits, and any restrictions on voice-driven or automated ordering.

## Capabilities we would use (minimum scope)
Search restaurants, view menus, manage a cart, checkout, view order history, track an order, read saved addresses. Nothing beyond these.

## How we will use it
- Each user authenticates with their own Zomato account; we never share or pool accounts.
- Every checkout requires an explicit spoken confirmation plus an on-screen confirmation of items and total before it is placed.
- No scraping, no bulk requests, no reselling or republishing of Zomato data.
- Only the sandbox/test environment (if offered) is used during development.

## Contact
GitHub: kaizen2k06-glitch (open an issue on this repository)
