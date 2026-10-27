---
title: Product Backlog
layout: default
parent: Agile Project
nav_order: 3
---

# Product Backlog
{: .no_toc }

<details Done markdown="block">
  <summary>Contents</summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Evidence

The product backlog for **SafeGuard Soshanguve** was kept on a shared [Trello board](https://trello.com/b/aCuzANQ9/safeguard). Each card is one backlog item, labelled by user type (Resident, Security, Admin) or work type (Infrastructure, Integration, Dev Wrap-Up, Onboarding, Deployment), assigned an owner and planned into a sprint.

|---|---|
| **Total backlog items** | 78 |
| **Marked done on the board** | 61 |
| **Planned sprints** | 16 (weekly, 20 July to 30 October 2026) |

### Backlog in priority order

Items are listed in the order they were prioritised on the board. Technical foundation work came first, followed by user-facing features grouped by user type (Resident, then Security, then Admin), then integration, wrap-up and deployment.

| # | Item | Type | Sprint | Owner | Status |
|---|---|---|---|---|---|
| 1 | Set up JWT authentication and role-based authorization | Infrastructure | 1 | Angel | Done |
| 2 | Integrate FCM for push notifications | Infrastructure | 1 | Nompumelelo | Done |
| 3 | Set up React project structure | Infrastructure | 1 | Ryle | Done |
| 4 | Implement geolocation "nearest guard" query | Infrastructure | 1 | Yamkela | Done |
| 5 | Set up Spring Boot project structure | Infrastructure | 1 | Ryle | Done |
| 6 | Design and implement database schema | Infrastructure | 1 | Tebogo | Done |
| 7 | Register an account using a phone number | Resident | 2 | Angel | Done |
| 8 | Set up a home address by dropping a pin on the map | Resident | 2 | Ryle | Done |
| 9 | Add up to 3 emergency contacts | Resident | 2 | Nompumelelo | Done |
| 10 | Edit or remove emergency contacts at any time | Resident | 2 | Tebogo | Done |
| 11 | Verify identity via OTP sent to phone | Resident | 2 | Yamkela | Done |
| 12 | Receive an emergency alert notification with resident name and location | Security | 3 | Yamkela | Done |
| 13 | Register a guard profile with ID number and training certificate | Security | 3 | Nompumelelo | Done |
| 14 | Log shift start by checking in on the app | Security | 3 | Angel | Done |
| 15 | Log shift end by checking out on the app | Security | 3 | Tebogo | Done |
| 16 | View assigned patrol zone on the map | Security | 3 | Ryle | Done |
| 17 | Press the SOS button to trigger an emergency alert | Resident | 4 | Nompumelelo | Done |
| 18 | Hold down the SOS button to confirm and avoid accidental triggers | Resident | 4 | Angel | Done |
| 19 | Share live GPS location automatically when SOS is activated | Resident | 4 | Ryle | Done |
| 20 | View a live map showing the responding guard's location | Resident | 4 | Tebogo | Done |
| 21 | See the guard's estimated time of arrival | Resident | 4 | Yamkela | Done |
| 22 | Receive a push notification when a guard accepts the alert | Resident | 5 | Nompumelelo | Done |
| 23 | Receive a push notification when the guard is on route | Resident | 5 | Angel | Done |
| 24 | Receive a push notification when the guard has arrived | Resident | 5 | Tebogo | Done |
| 25 | Cancel a false alarm before the guard departs | Resident | 5 | Yamkela | Done |
| 26 | View the full details of a resolved incident | Resident | 5 | Ryle | Done |
| 27 | Rate the guard's response after an incident is resolved | Resident | 6 | Angel | Done |
| 28 | View full personal alert history with dates, guards, and outcomes | Resident | 6 | Nompumelelo | Done |
| 29 | Report on suspicious activity in the area | Resident | 6 | Yamkela | Done |
| 30 | Select an incident type | Resident | 6 | Ryle | Done |
| 31 | View a live community crime feed filtered by area | Resident | 6 | Tebogo | Done |
| 32 | Receive community safety broadcast alerts from admin | Resident | 7 | Ryle | Done |
| 33 | View a map of recent crime hotspots in the township | Resident | 7 | Angel | Done |
| 34 | Log out of the app | Resident | 7 | Nompumelelo | Done |
| 35 | Set up payment method and pay monthly membership fee | Resident | 7 | Tebogo | Done |
| 36 | View guard's name, photo, and PSIRA number once assigned | Resident | 7 | Yamkela | Done |
| 37 | Navigate to the resident using in-app map routing | Security | 8 | Ryle | Done |
| 38 | Accept an incoming alert within the required response window, decline an alert if unavailable | Security | 8 | Angel | Done |
| 39 | Update availability status (available, on break, off duty) | Security | 8 | Tebogo | Done |
| 40 | Add notes when resolving an incident | Security | 8 | Yamkela | Done |
| 41 | View personal response history and past incidents handled | Security | 8 | Nompumelelo | Done |
| 42 | Upload PSIRA certificate and ID for verification during registration | Security | 9 | Ryle | Done |
| 43 | Receive notification when profile is approved/rejected by admin | Security | 9 | Angel | Done |
| 44 | View equipment checklist / confirm equipment issued | Security | 9 | Nompumelelo | Done |
| 45 | Report an equipment issue or request replacement | Security | 9 | Tebogo | Done |
| 46 | Flag a safety concern about a specific alert (e.g. "needs backup") | Security | 9 | Yamkela | Done |
| 47 | Register and approve new security guard profiles | Admin | 10 | Ryle | Done |
| 48 | Assign guards to specific patrol zones on the map | Admin | 10 | Angel | Done |
| 49 | Deactivate or suspend a guard account | Admin | 10 | Nompumelelo | Done |
| 50 | View a live dashboard of all active alerts in real time | Admin | 10 | Tebogo | Done |
| 51 | View live positions of all on-duty guards on the map | Admin | 10 | Yamkela | Done |
| 52 | Approve or reject community incident reports before they go public | Admin | 11 | Angel | Done |
| 53 | Post community safety announcements to residents in a specific area | Admin | 11 | Ryle | Done |
| 54 | Generate monthly reports on incidents and response times | Admin | 11 | Nompumelelo | Done |
| 55 | View guard performance metrics and average response times | Admin | 11 | Yamkela | Done |
| 56 | Configure patrol zone boundaries on the map | Admin | 11 | Tebogo | Done |
| 57 | Manage membership payments | Admin | 12 | Ryle | Done |
| 58 | Handle refunds or fee disputes | Admin | 12 | Angel | Done |
| 59 | Manage guard equipment inventory | Admin | 12 | Nompumelelo | Done |
| 60 | Broadcast emergency-wide alert (not area-specific) | Admin | 12 | Tebogo | Done |
| 61 | Review and resolve guard safety flags | Admin | 12 | Yamkela | Done |
| 62 | Integrate payment gateway sandbox and webhook handling | Integration | 13 | Angel | Done |
| 63 | Set up WebSocket channel for live alert status updates | Integration | 13 | Ryle | Done |
| 64 | Implement API rate limiting / abuse protection on SOS endpoint | Integration | 13 | Nompumelelo | Done |
| 65 | Write API documentation | Integration | 13 | Tebogo | Done |
| 66 | Set up error logging/monitoring | Integration | 13 | Yamkela | Done |
| 67 | Write unit tests | Dev Wrap-Up | 14 | Ryle | Done |
| 68 | Set up staging environment and deployment pipeline | Dev Wrap-Up | 14 | Angel | Done |
| 69 | POPIA compliance review | Dev Wrap-Up | 14 | Nompumelelo | Done |
| 70 | Conduct security penetration testing before launch | Dev Wrap-Up | 14 | Tebogo | Done |
| 71 | Set up automated database backup and recovery plan | Dev Wrap-Up | 14 | Yamkela | Done |
| 72 | Complete first-time app onboarding walkthrough | Onboarding | 15 | Yamkela, Ryle, Angel | Done |
| 73 | Complete in-app safety onboarding training module | Onboarding | 15 | Nompumelelo, Tebogo | Done |
| 74 | Implement SMS fallback integration | Deployment | 16 | Ryle | Done |
| 75 | Implement caching layer for guard location lookups | Deployment | 16 | Angel | Done |
| 76 | Set up load testing for the SOS/alert endpoint | Deployment | 16 | Tebogo | Done |
| 77 | Set up mobile app crash reporting | Deployment | 16 | Yamkela | Done |
| 78 | Set up app store deployment pipeline | Onboarding, Deployment | 16 | Nompumelelo | Done |


![Product backlog on Trello]({{ site.baseurl }}/assets/images/product-backlog.png)

[https://trello.com/b/aCuzANQ9/safeguard](https://trello.com/b/aCuzANQ9/safeguard)

## Reflection

The product backlog took shape between 16 and 22 July, when I wrote the user stories, revised the backlog and then added dates to each item. It ended up with 78 items on Trello: infrastructure first, then resident, guard and admin features, and finally integration, wrap-up and deployment work.

Looking back, the order followed user type rather than value. The SOS button, the core of the product, was only built in Sprint 4, after account set-up and guard onboarding. That made sense because the app cannot work without accounts, but a thin end-to-end alert flow earlier would have shown us sooner whether the idea worked.

The backlog also changed under us. The infrastructure items assumed a Java Spring Boot backend with MySQL, and in mid-August we moved to Supabase, so those early items no longer matched what we built. I also did not estimate items. Every card was effectively one day of work, which hides the fact that some stories were much bigger than others.

Next time I would prioritise by value and risk, put a minimal working alert flow into the first sprints, add story point estimates, and review and reprioritise the backlog at the start of every sprint.