# APA Discord Bot

## What does this project aim to do?

This APA bot is meant to login to the APA poolplayers website using your credentials to then scrape team stats and upcoming week's matchups. CSV files will be generated for 8-ball and 9-ball team stats for stat tracking over time (if you're into that). It will also grab the upcoming matchup details and create an html file where a screenshot will be taken and then posted to the discord server channel of your choosing.

## Planned Features

- CSV files for your team stats
    - 8-ball stats
    - 9-ball stats
- HTML file creation with custom CSS for matchup screenshot
- Snapshot of HTML page and post into team discord channel
- Optimized team combos to reach 23 team handicap

## Note

This program utilizes .env file for storing username, password, bot token, etc. Highly recommend using a venv after cloning this project.