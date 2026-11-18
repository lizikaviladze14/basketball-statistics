# Basketball Statistics Analyser

Python desktop app that collects and visualises NBA player and team statistics.

## Features
- **Player stats:** enter a player's name; a Selenium bot retrieves their per-game stats from basketball-reference.com, pandas processes them, and matplotlib shows charts (scoring, shooting, defence, playing time).
- **Team stats:** scrapes NBA champions and MVP winners with BeautifulSoup, stores them in SQLite, and charts playoff wins and MVPs per team.
- **MVP counter:** enter a team name to see how many MVPs it had (1956–2021).

## Tech
Python 3.8 · PyQt5 · Selenium · BeautifulSoup · pandas · matplotlib · SQLite

## Authors
Joint university project by [Lizi Kaviladze](https://github.com/lizikaviladze14) and [Andria Inasaridze](https://github.com/andriainasaridze), 2022.

My contribution: team-statistics pipeline (MVP scraping, SQLite storage, pandas analysis, team charts) and the main GUI integration.

Originally hosted at https://github.com/andriainasaridze/Basketball_Stats
