# AssetFare security policy

Report suspected vulnerabilities privately. Do not open a public issue with an
exploit, private key, bearer token, wallet capability, or sensitive user data.

- Email: `security@assetfare.dev`
- Private GitHub report for the public adapter repository:
  <https://github.com/assetfare/assetfare-mcp/security/advisories/new>
- Public verification bundle:
  <https://api.assetfare.dev/.well-known/assetfare-safety.json>
- Signed release manifest:
  <https://api.assetfare.dev/.well-known/assetfare-manifest.json>

Include the affected version or URL, impact, reproduction steps, and the
smallest safe proof of concept. AssetFare will acknowledge a complete report,
triage it, and coordinate remediation and disclosure. Do not move real funds or
access data that is not yours while testing.

AssetFare is non-custodial: the service must never request a private key or seed
phrase, sign a caller transaction, or submit one on the caller's behalf. Treat
any behavior that violates that boundary as security-sensitive.

