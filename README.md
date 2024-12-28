# Attacker Endpoints
My personal resume site gets scanned a lot. To me, this is interesting data. It might also be interesting to you. Feel free to use this to add a catch-all to your server to mess with said bots ;)

This list gets updated daily based on data gathered on naamloos.dev through a catch-all endpoint. This list may contain otherwise valid endpoints, for example when a mastodon server does not properly send their host.

## Soon ™️
At this moment, the list is not yet being populated. I want to automate this process by pushing an update daily. Data is being gathered with a catch-all on `naamloos.dev`.

## Format
The file `endpoints.json` contains a JSON array with objects that contain the following fields:

| Field | Type | Description |
|-------|------|-------------|
| endpoint | string | Endpoint that the bot tried to call |
| method | string | HTTP method: `GET`, `HEAD`, `POST`, `PUT`, `DELETE`, `CONNECT`, `OPTIONS`, `TRACE`, `PATCH` |
| occurences | integer | Amount of occurences at the time of updating |
