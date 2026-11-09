# SpamBack Custody Dummy

## Purpose
This repository is dedicated exclusively to isolated, dummy-only testing of the SpamBack AI encrypted credential-handoff system.

## Security Boundaries
- No production credentials or private signing keys.
- No private SpamBack AI application source code.
- No real Apple certificates or provisioning profiles.
- No access to the production Release Controller.
- No production secrets in logs, artifacts, or repository files.
- No additional paid spending.

## Test Environment
Environment: Dummy-Qualification

Required reviewer: azodomain-svg

Prevent self-review: Enabled

Administrator bypass: Disabled

Deployment branch: main only

## Authorization Requirements
All workflow installations, privileged permissions, token creation, and live test executions require separate authorization.

Production credential transfers, application signing, Apple uploads, and production modifications are prohibited.

## Current Status
Initial isolated repository setup.

No production credentials authorized.

Live dummy qualification pending separate approval.
