---
title: Agile Logbook
layout: default
parent: Agile Project
nav_order: 5
---

# Agile Logbook
{: .no_toc }

<details open markdown="block">
  <summary>Contents</summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Evidence

A daily stand-up log, kept by me as team leader from 14 July to 7 August 2026. Each entry answers the three Scrum questions:

1. What did I complete since the last stand-up?
2. What am I planning to complete between now and the next stand-up?
3. What are my impediments (risks or problems)?

The log covers the planning weeks before development and the first three sprints (see the [Sprint Backlog]({{ site.baseurl }}/agile/sprint-backlog/)).


### Week 1: 14 to 20 July

| Date | Completed since last stand-up | Planned next | Impediments |
|---|---|---|---|
| Tue 14 Jul | Revised on what the PFP business idea was | Prepare PowerPoint for presentation | None |
| Wed 15 Jul | Prepare PowerPoint slides for presentation | Preparing for presentation | None |
| Thu 16 Jul | Presentation | User stories for the SafeGuard mobile app | None |
| Fri 17 Jul | User stories for the SafeGuard mobile app | Project requirements of the project | None |
| Sat 18 Jul | Nothing was done | Complete project requirements from previous day | None |
| Sun 19 Jul | Project requirements | Decide on tech stack | Slow network; difficult to communicate online |
| Mon 20 Jul | Nothing | Decide on tech stack | Slow network; difficult to communicate online |

### Week 2: 21 to 24 July

| Date | Completed since last stand-up | Planned next | Impediments |
|---|---|---|---|
| Tue 21 Jul | Revised the product backlog | Update product backlog | None |
| Wed 22 Jul | Updated product backlog | Add dates to tasks for product backlog | None |
| Thu 23 Jul | Researched building mobile apps with our chosen tech stack | Update wireframes and start prototyping | None |
| Fri 24 Jul | Updated wireframes | Start setting up project structure | None |

### Week 3: 28 to 31 July

| Date | Completed since last stand-up | Planned next | Impediments |
|---|---|---|---|
| Tue 28 Jul | Updated wireframes | Start frontend development | Time management due to workload from other modules |
| Wed 29 Jul | Started frontend development | Complete login screen for frontend | None |
| Thu 30 Jul | Completed login screen | Complete home screen | None |
| Fri 31 Jul | Home screen for frontend | Complete the registration process screen | None |

### Week 4: 4 to 7 August

| Date | Completed since last stand-up | Planned next | Impediments |
|---|---|---|---|
| Tue 4 Aug | Completed registration screen | Add sprint panel in the Trello board to complete sprint backlog | None |
| Wed 5 Aug | Added sprint board to Trello | Complete brand guide | None |
| Thu 6 Aug | Nothing | Add frontend to GitHub Pages | None |
| Fri 7 Aug | Attempted to add screens to GitHub Pages | Fix issues with adding pages to GitHub Pages | Error with adding pages to GitHub Pages |

### Week 5: 11 to 14 August

| Date | Completed since last stand-up | Planned next | Impediments |
|---|---|---|---|
| Tue 11 Aug | Completed the Registration process screen | Complete the Frontend for Security Guard | None |
| Wed 12 Aug | Complete the Frontend for Security Guard | Setup Supabase Database | None |
| Thu 13 Aug | Completed Supabase setup | Complete tables for database | None |
| Fri 14 Aug | Completed tables for database | Adding RLS Policies to the tables | None |

### Week 6: 18 to 21 August

| Date | Completed since last stand-up | Planned next | Impediments |
|---|---|---|---|
| Tue 18 Aug | Adding RLS Policies to the tables | Allow users to view details of a resolved incident | None |
| Wed 19 Aug | Allow users to view details of a resolved incident | Allow guards to receive push notifcaions | None |
| Thu 20 Aug | Allow guards to receive push notifcaions | Cancel a false alarm before the guard departs | None |
| Fri 21 Aug | Cancel a false alarm before the guard departs | Rate the guard's response after an incident is resolved | None |

### Impediments logged

| Date | Impediment | What happened next |
|---|---|---|
| 19 to 20 Jul | Slow network and difficulty communicating online | Tech stack decision was carried over two days; Sprint 1 started on 20 July |
| 28 Jul | Time management due to workload from other modules | Frontend development started the next day (29 Jul) |
| 7 Aug | Error adding pages to GitHub Pages | Carried into the next stand-up as the plan to fix |


## Reflection

The log shows how the project actually went, which didn't go according to the actual plan. The first week was mostly presentation and requirements work, including two days where I recorded that nothing was done. From 11 August the log turns to building: the security guard frontend, then setting up Supabase, the database tables and row level security policies.

The impediments were small. A slow network made it hard to communicate online on 19 and 20 July, module workload hurt my time management on 28 July, and on 7 August I could not add the screens to GitHub Pages. I noticed that I recorded each problem but not always how it was resolved: the GitHub Pages error is last mentioned on 7 August, and by 11 August the plan had moved on. I should have written down the fix so the team could learn from it.

The log also captured the biggest technical decision of the project. We had planned a Java backend, and the entries from 12 to 14 August show the switch to Supabase and the database being built there.