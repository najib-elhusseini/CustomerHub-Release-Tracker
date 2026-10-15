# CustomerHub Release Tracker

## Purpose

The purpose of this repository is to maintain a centralized record of all CustomerHub changes delivered across environments.

This tracker serves as the single source of truth for:

- Features
- Enhancements
- Bug fixes
- Hotfixes
- Database changes
- Deployment information

The goal is to improve visibility, deployment coordination, and historical traceability for all CustomerHub releases.

---

## Environments

| Environment | Description |
|-------------|-------------|
| DEV | Development environment |
| TST | Testing/UAT environment |
| PROD | Production environment |

---

## Release Process

1. Complete development and testing in DEV.
2. Record all changes in the release tracker.
3. Deploy to TST.
4. Validate functionality.
5. Deploy approved changes to PROD.
6. Update deployment status and release notes.

---

## Change Entry Template

### Change ID

CH-YYYY-MM-DD-001

### Title

Short description of the change.

### Type

- Feature
- Enhancement
- Bug Fix
- Hotfix
- Configuration
- Data Fix

### Description

Detailed summary of the implemented change.

### Related Work Item

- Jira:
- User Story:
- Incident:

### Author

GitHub Username

### Deployment Status

| Environment | Status | Date |
|-------------|--------|------|
| DEV | ✅ | YYYY-MM-DD |
| TST | ⬜ | |
| PROD | ⬜ | |

### Notes

Additional deployment notes, testing observations, or known limitations.

---

## Release Notes Template

# Release YYYY.MM.DD

## Features

- Item 1
- Item 2

## Enhancements

- Item 1
- Item 2

## Bug Fixes

- Item 1
- Item 2

## Hotfixes

- Item 1
- Item 2

## Deployment Information

| Environment | Date | By |
|-------------|------|----|
| TST | YYYY-MM-DD | Name |
| PROD | YYYY-MM-DD | Name |

## Remarks

Any relevant deployment comments or follow-up actions.
