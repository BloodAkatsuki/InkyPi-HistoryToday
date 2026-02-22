# InkyPi This Day in History Plugin

An [InkyPi](https://github.com/fatihak/InkyPi) plugin that displays historical events that happened on today's date, pulled from the Wikipedia On This Day API.

## Screenshot

<!-- Add a screenshot of the plugin running on your display here -->

## Features

- Fetches real historical events for today's month and day from Wikipedia
- Randomly picks from available events for variety on each refresh
- Configurable number of events shown (3, 5, or 7)

## APIs Used

- **[Wikipedia On This Day API](https://en.wikipedia.org/api/rest_v1/#/Feed/onThisDay)** — free, no API key required.
  - `GET /api/rest_v1/feed/onthisday/events/{month}/{day}`

## Installation

Run the following command on your Raspberry Pi:

```bash
inkypi plugin install history_today https://github.com/BloodAkatsuki/InkyPi-HistoryToday
```

## Configuration

| Setting | Description |
|---|---|
| **Number of Events** | How many historical events to display (3, 5, or 7) |

## Status

Actively maintained.
