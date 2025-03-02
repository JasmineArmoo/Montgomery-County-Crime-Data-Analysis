# Montgomery County Crime Data Analysis

## Project Overview
This project analyzes crime trends in Montgomery County, Maryland, using a relational database. The database tracks incidents, locations, types of crimes, and other relevant data to help law enforcement, policymakers, and the public understand crime patterns.

## Database Structure
The database consists of 8 tables:
- `incident`: Tracks crime incidents with date, time, and location.
- `location`: Stores location details (coordinates, police district, address, zip code).
- `crimes`: Lists types of crimes (e.g., "Crime Against Property").
- `offenses`: Provides offense codes and descriptions.
- `nibrs`: Tracks NIBRS (National Incident-Based Reporting System) codes.
- Linking tables (`crime_incident`, `offense_incident`, `nibrs_incident`) connect incidents to crimes, offenses, and NIBRS codes.

## Queries
Five queries were created to analyze the data:
1. **Query 1:** Sorts incidents by location.
2. **Query 2:** Identifies frequent NIBRS codes.
3. **Query 3:** Filters lesser offenses (offense codes > 5000).
4. **Query 4:** Counts crimes by date and time.
5. **Query 5:** Focuses on crimes against property and their timing.

## How to Use
1. Download the SQL files (`annotated-team_6_montgomeryCountyCrime_backup.sql` and `annotated-team_6_montgomeryCountyCrime_queries.sql`).
2. Restore the database using the backup file.
3. Run the queries to analyze the data.

## Future Work
- Expand the database to include other counties.
- Regularly update the database with new crime data.
- Create a database to track police patrols and their impact on crime rates.
