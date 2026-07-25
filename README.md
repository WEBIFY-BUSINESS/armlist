<p align="center">
  <img src="./assets/cover.png" width="100%" alt="ArmList marketplace platform">
</p>

# ArmList

### Marketplace platform built for Armenia.

ArmList is a full-scale marketplace designed to connect buyers and sellers through a modern, structured and scalable platform.

<p>
  <a href="https://armlist.am"><strong>Visit Live Product</strong></a>
  ·
  <a href="https://webifybusiness.com"><strong>Built by Webify</strong></a>
</p>

> This repository is a public product overview.  
> The commercial source code and private infrastructure remain confidential.

---

## Overview

ArmList was designed as a complete marketplace ecosystem rather than a basic listings website.

The platform includes user accounts, product publishing, category-based search, premium placements, messaging, moderation, administration and automated notifications.

The product was built with a strong focus on usability, scalability and long-term business growth.

---

## Core Features

- User registration and authentication
- Product listings with categories and subcategories
- Image uploads and structured product data
- Premium and highlighted listings
- User profiles and seller information
- Internal messaging system
- Product moderation
- Reports and blocking
- Admin dashboard
- Email notifications
- Listing expiration management
- Account and session management
- Responsive interface

---

## Product Areas

### Marketplace

Users can publish, browse and manage listings across multiple categories.

### Messaging

The internal messaging system allows buyers and sellers to communicate directly inside the platform.

### Premium Placement

Listings can receive additional visibility through paid placement options and expiration-based promotion logic.

### Administration

The administration system supports moderation, users, listings, reports and platform management.

---

## Technology

### Frontend

- HTML
- CSS
- JavaScript

### Backend

- PHP
- MySQL

### Infrastructure

- Apache
- cPanel
- Cron Jobs
- PHPMailer
- Git

---

## Architecture

```mermaid
flowchart LR
    User[User] --> Web[Responsive Web Application]
    Web --> Backend[PHP Backend]
    Backend --> Database[(MySQL Database)]
    Backend --> Email[Email Notifications]
    Backend --> Storage[Image Storage]
    Admin[Admin] --> Dashboard[Admin Dashboard]
    Dashboard --> Backend
    Cron[Cron Jobs] --> Backend
```

---

## My Role

- Product architecture
- Business logic
- Database design
- Backend development
- Frontend development
- Authentication and sessions
- Messaging system
- Admin dashboard
- Email automation
- Deployment
- Product iteration

---

## Gallery

<p align="center">
  <img src="./assets/homepage.png" width="100%" alt="ArmList homepage">
</p>

<table>
<tr>
<td width="50%">
  <img src="./assets/product-page.png" width="100%" alt="ArmList product page">
</td>
<td width="50%">
  <img src="./assets/dashboard.png" width="100%" alt="ArmList dashboard">
</td>
</tr>
<tr>
<td width="50%">
  <img src="./assets/chat.png" width="100%" alt="ArmList messaging system">
</td>
<td width="50%">
  <img src="./assets/admin.png" width="100%" alt="ArmList admin dashboard">
</td>
</tr>
</table>

---

## Status

**Production**

The platform is live and available at:

### https://armlist.am

---

<p align="center">
  Built by <a href="https://webifybusiness.com"><strong>Webify</strong></a>
</p>
