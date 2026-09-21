# Kawan Inap — Hotel Management System

A web-based hotel management system for managing reservations, customers, operational summaries, and authenticated user access.

## Overview

**Kawan Inap Hotel Management System** is a web application designed to simplify hotel reservation management through a centralized dashboard.

The application supports user authentication, reservation CRUD operations, customer management, and operational monitoring. Reservation data is stored persistently using **Supabase PostgreSQL**, while the application is deployed through **Vercel**.

## Preview

<img width="1905" height="912" alt="image" src="https://github.com/user-attachments/assets/5ae08b13-b1fc-4260-90be-5e34b209e305" />
<img width="1898" height="912" alt="image" src="https://github.com/user-attachments/assets/565839ed-085b-4b47-9ba7-df1aed9f756e" />

<img width="1910" height="957" alt="image" src="https://github.com/user-attachments/assets/8960e89c-b32d-4518-a01a-2c4b22ce05b7" />
<img width="1892" height="907" alt="image" src="https://github.com/user-attachments/assets/edd1946d-6b83-4f7a-ae42-9cf94379efa9" />
<img width="1895" height="916" alt="image" src="https://github.com/user-attachments/assets/174ac6e1-ca18-4cd6-be1e-2b6f6d1fd889" />
<img width="1887" height="911" alt="image" src="https://github.com/user-attachments/assets/d83b6891-190d-458f-ab0b-652844f2bd67" />
<img width="1897" height="912" alt="image" src="https://github.com/user-attachments/assets/9c3a2d50-0b1b-4dfc-b4c1-5ee93f7fbfef" />






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
```

## LINK

https://kawan-inap.vercel.app/
