# Event Storming Report: House Renting Process

link to the miro image (https://miro.com/app/board/uXjVIO-NccQ=/)

### Introduction
Event Storming is a domain-driven design technique used to visualize and explore complex business processes by mapping out key events, commands, and interactions. The house renting process involves multiple interactions between landlords and tenants, from listing a property to finalizing an agreement.

This report outlines the Event Storming methodology used to analyze and model the key events, commands, actors, and processes involved in renting a house. By breaking down these interactions, we ensure a structured and efficient renting experience for both actors.

### Identifying Domain Events
Domain events represent significant occurrences in the system, written in the past tense. Key domain events in the house renting process include:

- Landlord Initiated listing
- Landlord entered property details
- Landlord uploaded property Images
- Landlord Provided a property description
- Listing submitted for approval
- House listed for rent
- Tenant Initiated chat inquiry
- The tenant requested for an apartment tour
- Landlord confirmed the apartment tour
- Tenant confirmed Interest or moved on
- The lease agreement discussion started

### Identifying Commands
Commands are instructions that trigger domain events, written in the present tense. Some commands in the house renting process include:

- **Initiate Listing** (Triggered by the landlord)
- **Submit Property** Details (Triggered by the landlord)
- **Upload Images** (Triggered by the landlord)
- **Write Property Description** (Triggered by the landlord)
- **Search for a Property** (Triggered by the tenant)
- **Send Inquiry** (Triggered by the tenant)
- **Schedule a Visit** (Triggered by the tenant)
- **Confirm Visit** (Triggered by the landlord)
- **Negotiate Lease Terms** (Triggered by tenant & landlord)
- **Search for a Property** (Triggered by the tenant)
- **Send Inquiry** (Triggered by the tenant)
- **Schedule a Visit** (Triggered by the tenant)
- **Confirm Visit** (Triggered by the landlord)
- **Negotiate Lease Terms** (Triggered by tenant & landlord)

### Identifying Actors and Systems
Each command is executed by a specific actor or system component. The main actors and systems in the house renting process include:

- Landlord (Responsible for listing and managing the property)
- Tenant (Person who rents the property)
- Renting Services (Handles notifications, scheduling, and approvals)

### Key Features of the System
1. Property Listing & Management:
- Landlords can list and update properties.
- Admin approval for listings (if required).
2. Search & Discovery:
- Tenants can browse properties by location, price, and features.
- Filters for available properties.
3. Tenant-Landlord Communication:
- In-app chat feature for inquiries.
- Landlords can respond and provide additional details.
4. Scheduling Visits:
- Tenants can request a property visit.
- Landlords can confirm or reschedule visits.
5. Lease & Payment Process:
- Lease agreement discussions via chat.
- Secure deposit handling (if integrated).

### Conclusion
By applying the Event Storming methodology, we have structured the house renting process into well-defined events, commands, actors, policies, and schemas. This structured approach ensures efficiency, modularity, and a better experience for landlords and tenants.
