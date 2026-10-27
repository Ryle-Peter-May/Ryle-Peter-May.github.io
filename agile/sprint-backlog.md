---
title: Sprint Backlog
layout: default
parent: Agile Project
nav_order: 4
---

# Sprint Backlog
{: .no_toc }

<details open markdown="block">
  <summary>Contents</summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Evidence

Work was planned in one-week sprints (Monday to Friday) on the team's [Trello board](https://trello.com/b/aCuzANQ9/safeguard). Each sprint is a list on the board; every card has one owner and a due date. Sprint goals below summarise the theme of each sprint's cards.

| Sprint | Dates | Goal | Items | Done |
|---|---|---|---|---|
| [1](#sprint-1) | 20 Jul to 24 Jul | Infrastructure and project setup | 6 | 6/6 |
| [2](#sprint-2) | 27 Jul to 31 Jul | Resident onboarding and emergency contacts | 5 | 5/5 |
| [3](#sprint-3) | 03 Aug to 07 Aug | Guard onboarding, shifts and alert receipt | 5 | 5/5 |
| [4](#sprint-4) | 10 Aug to 14 Aug | SOS trigger and live guard tracking | 5 | 5/5 |
| [5](#sprint-5) | 17 Aug to 21 Aug | Alert notifications and incident closure | 5 | 5/5 |
| [6](#sprint-6) | 24 Aug to 28 Aug | Feedback, alert history and community reporting | 5 | 5/5 |
| [7](#sprint-7) | 31 Aug to 04 Sep | Community alerts, hotspots, payments and guard details | 5 | 5/5 |
| [8](#sprint-8) | 07 Sep to 11 Sep | Guard response workflow | 5 | 5/5 |
| [9](#sprint-9) | 14 Sep to 18 Sep | Guard verification and equipment | 5 | 5/5 |
| [10](#sprint-10) | 21 Sep to 25 Sep | Admin guard management and live monitoring | 5 | 5/5 |
| [11](#sprint-11) | 28 Sep to 02 Oct | Admin moderation, reporting and zones | 5 | 5/5 |
| [12](#sprint-12) | 05 Oct to 09 Oct | Admin payments, equipment and emergency broadcast | 5 | 5/5 |
| [13](#sprint-13) | 12 Oct to 16 Oct | Integration and API hardening | 5 | 5/5 |
| [14](#sprint-14) | 19 Oct to 23 Oct | Dev wrap-up: testing, compliance and deployment readiness | 5 | 5/5 |
| [15](#sprint-15) | 26 Oct to 30 Oct | Onboarding walkthrough and training | 2 | 2/2 |
| [16](#sprint-16) | 26 Oct to 30 Oct | Deployment and production readiness | 5 | 5/5 |

### Sprint 1

**Goal:** Infrastructure and project setup  
**Dates:** 20 July to 24 July 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Set up JWT authentication and role-based authorization | Infrastructure | Angel | 21 Jul | Done |
| Integrate FCM for push notifications | Infrastructure | Nompumelelo | 22 Jul | Done |
| Set up React project structure | Infrastructure | Ryle | 23 Jul | Done |
| Implement geolocation "nearest guard" query | Infrastructure | Yamkela | 24 Jul | Done |
| Set up Spring Boot project structure | Infrastructure | Ryle | 20 Jul | Done |
| Design and implement database schema | Infrastructure | Tebogo | 21 Jul | Done |

**Tasks per item**

- **Set up JWT authentication and role-based authorization**
  - ✅ Configure JWT authentication in the Spring Boot application.
  - ✅ Create user roles (e.g., Resident, Guard, Admin).
  - ✅ Restrict access to endpoints based on user roles.
  - ✅ Test authentication and role-based access control.
- **Integrate FCM for push notifications**
  - ✅ Configure Firebase Cloud Messaging (FCM) in the application.
  - ✅ Implement push notification sending functionality.
  - ✅ Register and manage user device tokens.
  - ✅ Test push notifications on supported devices.
- **Set up React project structure**
  - ✅ Create a new React project.
  - ✅ Install and configure the required dependencies.
  - ✅ Organize the project folders and components.
  - ✅ Run the application and verify it starts successfully.
- **Implement geolocation "nearest guard" query**
  - ✅ Retrieve the user's current location.
  - ✅ Calculate the nearest available security guard.
  - ✅ Display the nearest guard on the map.
  - ✅ Test the nearest guard query for accuracy.
- **Set up Spring Boot project structure**
  - ✅ Create a new Spring Boot project.
  - ✅ Configure project dependencies (Spring Web, JPA, MySQL, etc.).
  - ✅ Set up the project folder structure and packages.
  - ✅ Run the application and verify that it starts successfully.
- **Design and implement database schema**
  - ✅ Design the database tables and relationships.
  - ✅ Create the database schema in MySQL.
  - ✅ Implement primary and foreign keys.
  - ✅ Test the database structure and connections.

### Sprint 2

**Goal:** Resident onboarding and emergency contacts  
**Dates:** 27 July to 31 July 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Register an account using a phone number | Resident | Angel | 27 Jul | Done |
| Set up a home address by dropping a pin on the map | Resident | Ryle | 28 Jul | Done |
| Add up to 3 emergency contacts | Resident | Nompumelelo | 29 Jul | Done |
| Edit or remove emergency contacts at any time | Resident | Tebogo | 30 Jul | Done |
| Verify identity via OTP sent to phone | Resident | Yamkela | 31 Jul | Done |

**Tasks per item**

- **Register an account using a phone number**
  - ✅ Design the registration screen
  - ✅ Create the registration form
  - ✅ Validate phone number format
  - ✅ Validate required fields
- **Set up a home address by dropping a pin on the map**
  - ✅ Design the "Set Home Address" screen
  - ✅ Integrate Google Maps/OpenStreetMap
  - ✅ Display the user's current location
  - ✅ Enable dropping a pin on the map
  - ✅ Retrieve latitude and longitude from the pin
  - ✅ Convert coordinates to a readable address (reverse geocoding)
  - ✅ Display the selected address to the user
  - ✅ Allow the user to confirm or edit the location
  - ✅ Save the home address to the database
- **Add up to 3 emergency contacts**
  - ✅ Design the Emergency Contacts screen.
  - ✅ Create a form to add up to three emergency contacts.
  - ✅ Validate and save the emergency contacts to the database.
  - ✅ Test adding, editing, and deleting emergency contacts.
- **Edit or remove emergency contacts at any time**
  - ✅ Design the Edit Emergency Contact screen.
  - ✅ Allow users to edit existing emergency contacts.
  - ✅ Allow users to remove emergency contacts.
  - ✅ Test editing and deleting emergency contacts.
- **Verify identity via OTP sent to phone**
  - ✅ Generate and send an OTP to the user's phone number.
  - ✅ Allow the user to enter the OTP.
  - ✅ Verify the OTP and activate the account if valid.
  - ✅ Test OTP verification and handle invalid or expired OTPs.

### Sprint 3

**Goal:** Guard onboarding, shifts and alert receipt  
**Dates:** 03 August to 07 August 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Receive an emergency alert notification with resident name and location | Security | Yamkela | 07 Aug | Done |
| Register a guard profile with ID number and training certificate | Security | Nompumelelo | 03 Aug | Done |
| Log shift start by checking in on the app | Security | Angel | 04 Aug | Done |
| Log shift end by checking out on the app | Security | Tebogo | 05 Aug | Done |
| View assigned patrol zone on the map | Security | Ryle | 06 Aug | Done |

**Tasks per item**

- **Register a guard profile with ID number and training certificate**
  - ✅ Design the guard registration form.
  - ✅ Allow the guard to enter their ID number and upload a training certificate.
  - ✅ Validate the submitted information and documents.
  - ✅ Test the guard registration and verification process.
- **Log shift end by checking out on the app**
  - ✅ Design the shift check-out screen.
  - ✅ Allow the guard to check out at the end of their shift.
  - ✅ Record the check-out time in the database.
  - ✅ Test the shift check-out functionality.

### Sprint 4

**Goal:** SOS trigger and live guard tracking  
**Dates:** 10 August to 14 August 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Press the SOS button to trigger an emergency alert | Resident | Nompumelelo | 10 Aug | Done |
| Hold down the SOS button to confirm and avoid accidental triggers | Resident | Angel | 11 Aug | Done |
| Share live GPS location automatically when SOS is activated | Resident | Ryle | 12 Aug | Done |
| View a live map showing the responding guard's location | Resident | Tebogo | 13 Aug | Done |
| See the guard's estimated time of arrival | Resident | Yamkela | 14 Aug | Done |

### Sprint 5

**Goal:** Alert notifications and incident closure  
**Dates:** 17 August to 21 August 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Receive a push notification when a guard accepts the alert | Resident | Nompumelelo | 17 Aug | Done |
| Receive a push notification when the guard is on route | Resident | Angel | 18 Aug | Done |
| Receive a push notification when the guard has arrived | Resident | Tebogo | 19 Aug | Done |
| Cancel a false alarm before the guard departs | Resident | Yamkela | 20 Aug | Done |
| View the full details of a resolved incident | Resident | Ryle | 21 Aug | Done |

### Sprint 6

**Goal:** Feedback, alert history and community reporting  
**Dates:** 24 August to 28 August 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Rate the guard's response after an incident is resolved | Resident | Angel | 24 Aug | Done |
| View full personal alert history with dates, guards, and outcomes | Resident | Nompumelelo | 25 Aug | Done |
| Report on suspicious activity in the area | Resident | Yamkela | 26 Aug | Done |
| Select an incident type | Resident | Ryle | 27 Aug | Done |
| View a live community crime feed filtered by area | Resident | Tebogo | 28 Aug | Done |

### Sprint 7

**Goal:** Community alerts, hotspots, payments and guard details  
**Dates:** 31 August to 04 September 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Receive community safety broadcast alerts from admin | Resident | Ryle | 31 Aug | Done |
| View a map of recent crime hotspots in the township | Resident | Angel | 01 Sep | Done |
| Log out of the app | Resident | Nompumelelo | 02 Sep | Done |
| Set up payment method and pay monthly membership fee | Resident | Tebogo | 03 Sep | Done |
| View guard's name, photo, and PSIRA number once assigned | Resident | Yamkela | 04 Sep | Done |

### Sprint 8

**Goal:** Guard response workflow  
**Dates:** 07 September to 11 September 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Navigate to the resident using in-app map routing | Security | Ryle | 07 Sep | Done |
| Accept an incoming alert within the required response window, decline an alert if unavailable | Security | Angel | 08 Sep | Done |
| Update availability status (available, on break, off duty) | Security | Tebogo | 09 Sep | Done |
| Add notes when resolving an incident | Security | Yamkela | 10 Sep | Done |
| View personal response history and past incidents handled | Security | Nompumelelo | 11 Sep | Done |

### Sprint 9

**Goal:** Guard verification and equipment  
**Dates:** 14 September to 18 September 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Upload PSIRA certificate and ID for verification during registration | Security | Ryle | 14 Sep | Done |
| Receive notification when profile is approved/rejected by admin | Security | Angel | 15 Sep | Done |
| View equipment checklist / confirm equipment issued | Security | Nompumelelo | 16 Sep | Done |
| Report an equipment issue or request replacement | Security | Tebogo | 17 Sep | Done |
| Flag a safety concern about a specific alert (e.g. "needs backup") | Security | Yamkela | 18 Sep | Done |

### Sprint 10

**Goal:** Admin guard management and live monitoring  
**Dates:** 21 September to 25 September 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Register and approve new security guard profiles | Admin | Ryle | 21 Sep | Done |
| Assign guards to specific patrol zones on the map | Admin | Angel | 22 Sep | Done |
| Deactivate or suspend a guard account | Admin | Nompumelelo | 23 Sep | Done |
| View a live dashboard of all active alerts in real time | Admin | Tebogo | 24 Sep | Done |
| View live positions of all on-duty guards on the map | Admin | Yamkela | 25 Sep | Done |

### Sprint 11

**Goal:** Admin moderation, reporting and zones  
**Dates:** 28 September to 02 October 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Approve or reject community incident reports before they go public | Admin | Angel | 28 Sep | Done |
| Post community safety announcements to residents in a specific area | Admin | Ryle | 29 Sep | Done |
| Generate monthly reports on incidents and response times | Admin | Nompumelelo | 30 Sep | Done |
| View guard performance metrics and average response times | Admin | Yamkela | 01 Oct | Done |
| Configure patrol zone boundaries on the map | Admin | Tebogo | 02 Oct | Done |

### Sprint 12

**Goal:** Admin payments, equipment and emergency broadcast  
**Dates:** 05 October to 09 October 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Manage membership payments | Admin | Ryle | 05 Oct | Done |
| Handle refunds or fee disputes | Admin | Angel | 06 Oct | Done |
| Manage guard equipment inventory | Admin | Nompumelelo | 07 Oct | Done |
| Broadcast emergency-wide alert (not area-specific) | Admin | Tebogo | 08 Oct | Done |
| Review and resolve guard safety flags | Admin | Yamkela | 09 Oct | Done |

### Sprint 13

**Goal:** Integration and API hardening  
**Dates:** 12 October to 16 October 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Integrate payment gateway sandbox and webhook handling | Integration | Angel | 12 Oct | Done |
| Set up WebSocket channel for live alert status updates | Integration | Ryle | 13 Oct | Done |
| Implement API rate limiting / abuse protection on SOS endpoint | Integration | Nompumelelo | 14 Oct | Done |
| Write API documentation | Integration | Tebogo | 15 Oct | Done |
| Set up error logging/monitoring | Integration | Yamkela | 16 Oct | Done |

### Sprint 14

**Goal:** Dev wrap-up: testing, compliance and deployment readiness  
**Dates:** 19 October to 23 October 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Write unit tests | Dev Wrap-Up | Ryle | 19 Oct | Done |
| Set up staging environment and deployment pipeline | Dev Wrap-Up | Angel | 20 Oct | Done |
| POPIA compliance review | Dev Wrap-Up | Nompumelelo | 21 Oct | Done |
| Conduct security penetration testing before launch | Dev Wrap-Up | Tebogo | 22 Oct | Done |
| Set up automated database backup and recovery plan | Dev Wrap-Up | Yamkela | 23 Oct | Done |

### Sprint 15

**Goal:** Onboarding walkthrough and training  
**Dates:** 26 October to 30 October 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Complete first-time app onboarding walkthrough | Onboarding | Yamkela, Ryle, Angel | 26 Oct | Done |
| Complete in-app safety onboarding training module | Onboarding | Nompumelelo, Tebogo | 27 Oct | Done |

### Sprint 16

**Goal:** Deployment and production readiness  
**Dates:** 26 October to 30 October 2026

| Item | Type | Owner | Due | Status |
|---|---|---|---|---|
| Implement SMS fallback integration | Deployment | Ryle | 28 Oct | Done |
| Implement caching layer for guard location lookups | Deployment | Angel | 28 Oct | Done |
| Set up load testing for the SOS/alert endpoint | Deployment | Tebogo | 30 Oct | Done |
| Set up mobile app crash reporting | Deployment | Yamkela | 29 Oct | Done |
| Set up app store deployment pipeline | Onboarding, Deployment | Nompumelelo | 30 Oct | Done |


![Sprint board]({{ site.baseurl }}/assets/images/sprint-backlog.png)

[https://trello.com/b/aCuzANQ9/safeguard](https://trello.com/b/aCuzANQ9/safeguard)

## Reflection

We planned in sixteen one-week sprints starting on 20 July, each with about five items. Every item had one owner and its own daily due date, so each person had one story a day. Sprints 1 to 12 were all ticked off on the board, which shows the plan was achievable on paper.

What I learned is that this setup was neat but not very flexible. Giving everyone one item per day made the workload look even, but it ignored size and difficulty.

The move from Java to Supabase in August also showed the value of short sprints. Because the plan was broken into weekly blocks, the change could be absorbed between sprints instead of derailing one long plan.

Next time I would set up the sprint board before Sprint 1, agree a sprint goal with the team in every planning session, hold a short review and retrospective at the end of each sprint, and leave some room in each sprint for change.