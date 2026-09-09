<div align="center">

# Talabyaat

### B2B E-commerce Platform

**Wholesale Commerce · Business Platform · Mobile Applications**

<br>

<img src="https://img.shields.io/badge/Status-Private_Client_Project-111827?style=for-the-badge">
<img src="https://img.shields.io/badge/Platform-Web_%26_Mobile-2563EB?style=for-the-badge">
<img src="https://img.shields.io/badge/Backend-Laravel-EF4444?style=for-the-badge">
<img src="https://img.shields.io/badge/Mobile-Flutter-0EA5E9?style=for-the-badge">

</div>

---

## Overview

**Talabyaat** is a B2B e-commerce platform designed to help shops and businesses discover wholesale products, compare available offers, and manage their purchasing activity through a unified digital platform.

The platform connects businesses with suppliers and wholesalers while supporting different commercial workflows across web and mobile.

---

## The Business Goal

The goal was to transform traditional wholesale purchasing into a more organized digital experience.

The platform was designed to help businesses:

* Discover wholesale products
* View prices and required quantities
* Explore offers from multiple suppliers
* Create and manage purchase orders
* Follow order status
* Access their purchasing experience from web and mobile

---

## What I Built

### Web Platform

* Product catalog and categories
* Wholesale product browsing
* Search and discovery
* Cart and order workflows
* Business-focused purchasing experience
* Responsive interfaces

### Administration

* Product management
* Order management
* User and role management
* Business workflows
* Operational controls
* Platform administration

### Mobile Applications

* Flutter mobile applications
* Secure API communication
* Authentication
* Product browsing
* Cart and ordering
* Push notifications

### Backend

* Laravel application
* MySQL database
* REST APIs
* Authentication and authorization
* Background jobs
* Notification services
* Production deployment

---

## Technology Stack

| Layer          | Technologies                        |
| -------------- | ----------------------------------- |
| Backend        | Laravel, PHP                        |
| Database       | MySQL                               |
| Mobile         | Flutter, Dart                       |
| APIs           | REST API                            |
| Notifications  | Firebase Cloud Messaging            |
| Infrastructure | Linux, Git, Cloudflare              |
| Security       | Authentication, Roles & Permissions |

---

## Architecture

```text
                    ┌─────────────────────┐
                    │     Web Platform    │
                    └──────────┬──────────┘
                               │
                               │
                    ┌──────────▼──────────┐
                    │      REST APIs      │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
      ┌───────▼───────┐ ┌──────▼──────┐ ┌──────▼──────┐
      │    Flutter    │ │   Laravel   │ │    Admin    │
      │     Apps      │ │   Backend   │ │   System    │
      └───────────────┘ └──────┬──────┘ └─────────────┘
                               │
                         ┌─────▼─────┐
                         │   MySQL   │
                         └───────────┘
```

---

## My Role

I worked on the technical architecture and development of the platform, including:

* Backend development
* API development
* E-commerce workflows
* Database design
* Mobile application development
* Admin systems
* Notifications
* Authentication and permissions
* Production deployment

---

## Key Challenges

### Multi-role Business Logic

The platform needed to support different users and business workflows without making the system difficult to maintain.

### Wholesale Purchasing

Wholesale products often depend on pricing and minimum quantities, which required business rules different from a standard consumer store.

### Web & Mobile Consistency

The web platform and mobile applications needed to work with the same backend and business logic.

### Production Reliability

The application required secure deployment, background processing, notifications, and reliable communication between the mobile applications and backend.

---

## Result

The result is a complete B2B commerce platform that brings wholesale products, businesses, suppliers, orders, administration, and mobile access together in one system.

The platform is designed to make wholesale purchasing more organized, accessible, and efficient.

---

## Project Privacy

This is a **private client project**.

The production source code, business data, credentials, and internal implementation details are not publicly available due to client confidentiality.

This repository is a **public case study only**.

---

<div align="center">

### Talabyaat

**B2B E-commerce • Laravel • Flutter • REST APIs**

</div>
