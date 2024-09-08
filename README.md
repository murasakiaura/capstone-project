# Project Title

Adopt an Animal: A Global Platform for Animal Adoption

## Overview

The app will allow users to browse and adopt animals from around the world, with options for physical adoption from local shelters and virtual adoption for endangered species. It will connect animal lovers with shelters, zoos, and conservation efforts, helping to protect wildlife and rescue animals.


### Problem

There are many animals in need of adoption, whether through local shelters or international conservation programs. However, there is no centralised platform that connects users with both physical and virtual adoption options across the globe. Existing platforms are fragmented, and users may have difficulty navigating different processes depending on the country or organization. Additionally, raising awareness for endangered species and funding their conservation is crucial.

### User Profile

Who will use your app?

Target Audience:
Animal lovers interested in adopting local pets or supporting conservation through virtual adoptions.
Conservation organizations and local shelters seeking exposure and donations.
General users interested in tracking the impact of their donations or adoptions.
How will they use it?
Users will browse available animals, learn about their background and needs, and complete the adoption process directly through the app. They will receive updates about their adopted animal and have access to real-time notifications.

Special Considerations:

Global User Base: The app will need to support multiple languages and currencies.
Legal Compliance: Adopting animals internationally requires strict adherence to adoption laws across different countries.


### Features

Browse Animals: Users can browse a list of animals categorized by region, species, or shelter.
Adopt and Donate: Users can initiate physical adoptions or sponsor virtual adoptions for endangered species with the ability to donate funds.
Track Adoption: Users receive updates and track their adopted animals with photos, videos, and progress reports.
User Profiles: Personalized profiles to track donations, adoptions, and interaction with the platform.
Shelter/Organization Portal: Partner organizations can list animals for adoption and provide updates about their status.
Multilingual & Multi-currency Support: Support for users across various regions with proper translations and financial processing.
Merchandise: Users are able to purphase merchandise of all animals including the ones they adopted from the website.

## Implementation

### Tech Stack
Frontend: React.js.
Backend: Node.js and mySQL for the database.


### APIs

Animal Information: Use APIs from organisations like Petfinder, World Wildlife Fund (WWF), and other wildlife conservation databases for information on species and available animals.

### Sitemap

Home Page: Overview of the platform and featured animals for adoption.
Browse Animals: A searchable and filterable list of animals.
Animal Profile Page: Detailed information on the selected animal with an "Adopt" button.
User Profile: A user’s adoption history, donations, and account settings.
Shelter/Organisation Dashboard: Interface for shelters and organizations to manage their listings.
Merchandise: Users are able to purphase merchandise of all animals including the ones they adopted from the website.
Contact Us: Support page for users to get help or ask questions.

### Mockups

TBC

### Data

Entities:
Animals: Species, age, adoption status, photos/videos, location.
Users: Personal details, adoption history, donation records.
Organisations/Shelters: Name, location, animals listed, adoption status.
Relationships:
Users can adopt many animals.
Animals can belong to only one shelter/organization.
Users can donate to multiple organizations.

### Endpoints

GET /animals – Retrieve a list of animals available for adoption.
POST /adopt – Submit an adoption request for a specific animal.
GET /user/profile – Get user profile and adoption history.
POST /donate – Process a donation for an organisation or animal.
POST /login – Authenticate user credentials.

### Auth

User Login: User Authentication to allow users to log in via email/password, Google, or social media.
Roles: Two types of roles – regular users (adopters) and organisations (shelters, zoos, etc.).

## Roadmap

Sprint 1 (Week 1-2)
Research & Planning: Finalize user stories, sitemap, and data structure.
Design & Prototyping: Create mockups for key pages using Figma or another tool.
Sprint 2 (Week 3-4)
Backend Development: Set up API, database, and authentication.
Frontend Development: Develop core features of the web and mobile app.
Sprint 3 (Week 5-6)
Testing & Deployment: User testing, bug fixes, and deploy to production.


## Nice-to-haves

Social Sharing: Allow users to share their adoption stories on social media.
Push Notifications: Notify users about new animals available for adoption or updates on their adopted animals.
# capstone-project
