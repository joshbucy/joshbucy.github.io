# Nebrasketball NCAA odds machine
Tracking tournament odds for the Nebraska basketball team

- Scrapes a few data sources for rankings and record projections. (Requests, Selenium, BeautifulSoup)
- Pulls them into an HTML table. (.getJSON())
- Calculates chance of making the tournament, assigns score based on each rating. (Educated guesswork)
- Assigns weighted average to scores. (Math)
- Powers a needle gauge, a la #nytneedle from Election Night 2016. (Google Charts)
- Updates self automatically every couple hours. (cron)
