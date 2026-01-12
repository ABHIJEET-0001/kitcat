##🔐 Security Policy
Reporting Security Vulnerabilities

Security-related issues must never be reported through GitHub issues or pull requests.

If you discover any vulnerability, data-integrity issue, or unsafe behavior, report it privately by email:

#📧 zeeshanalavi1@gmail.com

This applies to (but is not limited to):

## Repository corruption

Data loss or silent failure

Index, object, or reference inconsistencies

Unsafe filesystem operations

Checkout, reset, or recovery behaviors that overwrite user data

Crashes that leave repositories in an unrecoverable state

Any behavior that could compromise .git or .kitcat compatibility

What Is Considered a Security Issue?

The following are classified as security vulnerabilities, not standard bugs:

Silent or partial corruption of .kitcat repositories

Incorrect or unsafe handling of user data on disk

Files being overwritten without explicit user intent

Unsafe defaults that can destroy or modify local data

Index or object mismatches that break repositories

Crashes during write operations that leave incomplete state

Any defect that could result in permanent data loss

If you are unsure whether an issue is security-related, treat it as one and report it privately.

## How to Submit a Security Report

Your email must include the following information:

# 1. Summary

A brief description of the issue.

# 2. Affected Area

Specify what is impacted:

Commands

Files or directories

Storage, index, or object layers

Branch (e.g., main, develop)

# 3. Reproduction Steps

Clear, minimal steps to reproduce the issue, including:

Commands executed

Files modified or created

# 4. Impact

Describe what could go wrong:

Data loss

Repository corruption

Incorrect behavior

Crashes or denial of service

# 5. Environment

Include:

Operating System

KitCat version or commit hash

Go version

Incomplete reports may not be processed.

What Not to Do

To protect users and repository integrity:

❌ Do not open public GitHub issues for security problems

❌ Do not submit pull requests attempting to fix security issues

❌ Do not discuss vulnerabilities publicly before maintainers respond

❌ Do not send large archives or binaries without permission

Security fixes require coordinated review and controlled disclosure.

Vulnerability Handling & Disclosure

Once a report is received:

We will acknowledge the report

We will assess the severity and impact

Fixes will be developed privately when required

Public disclosure (if any) will occur only after a fix is available

There is no guaranteed response time, but critical issues are prioritized.

Relationship to Contributions

Security issues are not standard contributions.

Type	Where to Report
Normal bugs	GitHub Issues & Pull Requests
Security issues	Private email only
Security-sensitive PRs	Must be coordinated in advance

Pull requests that modify security-critical code without prior approval will be rejected.

Final Note

If an issue involves .git, .kitcat, object storage, index files, or checkout/reset behavior, assume it is security-sensitive and report it privately.

When in doubt: email first.
