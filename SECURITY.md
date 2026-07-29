# Security policy

## Reporting a vulnerability

If you believe you have found a security issue in Overcaption, its update mechanism, or its services (overcaption.com, api.overcaption.com), please report it privately rather than opening a public issue.

Email: **security@overcaption.com**

You will get a reply within a few days. Please include steps to reproduce and the app version. If the report is valid, the fix ships in the next release and you will be credited in the release notes if you want to be.

## Scope notes

- Overcaption processes files locally. There is no server-side account system or user data store: nothing to breach beyond the machine it runs on.
- The auto-updater fetches signed builds over HTTPS; both the macOS and Windows builds are code-signed. Reports about the update path are especially welcome.
