# Polygon

A voice-first mobile assistant for food ordering. The user speaks; Polygon understands the request, performs the action through an MCP (Model Context Protocol) server, and replies by voice.

**Status:** pre-development / design. No code, no credentials, and no Zomato integration exist yet.

## Flow
```
mic -> speech-to-text -> LLM agent (Claude) -> MCP tool call -> result -> text-to-speech -> speaker
```

## Docs
- [docs/ZOMATO-INTEGRATION.md](docs/ZOMATO-INTEGRATION.md) - what we need from Zomato and how we will use it
- [docs/SECURITY.md](docs/SECURITY.md) - data handling and security commitments
- [SECURITY.md](SECURITY.md) - how to report a vulnerability

## Contact
Maintainer: GitHub `kaizen2k06-glitch`
