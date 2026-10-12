# MetroSense City — Audit Trail Design

## 1. Purpose

The audit trail is designed to maintain a traceable history
of inspection activities, record corrections, and report versions.

It supports accountability and helps authorized users review
changes made during the inspection process.

## 2. Record Editing Policy

The proposed editing policy is:

- Draft observations may be edited by authorized users.
- Changes to submitted records should include a reason.
- Approved reports should not be silently overwritten.
- Corrections should create a new report version.
- Previous versions should remain available for review.
- Access to records should depend on user permissions.

## 3. Audit Event Information

Each audit event may record:

- Event ID
- Inspection or report ID
- User ID and role
- Action performed
- Previous value
- New value
- Reason for the change
- Date and timestamp
- Report version
- Approval status
- Integrity verification reference

## 4. Example Workflow

1. An inspector creates a draft inspection record.
2. The inspector enters test observations.
3. The record is submitted for review.
4. An authorized reviewer reviews the record.
5. The report is approved, if requirements are satisfied.
6. A subsequent correction creates a new version.
7. The original version remains available for traceability.

## 5. Security Considerations

- Only authorized users should modify records.
- Audit events should be protected against unauthorized changes.
- Sensitive information should not appear in public logs.
- Report versions should be linked to their associated records.
- Important actions should be attributable to authenticated users.

## 6. Implementation Status

This document describes the intended design.

The actual level of protection depends on the implemented
authentication, authorization, storage, and version-control
mechanisms.

An audit trail should only be described as immutable when
appropriate technical protections have been implemented
and verified.
