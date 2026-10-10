# TrainStreak — Technical Design

---

## 1. Problem & Scope

### 1.1 Problem
- People find it hard to track their progress on a workout to workout basis, progress is often slow and not visible week to week, even if it's real without a record people can't tell the difference from a plateau and slow progress, abandoning their training that was working

### 1.2 Product
- A training log which records what workout you performed and shows whether you're actually improving from previous logs

### 1.3 User usage
- The user chooses a workout they are currently performing or have performed on a given day and input the specifics for that workout Example: Bench Press 40kg x 8 x 3 on 10 Oct

### 1.4 Solution
- Then a timeline of performance is established where the user can check on a weekly/monthly/yearly basis how are they progressing strength or endurance-wise on a given workout

### 1.5 User Base
- Self-hosted and intended for 3-5 users training a few times a week

### 1.6 Out of Scope
- Social features, nutrition, wearables, coaching, payments - self-developed app intended for personal and friend use currently

---

## 2. Stack Constraints

### 2.1 Specific Exlusions
- Kotlin, Javalin, Vue, Bootsrap, Maven, OpenShift, JUnit 5, Unirest, Exposed, ( exception: Postgres ) were not used as i am creating / have created a "HealthTracker" app for my MSs "Agile Software Development" course with the use of this stack. Making sure these two projects don't look too similar to one another as they solve for different problem and ensure I become familiarised with a wider range of frameworks, libraries and languages.

### 2.2 Current Stack 

| Category | Choice | Status | Reason |
|---|---|---|---|
| Language / runtime | C# / .NET 10 | Decided | Deepening my strongest existing skill from my internship in a new context
| API Framework | ASP.NET Core Minimal APIs | Decided | No benefit in a second server side language
| Local orchestration | Docker Desktop + Compose | Decided | Same container definition serves local dev and a host later |
| Database | PostgreSQL (Docker) | Decided | Smaller container size for local PC
| Frontend Tooling | Node.js + npm | Decided | Required to run Vite
| Frontend Stack | React / TypeScript / Vite | Decided | Building on prior experience 
| API Description | OpenAPI | Decided | REST API documentation with API inspection and Testing
| Testing | xUnit v3 | Decided | Standard .NET test template
| CI/CD | GitHub Actions | Decided | Free and unlimited for public repositories | 

### 2.3 Deferred / Dropped
---

## 3. Domain Model

---

## 4. Solution & Project Structure

---

## 5. Mobile Roadmap

---