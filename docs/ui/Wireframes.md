# EA Inventory System

## Wireframes MVP 0.1

**Version:** 1.0  
**Status:** Approved  
**Last Updated:** June 2026

---

# Overview

This document contains the initial low-fidelity wireframes for the MVP 0.1.

The purpose of these wireframes is to validate navigation, workflows and screen structure before development begins.

---

# Navigation Structure
```text
+----------------------+
| EA Inventory System  |
+----------------------+
| Dashboard            |
| Company              |
| Branches             |
| Categories           |
| Inventory            |
+----------------------+
```
---

# Dashboard
```text
+------------------------------------------------------+
| Dashboard                                            |
+------------------------------------------------------+

+-----------+  +-----------+  +-----------+  +---------+
| Total     |  | Available |  | In Use    |  | Maint.  |
| Assets    |  |           |  |           |  |         |
+-----------+  +-----------+  +-----------+  +---------+

+------------------------------------------------------+
| Recent Assets                                        |
+------------------------------------------------------+
| Code  | Name    | Category | Status                  |
|------------------------------------------------------|
| EA001 | Speaker | Audio    | Available               |
| EA002 | Mixer   | Audio    | In Use                  |
+------------------------------------------------------+
```
---

# Company
```text
+------------------------------------------------------+
| Company                                              |
+------------------------------------------------------+

Name:
[________________________]

Email:
[________________________]

Phone:
[________________________]

Address:
[________________________]

[Save]
```
---

# Branches
```text
+------------------------------------------------------+
| Branches                               [New Branch]  |
+------------------------------------------------------+

+------------------------------------------------------+
| Name         | Address             | Actions         |
|------------------------------------------------------|
| Main Office  | Downtown            | Edit            |
| Warehouse    | Industrial Area     | Edit            |
+------------------------------------------------------+
```
---

# Categories
```text
+------------------------------------------------------+
| Categories                           [New Category]  |
+------------------------------------------------------+

+------------------------------------------------------+
| Name          | Description        | Actions         |
|------------------------------------------------------|
| Audio         | Sound Equipment    | Edit            |
| Lighting      | Event Lighting     | Edit            |
+------------------------------------------------------+
```
---

# Inventory
```text
+------------------------------------------------------+
| Inventory                           [New Asset]      |
+------------------------------------------------------+

Search:
[_____________________]

+------------------------------------------------------+
| Code | Name   | Category | Branch | Status          |
|------------------------------------------------------|
| EA001| Speaker| Audio    | Main   | Available       |
| EA002| Mixer  | Audio    | Main   | In Use          |
+------------------------------------------------------+
```
---
