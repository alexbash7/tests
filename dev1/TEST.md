# Test Assignment: Companies Data Scraper

## ⏱ Test Rules & Environment
- **Time limit:** 45 minutes. Stop exactly when the time is up, even if the task is incomplete.
- **AI-Driven:** AI coding tools are **mandatory**. All code must be generated using AI. No manual code writing.
- **Environment:** You have a fully provisioned Ubuntu server. You can install any dependencies, packages, and libraries you need.
- **Language:** Python or Node.js.

## Task

Create a script that collects company data from this Crunchbase page:

https://www.crunchbase.com/discover/saved/companies/414e9c05-7475-48d9-9082-9c0b293cfb79

**Requirements:**
- Use the internal API endpoint that the page uses to load data
- **Input:** Accept a start date as a command-line parameter (e.g., `2024-01-01`). The script should collect data for each day from that date until today.
- Collect the following fields: **Organization Name**, **Description**, **Founded Date**
- Save collected data to a local file (CSV or JSON)
- If the script crashes or is stopped, it should be able to continue from where it left off
- The script should be production-ready

When time is up, just stop wherever you are
