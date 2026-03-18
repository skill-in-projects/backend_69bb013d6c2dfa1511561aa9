# FoodRoute - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69bb013d6c2dfa1511561aa9_user:6L%21HO6T8PKWh9R3Bl%40EhE%40%26%40qiBEkuoU@ep-crimson-mountain-ajw23e8g.c-3.us-east-2.aws.neon.tech:5432/AppDB_69bb013d6c2dfa1511561aa9?sslmode=require`

## Web API

**WebApi URL:** https://webapi69bb013d6c2dfa1511561aa9-production.up.railway.app

**Swagger API Tester URL:** https://webapi69bb013d6c2dfa1511561aa9-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
