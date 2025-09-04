# OpenLift — Open‑Source, Self‑Hosted Workout Tracker

Fitness workout logger built by lifters for lifters. Privacy‑first, open‑source, and designed to feel like a modern Excel sheet for the gym: fast, structured, and distraction‑free.

---

## What We’re Building

OpenLift is a simple, open‑source fitness tracker designed for fast, between‑sets logging and clear progress tracking. It’s a self‑hosted workout tracker you can run yourself or use with our hosted service.

- Self‑hosted, privacy‑first workout logger — your data stays yours
- Strength training and powerlifting focused (reps, weight, RPE, notes)
- Clean workout analytics: volume, intensity, PRs, 1RM estimates
- Offline‑first mobile app: log full workouts without internet; auto‑sync when you’re back online
- Excel‑like speed: quick‑add sets, copy last set, smart defaults, and sheet‑style flow on mobile
- Workout planner: build weekly splits and session templates without the spreadsheet juggling

---

## Why Not Excel (or Paper) Anymore?

Lots of lifters still use paper or a fitness Excel sheet because it’s fast. OpenLift keeps that “spreadsheet speed” but upgrades the experience:

- One‑tap logging with sheet‑like, row‑by‑row entry
- Copy last set, auto‑fill weights, and smart defaults
- PR detection, weekly volume summaries, and simple charts
- Program templates (PPL, 5×5, DUP) and progression helpers
- Clean history you can actually search and review on mobile

If you track training in Excel, you’ll feel at home — OpenLift is the modern, mobile spreadsheet for workouts.

---

## Planner (Workout Planner)

Plan your training week like you would in a spreadsheet — minus the manual hassle.

- Create weekly splits (PPL, Upper/Lower, 5×5, DUP)
- Drag‑and‑drop sessions, reuse templates, and keep notes
- See planned vs completed work at a glance
- Optional reminders; always private and under your control
- Periodization support: plan blocks (accumulation, intensification, deload, peak) and schedule them across weeks

---

## Progression Playbook (Optional, Math Included)

Not everyone wants to fiddle with formulas. The Progression Playbook suggests what to do next so you can focus on lifting:

- Auto‑suggest next weights/reps based on your recent sets and RPE
- Supports common styles: linear, double progression, rep targets, RPE‑based
- Smart guardrails for PRs, plate jumps, and sensible deloads when progress stalls
- Always optional — override anytime and log exactly what you did
- Periodization‑aware: respects planned deload/peak weeks when making suggestions

Set your guardrails once; OpenLift handles the math and tracking.

---

## Philosophy

No dark patterns, no engagement tricks, no data selling. Core features remain free when you self‑host. Optional paid add‑ons (advanced analytics, cloud backup, integrations) help keep the project sustainable.

---

## Tech We Use

- Fastify + TypeScript backend with GraphQL
- MongoDB for storage; object storage for media
- Built for observability, reliability, and portability (Docker‑ready)
 - Flutter for iOS/Android mobile app
 - Riverpod for predictable, testable state management
 - Isar embedded database for fast, fully offline workout storage and sync

---

## Follow Along

- Website: https://openlift.app
- Docs: https://openlift.dev/docs/overview/introduction
- Discord: https://discord.gg/SBUPVfMH47
- GitHub: https://github.com/openlift
- Email: support@openlift.app

We’re building in public and aiming for our first major release in 2025. If “open‑source fitness tracker,” “workout logger,” or “self‑hosted workout tracker” speaks to you — come hang out, kick the tires, or contribute.
