# Awesome-Return-To-Workplace-Command-Center

# Top Return-to-Workplace Command Center Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Workplace Occupancy, Desk Booking & Self-Hosted Return-to-Office Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial workplace command center platforms** and **open-source projects** that manage return-to-office operations — occupancy tracking, desk and room booking, employee wellness checks, capacity management, and workplace analytics.

**Examples** include Salesforce Workplace Command Center, ServiceNow Workplace Service Delivery, Envoy Protect, Robin Return-to-Office, Eptura Workplace, VergeSense Occupancy, OfficeRnD, Density OpenPath, Condeco, and Kadence (the category leaders).

**Open-source emphasis**: Return-to-workplace management is a growing open-source domain. **OpenDesk** leads as a lightweight desk reservation system for hybrid offices . **WARP (Workspace Autonomous Reservation Program)** brings a comprehensive hybrid workspace management system with floor plans, zones, SAML/LDAP/OIDC SSO, iCal feeds, and PWA support . **Occupi** provides AI-powered office occupancy prediction and real-time analytics . **HQ Command Center** offers an offline React dashboard for cross-machine fleet coordination .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Workplace Command Center](https://www.salesforce.com/)**  
  **Salesforce's workplace reopening hub** — employee wellness surveys, shift scheduling, facility preparedness tracking, and public health data integration. **Pricing: $5/user/month** with base Platform or CRM license required . **Includes 300 survey responses** with Enterprise Editions; additional packs of 1,000 surveys for $300 . **Personas**: Workplace Admin, Workplace Operations, Workplace Operations Executive .

- **[ServiceNow Workplace Service Delivery](https://www.servicenow.com/)**  
  **ServiceNow's workplace operations platform** — space reservations, visitor management, indoor mapping, and event planning with bidirectional sync between Indoor Mapping and WSD .

- **[Envoy Protect](https://envoy.com/)**  
  **Workplace safety and capacity management** — employee registration with health questionnaires, touchless sign-in, capacity limits, and Protect analytics showing expected vs. actual arrivals .

- **[Robin Return-to-Office](https://robinpowered.com/)**  
  **Hybrid workplace platform** — Schedule page showing who plans to be in office, desk booking with automatic status updates, and default work schedules with automatic desk reservations .

- **[Eptura Workplace](https://eptura.com/)**  
  **Integrated workplace operations platform** — live analytics for desk and room usage, AI assistants for booking and maintenance, visitor management, and space planning with scenario analysis .

- **[VergeSense Occupancy](https://www.vergesense.com/)**  
  **Occupancy intelligence and predictive planning** — Large Spatial Model trained on 250M+ sq ft, badge data uploads, read-only calendar integrations, and Logitech integration for person counting .

- **[OfficeRnD](https://www.officernd.com/)**  
  **Coworking and flexible workspace management** — resource types (hot desks, private offices, meeting rooms), hourly/daily rates, assignable resources, amenities, and occupancy dashboards .

- **[Density OpenPath](https://www.density.io/)**  
  **Occupancy analytics and access control** — anonymous people counting, conference room monitoring, and integration with workplace platforms .

- **[Condeco](https://www.condeco.com/)**  
  **Workspace booking platform** — book desks, meeting rooms, parking, lockers, and quiet spaces via mobile app with proximity-based check-in .

- **[Kadence](https://kadence.co/)**  
  **Workplace operations platform** — bulk space layout uploads, multi-day bookings, workplace surveys, automatic desk assignment via Kadence Agent, and Neighborhood Scheduler for team coordination .

## Open-Source GitHub Projects

### Desk Booking & Space Reservation

- **[WARP (Workspace Autonomous Reservation Program)](https://github.com/sebo-b/warp)**  
  **Comprehensive open-source hybrid workspace management system**, open-source . **Book/change/unbook desks or parking stalls** in the office . **Mobile-friendly with PWA support** — installable as app . **Visual floor plans with zones** — each seat assigned to a specific zone, one seat per zone per time slot . **Assigned seats** — limit seats to certain people; **Disabled seats** — hide seats from view . **Auto-Book** with floating "+" button . **Calendar integration** — subscribe to iCal feeds in Google Calendar, Outlook, or Apple Calendar with `?type=bookings` or `?type=reminders` filters . **Per-zone reminders** for automatic booking and seat-release notifications . **Days-in-advance booking window** per assignment . **Virtual "everyone" access** for flexible seat management . **Translations**: English, German, French, Spanish, Polish . **SSO support**: SAML 2.0, LDAP/Active Directory, Azure AD (MSAL), OIDC/OpenID Connect . **Full admin interface** for maps, zones, groups, and users . **Report generation** with Excel export . **Tech stack**: Python, with detailed FEATURES.md, GLOSSARY.md, and PERMISSIONS.md documentation . **Best for organizations wanting a complete self-hosted hybrid workspace reservation system** .

- **[OpenDesk](https://github.com/kanwalnainsingh/OpenDesk)**  
  **Open-source desk reservation system for hybrid offices**, open-source . **Organizations set up sites/buildings with desk capacity** — available and reserved desks . **Dashboard to view present state and availability** . **Employees reserve desks for specific dates** before coming to office . **Modify, cancel, and view previous reservations** . **Booking confirmation alerts** . **Roadmap**: SSO with roles, email notifications, department segregation, desk map configurations, and real-time organization dashboard . **Microservice architecture** . **Best for simple, lightweight desk booking without complexity** .

- **[HQ Command Center (@wrongstack/webui-hq)](https://www.npmjs.com/package/@wrongstack/webui-hq)**  
  **Offline React app for cross-machine coordination**, open-source . **Self-contained Vite + React app** with zero CDN dependencies — works on offline/LAN/restricted-network machines . **12 views**: Cockpit (fleet/alert/cost overview), Fleet (searchable topology), Console (live chat + leader/subagent messaging), Mailbox, Kanban, Cost, Brain (decision timeline), Worktrees, Trends, Alerts, Control (steer/abort/spawn/broadcast), and Security . **Connects via WebSocket** to HQ server . **Zustand store** for state management . **Best for technical teams wanting a custom offline command center dashboard** .

### Occupancy Intelligence & Prediction

- **[Occupi](https://github.com/COS301-SE-2024/occupi)**  
  **System to record and predict office occupancy on a day-to-day basis**, MIT licensed with **8 GitHub stars** . **AI-powered occupancy prediction** — forecasts daily office usage patterns . **Real-time analytics** — live occupancy tracking and historical trends . **Cross-platform**: desktop, mobile, and web applications . **Backend in Go** with MIT license . **Best for organizations wanting predictive occupancy analytics** .

- **[Thermal Occupancy Detection](https://www.sciencedirect.com/science/article/abs/pii/S0360132325013411)**  
  **Privacy-preserving occupancy detection using thermal imaging and edge computing**, research-based . **CNN with fewer than 10 hidden layers** achieves **96% training accuracy and 97% validation accuracy** . **Real-time detection accuracy of 78%** in both illuminated and dark environments . **Infrared images capture only thermal distribution** — no face features or identifiable information . **Edge computing** — processes data locally with reduced latency and bandwidth . **Best for privacy-conscious occupancy detection without cameras** .

### Additional Strong Open-Source Options

- **Zulip** — Open-source team chat that can be integrated with workplace coordination workflows.
- **Nextcloud** — Self-hosted file sharing and collaboration for workplace documents.
- **Outline** — Open-source knowledge base for workplace policies and procedures.
- **BookStack** — Open-source documentation platform for workplace guides.
- **Odoo** — Open-source ERP with HR and facility management modules adaptable for workplace operations.

**Frameworks for building custom return-to-workplace solutions**: Combine **WARP** for comprehensive desk booking with floor plans, zones, and SSO . Use **OpenDesk** for lightweight desk reservation without complexity . Deploy **Occupi** for AI-powered occupancy prediction and analytics . Integrate **HQ Command Center** for offline cross-machine coordination dashboards . Note that true enterprise workplace command centers with capacity management, wellness checks, visitor management, and vendor-supported SLAs (Salesforce WCC, ServiceNow WSD, Envoy Protect) remain primarily commercial territory; open-source stacks provide strong desk booking, occupancy tracking, and coordination foundations that require integration for complete return-to-workplace operations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Workplace command centers handle sensitive employee data including health information and location tracking. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, HIPAA for health data).
- **Employee wellness data requires strict privacy controls** — Salesforce recommends granting admin privileges only to admins who must know the information . Envoy Protect records only pass/fail status, not detailed health answers .
- **Occupancy tracking must be transparent** — employees should be informed about what data is collected and how it is used. Thermal imaging solutions offer privacy-preserving alternatives to cameras .
- **License considerations**: WARP is open-source , OpenDesk is open-source , and Occupi uses MIT license . Verify licensing against your use case before committing.
- The open-source ecosystem provides strong desk booking, occupancy tracking, and coordination foundations, but **capacity management, wellness checks, visitor management, and vendor-supported SLAs** remain primarily commercial offerings.
