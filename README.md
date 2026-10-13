# Student Project Tracker

## Project Overview

This is a hands-on web app development **cloud variant** of the Student Project Tracker.

## Technology Stack

* **Hosting:** Vercel
* **Database:** Supabase PostgreSQL
* **Database Schema:** `schema.sql`

## Local Setup and Rehearsal

Follow these steps to run the application locally.

### 1. Install Dependencies

Run the following command in the project terminal:

```powershell
npm.cmd ci
```

### 2. Configure Environment Variables

Create a private `.env` file using `.env.example` as the template.

Configure the required environment variables, including `DATABASE_URL`, with the appropriate values.

**Important:** Keep `.env` private. Never commit real credentials or expose `DATABASE_URL` in frontend or browser-side code.

### 3. Set Up the Database

Use `schema.sql` to create the required table in the Supabase PostgreSQL database.

Ensure the database connection is configured correctly before starting the application.

### 4. Start the Application

Run the following command:

```powershell
npm.cmd start
```

## Deployment

The application is intended to be hosted on **Vercel**, with **Supabase PostgreSQL** used for database storage.

**Hosted URL:** To be added after deployment.

## Demo Access and Data

* The application uses shared demo records.
* There is no sign-in or authentication.
* Users accessing the application may be able to view or modify shared demo data.
* Do not store sensitive or personal information in the demo application.
* Existing local SQLite records are not migrated to Supabase PostgreSQL. The hosted database will contain the records created or loaded in Supabase after database setup.

## Security Notes

* Keep `DATABASE_URL` server-only.
* Store database credentials in private environment variables.
* Do not commit `.env` or expose secrets in frontend JavaScript.
* Use `.env.example` as a template without real credentials.

## Verification Record

No setup, database, or deployment checks are claimed as completed yet. Update this section only after the corresponding checks have actually been run and verified.
