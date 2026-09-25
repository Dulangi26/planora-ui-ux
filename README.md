# Planora — Travel Planning Workspace

**Every journey, connected.**

Planora is a desktop UI/UX design concept for travel agents who manage client enquiries, build trips and coordinate travel services. The project explores how a consistent workspace can make everyday travel planning easier to scan and navigate.

**Designer:** Dulangika Chathurani Malankande  
**Tool:** Figma  
**Project type:** UI/UX design portfolio

[View the Figma design](https://www.figma.com/design/ZIwKa7xrfR3Aj36LBIhyuA/PLANORA)

## Contents

- [Overview](#overview)
- [Design approach](#design-approach)
- [Screen gallery](#screen-gallery)
- [Navigation flow](#navigation-flow)
- [Scope](#scope)
- [Repository files](#repository-files)
- [Credits](#credits)

## Overview

Busy travel agents need to find enquiries quickly, identify requests needing attention and review the services attached to a trip. Planora brings these tasks into a shared interface with compact tables, clear actions and labelled statuses.

The design considers internal agents and partner agencies sharing a sign-in entry point. The dashboard shown in this repository is the internal agent view.

## Design approach

- **Task-focused dashboard:** enquiries awaiting replies, quotations awaiting decisions and supplier requests awaiting confirmation.
- **Compact enquiry management:** client names, destinations, travel dates, traveller counts, values, owners and statuses in one table.
- **Trip context:** services, client information and estimated prices grouped within a single workspace.
- **Contextual service selection:** an Add service menu introduces Flight, Hotel and Restaurant options.
- **Property-first hotel selection:** agents compare properties, then choose room types, board basis and quantities.
- **Consistent visual identity:** deep ocean and teal colours, light surfaces, reusable controls and travel imagery.

Enquiry labels include **New, Quoted, Accepted, Partially booked, Fully booked and Lost**. Trip service rows demonstrate **Draft** status. Enquiry stage and individual service status represent different levels of progress.

## Screen gallery

### Brand board

Brand identity and visual foundations.

![Brand board](screens/Brand%20Board.png)

### Splash — Start

A coastal introduction to the Planora workspace.

![Splash — Start](screens/Splash%201.png)

### Splash — Ready

A ready state with a clear route to sign in.

![Splash — Ready](screens/Splash%202.png)

### Login

Email and password entry with account setup and password recovery links.

![Login](screens/02%20%E2%80%94%20Login%281%29.png)

### Wrong credentials

Sign-in feedback when the supplied credentials cannot be verified.

![Wrong credentials](screens/02A%20%E2%80%94%20Wrong%20credentials%281%29.png)

### Account not activated

A separate state for an account awaiting activation.

![Account not activated](screens/02B%20%E2%80%94%20Account%20not%20activated%281%29.png)

### First-time password setup

Password creation with visible password requirements.

![First-time password setup](screens/02C%20-%20First%20Time%20Password%20Setup%281%29.png)

### Internal agent dashboard

Queues for enquiries, quotation follow-ups and supplier confirmations.

![Internal agent dashboard](screens/03A%20%E2%80%94%20Internal%20agent%20dashboard%281%29.png)

### Enquiries list

A compact client table with search, filter controls, ownership, values and enquiry statuses.

![Enquiries list](screens/04A%20%E2%80%94%20Enquiries%20List.png)

### Trip detail

Trip information, draft services, client and traveller panels, and a price summary.

![Trip detail](screens/05%20-%20Trip%20Details.png)

### Add service menu

A contextual chooser for Flight, Hotel or Restaurant.

![Add service menu](screens/Add%20service%20menu.png)

### Hotel search and room selection

Property images, room rates, board basis, cancellation terms and room quantities, including a property without photographs.

![Hotel search and room selection](screens/07%20-%20Add%20Hotel.png)

The hotel screen uses a separate Singapore sample trip. The trip detail screen shows N. Perera’s Kandy enquiry; these examples are not a single continuous itinerary.

## Navigation flow

The intended interaction flow is:

1. Splash and ready screens lead to sign-in.
2. Sign-in leads to the internal agent dashboard.
3. An enquiry row opens its trip detail view.
4. **Add service** opens the Flight / Hotel / Restaurant chooser.
5. A service search allows selection before returning to the trip.

The hotel example demonstrates **3 rooms × 5 nights × USD 150 = USD 2,250**, with room occupancy shown in the selection panel. Selecting rooms adds a service to the trip; it does not itself establish supplier confirmation.

These PNGs are static design exports. Refer to the Figma file to explore the design; this repository does not contain a running application or live booking integration.

## Scope

The gallery documents the supplied final exports: brand foundations, splash screens, authentication states, internal dashboard, enquiries, trip detail, service chooser and hotel selection.

Flight and restaurant search screens, the partner dashboard, dedicated no-results variants and zero-/fourteen-service trip examples are not included in this export set. The screenshots do not establish completed usability testing, accessibility conformance or fully implemented interactions.

All client information, suppliers, prices and availability are illustrative design data.

## Repository files

Keep `README.md` at the repository root and all 13 images directly inside `screens/`.

| File in screens/ | Purpose |
| --- | --- |
| [Brand Board.png](screens/Brand%20Board.png) | Brand board |
| [Splash 1.png](screens/Splash%201.png) | Splash — Start |
| [Splash 2.png](screens/Splash%202.png) | Splash — Ready |
| [02 — Login(1).png](screens/02%20%E2%80%94%20Login%281%29.png) | Login |
| [02A — Wrong credentials(1).png](screens/02A%20%E2%80%94%20Wrong%20credentials%281%29.png) | Wrong credentials |
| [02B — Account not activated(1).png](screens/02B%20%E2%80%94%20Account%20not%20activated%281%29.png) | Account not activated |
| [02C - First Time Password Setup(1).png](screens/02C%20-%20First%20Time%20Password%20Setup%281%29.png) | First-time password setup |
| [03A — Internal agent dashboard(1).png](screens/03A%20%E2%80%94%20Internal%20agent%20dashboard%281%29.png) | Internal agent dashboard |
| [04A — Enquiries List.png](screens/04A%20%E2%80%94%20Enquiries%20List.png) | Enquiries list |
| [05 - Trip Details.png](screens/05%20-%20Trip%20Details.png) | Trip detail |
| [Add service menu.png](screens/Add%20service%20menu.png) | Add service menu |
| [07 - Add Hotel.png](screens/07%20-%20Add%20Hotel.png) | Hotel search and room selection |
| [Logo.png](screens/Logo.png) | Planora logo |

Image links use the exact final export filenames, including spaces and `(1)` suffixes. If you rename an image, update its link in this README as well.

## Credits

UI design and Figma assembly by **Dulangika Chathurani Malankande**.

AI assistance supported design exploration, reference mockups, selected imagery and documentation. Other photographs and icons remain subject to their original sources and usage terms. Planora is a portfolio concept and does not claim affiliation with the suppliers shown.
