# Smart Restaurant System - Documentation Directory

## Overview

This workspace contains the Smart Restaurant System, a multi-application platform consisting of four interconnected repositories. This document serves as the central navigation guide to all project documentation.

The Github organization hosting this workspace is: https://github.com/K23-Smart-Restaurant

The demo video can be found on Youtube: https://youtu.be/l-kez8bRPS0

## Primary Documentation

The comprehensive system documentation is located in the **smart-restaurant-root** repository:

**[Smart Restaurant Root - Main README](smart-restaurant-root/README.md)**

This is the primary reference document containing complete system information, setup instructions, architecture, and operational guides.

### General Documentation

The [smart-restaurant-root/docs/general](smart-restaurant-root/docs/general/) directory contains essential system-wide documentation:

- [ARCHITECTURE.md](smart-restaurant-root/docs/general/ARCHITECTURE.md) - System architecture and design principles
- [DATABASE_DESIGN.md](smart-restaurant-root/docs/general/DATABASE_DESIGN.md) - Database schema and relationships
- [DATABASE_SETUP.md](smart-restaurant-root/docs/general/DATABASE_SETUP.md) - Database installation and configuration
- [SETUP.md](smart-restaurant-root/docs/general/SETUP.md) - System setup and deployment instructions
- [USER_GUIDE.md](smart-restaurant-root/docs/general/USER_GUIDE.md) - User guide and operational procedures
- [CICD.md](smart-restaurant-root/docs/general/CICD.md) - Continuous integration and deployment guidelines

## Repository Structure

The workspace is organized into four primary directories:

### 1. Smart Restaurant Root

**Directory**: [smart-restaurant-root](smart-restaurant-root/)

**Purpose**: Shared database schema, migrations, Docker orchestration, and system-wide documentation

**Documentation**: [smart-restaurant-root/docs](smart-restaurant-root/docs/)

### 2. Smart Restaurant Admin

**Directory**: [smart-restaurant-admin](smart-restaurant-admin/)

**Purpose**: Restaurant management and kitchen display system

**Documentation**: [smart-restaurant-admin/docs](smart-restaurant-admin/docs/)

Key documentation files:

- [API_REFERENCE.md](smart-restaurant-admin/docs/API_REFERENCE.md) - Admin API endpoints
- [ARCHITECTURE.md](smart-restaurant-admin/docs/ARCHITECTURE.md) - Application architecture
- [DATABASE_DESIGN.md](smart-restaurant-admin/docs/DATABASE_DESIGN.md) - Database schema reference
- [SETUP.md](smart-restaurant-admin/docs/SETUP.md) - Installation guide
- [USER_GUIDE.md](smart-restaurant-admin/docs/USER_GUIDE.md) - Admin application user guide

### 3. Smart Restaurant Customer

**Directory**: [smart-restaurant-customer](smart-restaurant-customer/)

**Purpose**: Customer-facing QR ordering and payment application

**Documentation**: [smart-restaurant-customer/docs](smart-restaurant-customer/docs/)

Key documentation files:

- [API_REFERENCE.md](smart-restaurant-customer/docs/API_REFERENCE.md) - Customer API endpoints
- [ARCHITECTURE.md](smart-restaurant-customer/docs/ARCHITECTURE.md) - Application architecture
- [DATABASE_DESIGN.md](smart-restaurant-customer/docs/DATABASE_DESIGN.md) - Database schema reference
- [SETUP.md](smart-restaurant-customer/docs/SETUP.md) - Installation guide
- [USER_GUIDE.md](smart-restaurant-customer/docs/USER_GUIDE.md) - Customer application user guide

### 4. Smart Restaurant Super Admin

**Directory**: [smart-restaurant-super-admin](smart-restaurant-super-admin/)

**Purpose**: Platform administration and multi-tenant management

**Documentation**: [smart-restaurant-super-admin/docs](smart-restaurant-super-admin/docs/)

Key documentation files:

- [API_REFERENCE.md](smart-restaurant-super-admin/docs/API_REFERENCE.md) - SuperAdmin API endpoints
- [ARCHITECTURE.md](smart-restaurant-super-admin/docs/ARCHITECTURE.md) - Application architecture
- [DATABASE_DESIGN.md](smart-restaurant-super-admin/docs/DATABASE_DESIGN.md) - Database schema reference
- [SETUP.md](smart-restaurant-super-admin/docs/SETUP.md) - Installation guide
- [USER_GUIDE.md](smart-restaurant-super-admin/docs/USER_GUIDE.md) - SuperAdmin user guide

## Repository Statistics

Development activity and code metrics for each application:

- [Admin Statistics](smart-restaurant-root/docs/stats/admin/) - Commit history and code counts
- [Customer Statistics](smart-restaurant-root/docs/stats/customer/) - Commit history and code counts
- [SuperAdmin Statistics](smart-restaurant-root/docs/stats/super-admin/) - Commit history and code counts

## Navigation Guide

### For System Setup and Deployment

Begin with [smart-restaurant-root/README.md](smart-restaurant-root/README.md) and refer to [SETUP.md](smart-restaurant-root/docs/general/SETUP.md) for comprehensive setup instructions.

### For Architecture and Design

Consult [ARCHITECTURE.md](smart-restaurant-root/docs/general/ARCHITECTURE.md) for system-wide architecture and individual application architecture documents in their respective `docs/` folders.

### For Database Information

Reference [DATABASE_DESIGN.md](smart-restaurant-root/docs/general/DATABASE_DESIGN.md) for the complete database schema and [DATABASE_SETUP.md](smart-restaurant-root/docs/general/DATABASE_SETUP.md) for installation procedures.

### For API Integration

Refer to the `API_REFERENCE.md` file in each application's documentation folder for endpoint specifications and usage examples.

### For End Users

Access the `USER_GUIDE.md` in the relevant application's documentation folder for operational instructions.

---

**Last Updated**: January 19, 2026
