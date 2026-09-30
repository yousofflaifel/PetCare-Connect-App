# PetCare Connect

A mobile-first pet care platform built with **Adalo** to bring pet adoption, lost and found services, and veterinary consultations into one application.

PetCare Connect is designed for three main user groups: pet owners and animal lovers, veterinary professionals, and administrators. The platform combines community-based pet services with role-based access and moderation features.

## Live App

**Adalo Preview:**  
https://previewer.adalo.com/44a12654-4700-45f6-ada0-81352c6cf143?target=0qsnerdnovncdp4aj23ajus12&params=%7B%7D

> The preview link opens the current Adalo version of the application.

## Project Overview

PetCare Connect was developed as a mobile-first solution for common pet-care needs that are often handled through separate platforms.

The application focuses on three core services:

- Pet adoption
- Lost and found pets
- Veterinary consultations

The system also includes user profiles, role-based access, veterinary verification, filtering, notifications, and administrative moderation.

## Main Features

### Pet Adoption

Users can browse available pets for adoption and use filters to find suitable listings.

Adoption listings can include:

- Pet name
- Breed
- Gender
- Color
- City
- Pet image

The filtering system is designed around factors such as breed, gender, color, and city.

### Lost and Found

Users can create posts for lost or found pets and use the platform to help identify potential matches.

The system can support the process from reporting a pet to identifying a possible match and resolving the case.

### Veterinary Consultations

Users can submit veterinary questions and inquiries.

Verified veterinary professionals can respond to medical inquiries, providing a dedicated communication channel between users and veterinary professionals.

### User Profiles

Users can register, log in, and manage their profiles.

The system supports different account roles:

```text
Normal User
Veterinary Professional
Administrator
```

### Veterinary Verification

Veterinary professionals are required to go through an administrator verification process before being treated as verified professionals.

This helps establish trust and reduces the risk of unverified users providing veterinary advice.

### Notifications

The application is designed to provide notifications for important activities such as:

- Veterinary responses
- Adoption interest
- Lost and found updates
- Administrative updates

### Administration

Administrators can oversee the platform and manage:

- Veterinary verification
- User-generated posts
- Reported content
- User moderation

## Technology Stack

### Application Platform

- **Adalo**
- Low-code application development
- Mobile-first interface
- Cross-platform deployment

### Database

Adalo collections are used to manage application data such as:

- Users
- Pets
- Adoption posts
- Lost and found posts
- Medical inquiries
- Veterinary responses
- Reports

### Integrations

The project was designed to support integrations with external services when required, including:

- Google Maps API for future location/GPS functionality
- Zapier for automation
- Stripe or PayPal for future veterinary consultation payments

## User Roles

| Role | Main Responsibilities |
|---|---|
| Normal User | Manage profile, browse pets, create posts, submit inquiries, and interact with the platform |
| Veterinary Professional | Maintain a professional profile and respond to medical inquiries after verification |
| Administrator | Verify veterinary accounts, moderate content, and manage reports |

## Application Flow

A typical user journey is:

```text
Register / Login
       |
       v
   User Profile
       |
       +-------------------+
       |                   |
       v                   v
Pet Adoption        Lost & Found
       |                   |
       |                   v
       |              Pet Reports
       |
       v
Search & Filters

User
  |
  v
Medical Inquiry
  |
  v
Verified Veterinary Professional
  |
  v
Veterinary Response
  |
  v
Notification
```

## How to Use

### For Normal Users

1. Open the Adalo preview.
2. Register or log in.
3. Complete your profile.
4. Browse available adoption posts.
5. Use filters to search for suitable pets.
6. Create an adoption, lost, or found post when needed.
7. Submit a veterinary inquiry.
8. Check notifications for responses and updates.

### For Veterinary Professionals

1. Register as a veterinary professional.
2. Provide the required professional information.
3. Wait for administrator verification.
4. Access available medical inquiries after approval.
5. Respond to users' veterinary questions.

### For Administrators

1. Log in using an administrator account.
2. Review veterinary registration requests.
3. Verify or reject veterinary professionals.
4. Monitor user-generated content.
5. Review reported posts or users.
6. Remove content that violates platform guidelines.

## Design and Requirements

The application was designed around several key requirements:

- Simple and intuitive user interface
- Mobile-first experience
- Role-based access control
- Secure authentication
- Adoption search and filtering
- Veterinary verification
- Lost and found functionality
- Notifications
- Content moderation
- Scalability for future services

The project requirements specifically identify normal users, veterinary professionals, and administrators as the three main user groups.

## Future Improvements

The project can be extended with additional functionality such as:

- GPS-based pet care centers
- Location-based lost-pet matching
- Pet community forums
- Pet marketplace
- Veterinary consultation payments
- Pet food and accessory purchases
- More advanced notifications
- Additional reporting and analytics

Potential integrations include Google Maps for location services and Stripe or PayPal for payment processing.

## Development Approach

The project was developed as part of a Software Development Lifecycle project. The requirements, system analysis, design, and implementation were used to translate the proposed PetCare Connect solution into a working Adalo application.

The use of Adalo provides a low-code approach that allows the application to be developed without building the entire mobile application from scratch using traditional programming.

## Learning Outcomes

This project provided practical experience with:

- Low-code application development
- Mobile-first application design
- Requirements analysis
- Software design
- User experience design
- Role-based access control
- Database collections
- Authentication
- Search and filtering
- Notifications
- Content moderation
- Application prototyping
- Software Development Lifecycle concepts

## Project Status

**Platform:** Adalo  
**Application Type:** Mobile-first pet care platform  
**Status:** University project / functional prototype

## Author

**Yousof Flaifel**

Data Science & AI Student  
Al Hussein Technical University (HTU)

---

University Software Development Project
