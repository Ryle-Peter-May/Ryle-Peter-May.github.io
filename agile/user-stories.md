---
title: User Stories
layout: default
parent: Agile Project
nav_order: 2
---

# User Stories
{: .no_toc }

<details open markdown="block">
  <summary>Contents</summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Evidence

User stories for **SafeGuard Soshanguve**, grouped by the three types of user: residents, security guards and admins. Each reads as *"As a [user], I want to …"*.

### Resident

| ID | As a resident, I want to … |
|---|---|
| R-01 | Register an account using a phone number or email |
| R-02 | Verify my identity via OTP sent to my phone |
| R-03 | Set up a home address by dropping a pin on the map |
| R-04 | Add up to 3 emergency contacts |
| R-05 | Edit or remove emergency contacts at any time |
| R-06 | Set up a payment method and pay the monthly membership fee |
| R-07 | Press the SOS button to trigger an emergency alert |
| R-08 | Hold down the SOS button to confirm, to avoid accidental triggers |
| R-09 | Share my live GPS location automatically when SOS is activated |
| R-10 | Receive a push notification when a guard accepts the alert |
| R-11 | Receive a push notification when the guard is on route |
| R-12 | Receive a push notification when the guard has arrived |
| R-13 | View a live map showing the responding guard's location |
| R-14 | See the guard's estimated time of arrival |
| R-15 | View the guard's name, photo, and PSIRA number once assigned |
| R-16 | Cancel a false alarm before the guard departs |
| R-17 | View the full details of a resolved incident |
| R-18 | Rate the guard's response after an incident is resolved |
| R-19 | View my full alert history with dates, guards, and outcomes |
| R-20 | Report suspicious activity in the area |
| R-21 | Select an incident type when reporting |
| R-22 | View a live community crime feed filtered by area |
| R-23 | Receive community safety broadcast alerts from admin |
| R-24 | View a map of recent crime hotspots in the township |
| R-25 | Log out of the app |

### Security guard

| ID | As a security guard, I want to … |
|---|---|
| S-01 | Register a guard profile with my ID number and training certificate |
| S-02 | Upload my PSIRA certificate and ID for verification during registration |
| S-03 | Receive a notification when my profile is approved or rejected by admin |
| S-04 | Log my shift start by checking in on the app |
| S-05 | Log my shift end by checking out on the app |
| S-06 | View my assigned patrol zone on the map |
| S-07 | Update my availability status (available, on break, off duty) |
| S-08 | Receive an emergency alert notification with the resident's name and location |
| S-09 | Accept an incoming alert within the required response window, or decline it if unavailable |
| S-10 | Navigate to the resident using in-app map routing |
| S-11 | Flag a safety concern about a specific alert (e.g. "needs backup") |
| S-12 | Add notes when resolving an incident |
| S-13 | View my response history and past incidents handled |
| S-14 | View the equipment checklist and confirm equipment issued |
| S-15 | Report an equipment issue or request a replacement |

### Admin

| ID | As an admin, I want to … |
|---|---|
| A-01 | Register and approve new security guard profiles |
| A-02 | Deactivate or suspend a guard account |
| A-03 | Configure patrol zone boundaries on the map |
| A-04 | Assign guards to specific patrol zones on the map |
| A-05 | View a live dashboard of all active alerts in real time |
| A-06 | View live positions of all on-duty guards on the map |
| A-07 | Review and resolve guard safety flags |
| A-08 | Approve or reject community incident reports before they go public |
| A-09 | Post community safety announcements to residents in a specific area |
| A-10 | Broadcast an emergency-wide alert (not area-specific) |
| A-11 | Generate monthly reports on incidents and response times |
| A-12 | View guard performance metrics and average response times |
| A-13 | Manage membership payments |
| A-14 | Handle refunds or fee disputes |
| A-15 | Manage guard equipment inventory |

<!-- ### Tasks

*Each story breaks down into tasks on the team's Trello board. Add the tasks for the stories you worked on. The table below is a worked example.*

| Story | Task | Assigned to | Status |
|---|---|---|---|
| R-07 to R-09 | *[e.g. Design SOS button screen]* | *[Name]* | *[Status]* |
| R-07 to R-09 | *[e.g. Build hold-to-confirm logic]* | *[Name]* | *[Status]* |
| S-08 to S-10 | *[e.g. Build alert acceptance flow]* | *[Name]* | *[Status]* |

![Trello board with user stories]({{ site.baseurl }}/assets/images/trello-user-stories.png) -->

## Reflection

Writing the user stories made us think about the app from three points of view: the resident who needs help, the guard who responds, and the admin who keeps the system running. I drafted the first list on 16 and 17 July, and it grew to 55 stories. Each one later became a Trello card, written as "As a ... I want ..." with an owner and a due date.

The hardest part was splitting stories into tasks. The home address story had nine tasks while most others had four, so the stories were not the same size, and I only wrote task checklists for the first three sprints. After that the cards had no tasks, which made later work harder to track.

The user's point of view did change what we built. Stories like holding the SOS button to confirm it, or cancelling a false alarm, came from thinking about a resident in an emergency who might press the button by accident.

Next time I would write the tasks for every story before its sprint starts, review each card for copy and paste errors, and keep technical set-up out of the story list so that the stories stay about what users need.