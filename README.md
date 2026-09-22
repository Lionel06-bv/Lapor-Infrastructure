# Laporin: Infrastructure Damage Reporting Platform

A citizen reporting platform for road and public infrastructure damage, developed as a PKM-KC (Program Kreativitas Mahasiswa - Karsa Cipta) proposal and as the Software Engineering course final project at BINUS University.

## Problem and goal

Road damage such as potholes, cracks, broken street lighting, damaged traffic signs, and clogged drainage often goes unreported for a long time because there is no fast, structured, and well documented way for citizens to report it. Laporin lets citizens submit a report with a photo, a GPS location pinned through the Google Maps API, a damage category, and an urgency level, then track the status of that report over time. An admin dashboard lets the relevant authority verify reports, manage them, and monitor the spread of damage across a live map.

## Features

- Citizen mobile app to submit and track infrastructure damage reports
- Photo upload as evidence of the reported condition
- Location pinning through the Google Maps API
- Damage classification by category and severity (low, medium, high)
- Report status tracking for citizens
- Admin dashboard for verifying, managing, and monitoring reports in real time

## Tech stack

- **Mobile app**: Flutter (Dart), tested with an Android emulator
- **Admin dashboard**: React with Vite
- **Backend**: NestJS with Prisma
- **Database, auth, and storage**: Supabase
- **Design**: high fidelity prototypes in Figma

## Repository structure

- `mobile/`: the Flutter app citizens use to submit and track reports
- `admin-web/`: the React admin dashboard for verifying and managing reports
- `backend/`: the API and database layer

