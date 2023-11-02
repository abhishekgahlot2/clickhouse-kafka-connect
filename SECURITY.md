# Security Policy

## Security Announcements
Security fixes will be announced by posting them in the [security changelog](https://clickhouse.com/docs/en/whats-new/security-changelog/).

## Scope and Supported Versions

Generally the latest release contains the most recent security updates - we increment version numbers based on all changes, including security fixes. 

Where applicable we might backport, but generally the latest is the most secure.

## Reporting a Vulnerability

We're extremely grateful for security researchers and users that report vulnerabilities to the ClickHouse Open Source Community. All reports are thoroughly investigated by developers.

To report a potential vulnerability in ClickHouse please send the details about it to [security@clickhouse.com](mailto:security@clickhouse.com). We do not offer any financial rewards for reporting issues to us using this method. Alternatively, you can also submit your findings through our public bug bounty program hosted by [Bugcrowd](https://bugcrowd.com/clickhouse) and be rewarded for it as per the program scope and rules of engagement.

### When Should I Report a Vulnerability?

- You think you discovered a potential security vulnerability in ClickHouse
- You are unsure how a vulnerability affects ClickHouse

### When Should I NOT Report a Vulnerability?

- You need help tuning ClickHouse components for security
- You need help applying security related updates
- Your issue is not security related

## Security Vulnerability Response

Each report is acknowledged and analyzed by ClickHouse maintainers within 5 working days.
As the security issue moves from triage, to identified fix, to release planning we will keep the reporter updated.

## Public Disclosure Timing

A public disclosure date is negotiated by the ClickHouse maintainers and the bug submitter. We prefer to fully disclose the bug as soon as possible once a user mitigation is available. It is reasonable to delay disclosure when the bug or the fix is not yet fully understood, the solution is not well-tested, or for vendor coordination. The timeframe for disclosure is from immediate (especially if it's already publicly known) to 90 days. For a vulnerability with a straightforward mitigation, we expect the report date to disclosure date to be on the order of 7 days.