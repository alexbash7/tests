# Test Assignment: Crunchbase Companies Scraper

## Rules
- **Time limit: 45 minutes.** Stop when time is up, even if not finished.
- **AI tools are mandatory.** All coding must be done using AI coding tools. No manual code writing.
- **Environment:** Fully provisioned Ubuntu server. You can install any dependencies, packages, and libraries you need.
- **Language:** Python or Node.js

## Task

Create a script that collects company data from this Crunchbase page:

https://www.crunchbase.com/discover/saved/companies/414e9c05-7475-48d9-9082-9c0b293cfb79

**Requirements:**
- Use the internal API endpoint that the page uses to load data
- Accept a start date as input parameter (e.g. `2026-01-01`). The script should collect data for each day from that date until today.
- Collect the following fields: **Organization Name**, **Description**, **Founded Date**
- Save collected data to a local file (CSV or JSON)
- If the script crashes or is stopped, it should be able to continue from where it left off
- The script should be production-ready

When finished (or when time is up), just stop — everything stays in the environment for review.
