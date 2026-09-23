# AssetFare

AssetFare builds non-custodial, agent-native cross-chain route infrastructure.
The public service currently exposes six chains, eleven source endpoints and 76
directed routes through REST/OpenAPI, MCP and A2A.

AssetFare returns quotes and caller-approved **unsigned** actions. The service
does not receive private keys, sign transactions, or submit transactions. The
caller must decode, verify, sign and submit with its own wallet.

## Verify instead of trusting a badge

- [Signed release manifest](https://api.assetfare.dev/.well-known/assetfare-manifest.json)
- [Machine-verifiable safety bundle](https://api.assetfare.dev/.well-known/assetfare-safety.json)
- [Reproducible execution-core source and artifacts](https://github.com/assetfare/assetfare-core-evidence)
- [Independent verifier CLI and agent adapters](https://github.com/assetfare/assetfare-mcp)
- [On-chain execution evidence](https://assetfare.dev/evidence/)
- [Live capabilities](https://api.assetfare.dev/v2/capabilities)
- [Security policy](https://assetfare.dev/security/)

## Public repositories

- [`assetfare-mcp`](https://github.com/assetfare/assetfare-mcp) — MCP/A2A adapters, verifier CLI and agent integrations
- [`assetfare-core-evidence`](https://github.com/assetfare/assetfare-core-evidence) — five reproducible Solidity executors, exact artifacts and executable invariants
- [`dify-plugin-assetfare`](https://github.com/assetfare/dify-plugin-assetfare) — restricted read-only Dify Marketplace integration
- [`smolagents-assetfare`](https://github.com/assetfare/smolagents-assetfare) — Hugging Face smolagents tools

## Project status

AssetFare is operated by a project team and is not presently claiming to be an
incorporated legal entity. Security evidence is project-authored unless a page
explicitly identifies an independent reviewer. Automated checks and audits
reduce risk but do not guarantee that software is defect-free.

- Website: <https://assetfare.dev>
- Agent guide: <https://assetfare.dev/llms.txt>
- General contact: `support@assetfare.dev`
- Security reports: `security@assetfare.dev`
- Administration: `admin@assetfare.dev`
