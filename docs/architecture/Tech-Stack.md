# EA Inventory System

## Database Blueprint

**Version:** 1.0
**Status:** Approved
**Last Updated:** June 2026

---

# 1. Purpose

This document defines the initial database design required for MVP 0.1.

The design focuses exclusively on inventory management functionality.

---

# 2. Design Principles

- Simplicity before complexity.
- Support future expansion.
- Avoid premature optimization.
- Model only MVP requirements.

---

# 3. Core Entities

## Company

Represents a business using the platform.

Attributes:

- id
- name
- email
- phone
- address
- created_at

---

## Branch

Represents a physical location belonging to a company.

Attributes:

- id
- company_id
- name
- address
- created_at

Relationship:

One Company can have many Branches.

---

## Category

Represents an asset classification.

Examples:

- Audio
- Lighting
- Video
- Accessories

Attributes:

- id
- name
- description

---

## Asset

Represents an inventory item.

Attributes:

- id
- branch_id
- category_id
- code
- name
- description
- status
- created_at

Relationship:

One Branch can have many Assets.

One Category can contain many Assets.

---

# 4. Entity Relationships

Company
│
└── Branch
│
└── Asset
│
├── Category

---

# 5. Asset Status Values

The MVP supports the following statuses:

- Available
- In Use
- Maintenance

Future versions may support configurable statuses.

---

# 6. Excluded Entities

The following entities are intentionally excluded from MVP 0.1:

- Users
- Roles
- Permissions
- Events
- Inventory Movements
- Reports
- QR Tracking

These entities belong to future releases.
