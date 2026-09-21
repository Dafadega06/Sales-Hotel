# Kawan Inap — Hotel Management System

A web-based hotel management system for managing reservations, customers, operational summaries, and authenticated user access.

## Overview

**Kawan Inap Hotel Management System** is a web application designed to simplify hotel reservation management through a centralized dashboard.

The application supports user authentication, reservation CRUD operations, customer management, and operational monitoring. Reservation data is stored persistently using **Supabase PostgreSQL**, while the application is deployed through **Vercel**.

## Preview

### Dashboard

<p align="center">
  <img src="./docs/screenshots/dashboard.png" alt="Dashboard" width="90%">
</p>

### Reservation Management

<table>
  <tr>
    <td width="50%">
      <img src="./docs/screenshots/reservation-list.png" alt="Reservation List">
      <p align="center"><strong>Reservation List</strong></p>
    </td>
    <td width="50%">
      <img src="./docs/screenshots/add-reservation.png" alt="Add Reservation">
      <p align="center"><strong>Add Reservation</strong></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="./docs/screenshots/edit-reservation.png" alt="Edit Reservation">
      <p align="center"><strong>Edit Reservation</strong></p>
    </td>
    <td width="50%">
      <img src="./docs/screenshots/reservation-detail.png" alt="Reservation Detail">
      <p align="center"><strong>Reservation Detail</strong></p>
    </td>
  </tr>
</table>

### Analytics

<p align="center">
  <img src="./docs/screenshots/revenue-chart.png" alt="Revenue Chart" width="90%">
</p>

### Search & Filtering

<p align="center">
  <img src="./docs/screenshots/reservation-search.png" alt="Search and Filter" width="90%">
</p>

### Customer Management

<p align="center">
  <img src="./docs/screenshots/customers.png" alt="Customers" width="90%">
</p>

### Settings

<p align="center">
  <img src="./docs/screenshots/settings.png" alt="Settings" width="90%">
</p>

## Key Features

- User registration and login
- Supabase authentication and session management
- Protected application routes
- Create, view, edit, and delete reservations
- Reservation status management
- Customer directory
- Revenue and room summary
- Revenue trend visualization
- Search and reservation filtering
- Responsive dashboard interface

## Technology Stack

- **Frontend:** React + TypeScript
- **Build Tool:** Vite
- **Authentication:** Supabase Auth
- **Database:** Supabase PostgreSQL
- **Routing:** React Router
- **Charts:** Recharts
- **Icons:** Lucide React
- **Deployment:** Vercel
- **Version Control:** Git & GitHub

## Architecture

```text
User
  ↓
React Application
  ↓
Supabase Auth
  ↓
Supabase PostgreSQL
  ↓
Reservation Data
  ↓
Dashboard / Customers / Orders
