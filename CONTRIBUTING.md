# Contributing to AssetFare public repositories

AssetFare welcomes narrowly scoped, reviewable improvements to its public
adapters, verifier, documentation, tests, and reproducible contract evidence.

Before opening a pull request:

1. Open or reference an issue for behavior-changing work.
2. Preserve the non-custodial boundary: no private-key intake, server signing,
   server submission, hidden approval, or automatic execution.
3. Add fail-closed tests for parsing, amount, fee, recipient, target, deadline,
   and network-boundary changes.
4. Keep claims factual. Project-authored tests are not independent audits and a
   quote is not a guarantee of execution or price superiority.
5. Never commit credentials, wallet secrets, signed transactions, production
   bearer capabilities, or personal data.
6. Run the repository's documented formatting, test, audit, and pack commands.

Security reports belong in the private channel documented in `SECURITY.md`, not
in a public pull request or issue.

