# EA Inventory System

## MVP Scope Document

**Version:** 1.0
**Status:** Approved
**Last Updated:** June 2026

---

# 1. Purpose

This document defines the scope of the Minimum Viable Product (MVP) for EA Inventory System.

The purpose of the MVP is to validate the core business value of the platform by providing a configurable inventory management solution for small service-based businesses.

The MVP is intended for internal validation, stakeholder feedback and process discovery before investing in more advanced functionality.

---

# 2. MVP Objective

Develop a functional web application that allows a business to organize, manage and visualize its inventory through a centralized and configurable platform.

The MVP will focus exclusively on inventory management and organizational structure.

---

# 3. Business Hypothesis

Small service-based businesses can improve inventory control, asset visibility and operational organization through a configurable inventory management platform.

If the MVP successfully improves visibility and organization of assets, additional operational modules can be developed in future releases.

---

# 4. In Scope (Included Features)

The following features are included in MVP 0.1.

## 4.1 Company Configuration

The system shall allow:

* Create a company.
* Edit company information.
* View company information.

Examples of company information:

* Name
* Contact information
* Address
* Logo (future enhancement)

---

## 4.2 Branch Management

The system shall allow:

* Create branches.
* Edit branches.
* View branches.

Each branch belongs to a company.

---

## 4.3 Category Management

The system shall allow:

* Create categories.
* Edit categories.
* View categories.

Examples:

* Audio
* Lighting
* Video
* Accessories

Categories must be configurable.

---

## 4.4 Asset Management

The system shall allow:

* Register assets.
* Edit assets.
* View assets.
* Search assets.

Examples:

* Speakers
* Microphones
* Mixers
* Lighting fixtures
* Structures
* Cables

---

## 4.5 Asset Status Management

Assets shall support the following statuses:

* Available
* In Use
* Maintenance

Status values should be configurable in future versions.

---

## 4.6 Dashboard

The system shall display basic inventory indicators:

* Total assets
* Available assets
* Assets in use
* Assets under maintenance

The dashboard is intended to provide a quick operational overview.

---

# 5. Out of Scope (Excluded Features)

The following features are intentionally excluded from MVP 0.1.

---

## 5.1 User Management

Excluded until MVP 0.2.

Includes:

* User accounts
* Login
* Authentication
* Authorization
* Roles and permissions

Reason:

The MVP is intended for validation and demonstration purposes.

---

## 5.2 Event Management

Excluded until MVP 0.3.

Includes:

* Event creation
* Event scheduling
* Asset assignment to events

Reason:

Business processes must first be validated with stakeholders.

---

## 5.3 Inventory Movements

Excluded until MVP 0.3.

Includes:

* Check-in
* Check-out
* Transfers
* Movement history

Reason:

Depends on event and operational workflows.

---

## 5.4 Reporting

Excluded until Version 1.0.

Includes:

* PDF exports
* Excel exports
* Advanced reports

Reason:

Reporting does not contribute to initial business validation.

---

## 5.5 QR Code Integration

Excluded from current roadmap planning.

Reason:

Requires operational validation before implementation.

---

## 5.6 Notifications

Excluded from MVP.

Includes:

* Email notifications
* Alerts
* Reminders

Reason:

Not required to validate core inventory functionality.

---

# 6. Success Criteria

The MVP will be considered successful if:

* Inventory can be registered and maintained digitally.
* Stakeholders can locate inventory information quickly.
* Assets can be categorized effectively.
* Branches can be managed within the platform.
* The owner can review inventory indicators through the dashboard.
* Feedback validates the usefulness of the platform.

---

# 7. MVP Completion Criteria

MVP 0.1 will be considered complete when:

* Company management is functional.
* Branch management is functional.
* Category management is functional.
* Asset management is functional.
* Dashboard metrics are functional.
* The application can be demonstrated to stakeholders.

---

# 8. Future Releases

## MVP 0.2

Focus:

User Management and Security

Includes:

* Authentication
* User Accounts
* Roles and Permissions

---

## MVP 0.3

Focus:

Operational Management

Includes:

* Events
* Asset Assignment
* Inventory Movements

---

## Version 1.0

Focus:

Production Readiness

Includes:

* Reports
* Exports
* Audit Features
* UX Improvements

---

# 9. Scope Control Rule

Any functionality not explicitly included in the "In Scope" section of this document shall be considered outside the scope of MVP 0.1 and must be evaluated through the product backlog before being added to the project.

This rule exists to prevent uncontrolled scope growth and maintain focus on delivering business value.
